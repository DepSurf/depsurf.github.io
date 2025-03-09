# Struct: <code>packet_fanout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    struct sock *[256] arr;
    spinlock_t lock;
    atomic_t sk_ref;
    struct packet_type prot_hook;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    struct sock *[256] arr;
    spinlock_t lock;
    atomic_t sk_ref;
    struct packet_type prot_hook;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    struct sock *[256] arr;
    spinlock_t lock;
    atomic_t sk_ref;
    struct packet_type prot_hook;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    struct sock *[256] arr;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    struct sock *[256] arr;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    struct sock *[256] arr;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    struct sock *[256] arr;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    struct sock *[256] arr;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    struct sock *[256] arr;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    struct sock *[256] arr;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u32 max_num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
    struct sock *[0] arr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u32 max_num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
    struct sock *[0] arr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u32 max_num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
    struct sock *[0] arr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u32 max_num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
    struct sock *[0] arr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u32 max_num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
    struct sock *[0] arr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u32 max_num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
    struct sock *[0] arr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u32 max_num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
    struct sock *[0] arr;
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
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    struct sock *[256] arr;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    struct sock *[256] arr;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    struct sock *[256] arr;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    struct sock *[256] arr;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
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
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    struct sock *[256] arr;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    struct sock *[256] arr;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    struct sock *[256] arr;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct packet_fanout {
    possible_net_t net;
    unsigned int num_members;
    u16 id;
    u8 type;
    u8 flags;
    atomic_t rr_cur;
    struct bpf_prog * bpf_prog;
    struct list_head list;
    struct sock *[256] arr;
    spinlock_t lock;
    refcount_t sk_ref;
    struct packet_type prot_hook;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<code>atomic_t sk_ref</code> ➡️ <code>refcount_t sk_ref</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 max_num_members</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct sock *[256] arr</code> ➡️ <code>struct sock *[0] arr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
