# Struct: <code>unix_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex readlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    unsigned char recursion_level;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_t peer_wake;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    unsigned char recursion_level;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_t peer_wake;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    unsigned char recursion_level;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_t peer_wake;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    unsigned char recursion_level;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
    struct scm_stat scm_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
    struct scm_stat scm_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
    struct scm_stat scm_stat;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
    struct scm_stat scm_stat;
    struct sk_buff * oob_skb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
    struct scm_stat scm_stat;
    struct sk_buff * oob_skb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
    struct scm_stat scm_stat;
    struct sk_buff * oob_skb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
    struct scm_stat scm_stat;
    struct sk_buff * oob_skb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
    struct scm_stat scm_stat;
    struct sk_buff * oob_skb;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct unix_sock {
    struct sock sk;
    struct unix_address * addr;
    struct path path;
    struct mutex iolock;
    struct mutex bindlock;
    struct sock * peer;
    struct list_head link;
    atomic_long_t inflight;
    spinlock_t lock;
    long unsigned int gc_flags;
    struct socket_wq peer_wq;
    wait_queue_entry_t peer_wake;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct mutex iolock</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex bindlock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex readlock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>wait_queue_t peer_wake</code> ➡️ <code>wait_queue_entry_t peer_wake</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned char recursion_level</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct scm_stat scm_stat</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct sk_buff * oob_skb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
