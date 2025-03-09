# Struct: <code>percpu_rw_semaphore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * fast_read_ctr;
    struct rw_semaphore rw_sem;
    atomic_t slow_read_ctr;
    wait_queue_head_t write_waitq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * fast_read_ctr;
    struct rw_semaphore rw_sem;
    atomic_t slow_read_ctr;
    wait_queue_head_t write_waitq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rw_semaphore rw_sem;
    wait_queue_head_t writer;
    int readers_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rw_semaphore rw_sem;
    struct rcuwait writer;
    int readers_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rw_semaphore rw_sem;
    struct rcuwait writer;
    int readers_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rw_semaphore rw_sem;
    struct rcuwait writer;
    int readers_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rw_semaphore rw_sem;
    struct rcuwait writer;
    int readers_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rw_semaphore rw_sem;
    struct rcuwait writer;
    int readers_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rw_semaphore rw_sem;
    struct rcuwait writer;
    int readers_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rcuwait writer;
    wait_queue_head_t waiters;
    atomic_t block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rcuwait writer;
    wait_queue_head_t waiters;
    atomic_t block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rcuwait writer;
    wait_queue_head_t waiters;
    atomic_t block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rcuwait writer;
    wait_queue_head_t waiters;
    atomic_t block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rcuwait writer;
    wait_queue_head_t waiters;
    atomic_t block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rcuwait writer;
    wait_queue_head_t waiters;
    atomic_t block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rcuwait writer;
    wait_queue_head_t waiters;
    atomic_t block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rcuwait writer;
    wait_queue_head_t waiters;
    atomic_t block;
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
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rw_semaphore rw_sem;
    struct rcuwait writer;
    int readers_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rw_semaphore rw_sem;
    struct rcuwait writer;
    int readers_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rw_semaphore rw_sem;
    struct rcuwait writer;
    int readers_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rw_semaphore rw_sem;
    struct rcuwait writer;
    int readers_block;
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
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rw_semaphore rw_sem;
    struct rcuwait writer;
    int readers_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rw_semaphore rw_sem;
    struct rcuwait writer;
    int readers_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rw_semaphore rw_sem;
    struct rcuwait writer;
    int readers_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct percpu_rw_semaphore {
    struct rcu_sync rss;
    unsigned int * read_count;
    struct rw_semaphore rw_sem;
    struct rcuwait writer;
    int readers_block;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int * read_count</code>
</li>
<li>
<b>Field added. </b>
<code>wait_queue_head_t writer</code>
</li>
<li>
<b>Field added. </b>
<code>int readers_block</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int * fast_read_ctr</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t slow_read_ctr</code>
</li>
<li>
<b>Field removed. </b>
<code>wait_queue_head_t write_waitq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>wait_queue_head_t writer</code> ➡️ <code>struct rcuwait writer</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>wait_queue_head_t waiters</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t block</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rw_semaphore rw_sem</code>
</li>
<li>
<b>Field removed. </b>
<code>int readers_block</code>
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
