# Struct: <code>xdp_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    u16 queue_id;
    struct xsk_queue * tx;
    struct list_head list;
    bool zc;
    struct mutex mutex;
    spinlock_t tx_completion_lock;
    u64 rx_dropped;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    u16 queue_id;
    struct xsk_queue * tx;
    struct list_head list;
    bool zc;
    struct mutex mutex;
    spinlock_t tx_completion_lock;
    u64 rx_dropped;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    u16 queue_id;
    bool zc;
    enum (anon) state;
    struct mutex mutex;
    struct xsk_queue * tx;
    struct list_head list;
    spinlock_t tx_completion_lock;
    spinlock_t rx_lock;
    u64 rx_dropped;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    u16 queue_id;
    bool zc;
    enum (anon) state;
    struct mutex mutex;
    struct xsk_queue * tx;
    struct list_head list;
    spinlock_t tx_completion_lock;
    spinlock_t rx_lock;
    u64 rx_dropped;
    struct list_head map_list;
    spinlock_t map_list_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    u16 queue_id;
    bool zc;
    enum (anon) state;
    struct mutex mutex;
    struct xsk_queue * tx;
    struct list_head list;
    spinlock_t tx_completion_lock;
    spinlock_t rx_lock;
    u64 rx_dropped;
    struct list_head map_list;
    spinlock_t map_list_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    struct xsk_buff_pool * pool;
    u16 queue_id;
    bool zc;
    enum (anon) state;
    struct xsk_queue * tx;
    struct list_head tx_list;
    spinlock_t rx_lock;
    u64 rx_dropped;
    u64 rx_queue_full;
    struct list_head map_list;
    spinlock_t map_list_lock;
    struct mutex mutex;
    struct xsk_queue * fq_tmp;
    struct xsk_queue * cq_tmp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    struct xsk_buff_pool * pool;
    u16 queue_id;
    bool zc;
    enum (anon) state;
    struct xsk_queue * tx;
    struct list_head tx_list;
    spinlock_t rx_lock;
    u64 rx_dropped;
    u64 rx_queue_full;
    struct list_head map_list;
    spinlock_t map_list_lock;
    struct mutex mutex;
    struct xsk_queue * fq_tmp;
    struct xsk_queue * cq_tmp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    struct xsk_buff_pool * pool;
    u16 queue_id;
    bool zc;
    enum (anon) state;
    struct xsk_queue * tx;
    struct list_head tx_list;
    spinlock_t rx_lock;
    u64 rx_dropped;
    u64 rx_queue_full;
    struct list_head map_list;
    spinlock_t map_list_lock;
    struct mutex mutex;
    struct xsk_queue * fq_tmp;
    struct xsk_queue * cq_tmp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    struct xsk_buff_pool * pool;
    u16 queue_id;
    bool zc;
    enum (anon) state;
    struct xsk_queue * tx;
    struct list_head tx_list;
    spinlock_t rx_lock;
    u64 rx_dropped;
    u64 rx_queue_full;
    struct list_head map_list;
    spinlock_t map_list_lock;
    struct mutex mutex;
    struct xsk_queue * fq_tmp;
    struct xsk_queue * cq_tmp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    struct xsk_buff_pool * pool;
    u16 queue_id;
    bool zc;
    enum (anon) state;
    struct xsk_queue * tx;
    struct list_head tx_list;
    spinlock_t rx_lock;
    u64 rx_dropped;
    u64 rx_queue_full;
    struct list_head map_list;
    spinlock_t map_list_lock;
    struct mutex mutex;
    struct xsk_queue * fq_tmp;
    struct xsk_queue * cq_tmp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    struct xsk_buff_pool * pool;
    u16 queue_id;
    bool zc;
    enum (anon) state;
    struct xsk_queue * tx;
    struct list_head tx_list;
    spinlock_t rx_lock;
    u64 rx_dropped;
    u64 rx_queue_full;
    struct list_head map_list;
    spinlock_t map_list_lock;
    struct mutex mutex;
    struct xsk_queue * fq_tmp;
    struct xsk_queue * cq_tmp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    struct xsk_buff_pool * pool;
    u16 queue_id;
    bool zc;
    bool sg;
    enum (anon) state;
    struct xsk_queue * tx;
    struct list_head tx_list;
    u32 tx_budget_spent;
    spinlock_t rx_lock;
    u64 rx_dropped;
    u64 rx_queue_full;
    struct sk_buff * skb;
    struct list_head map_list;
    spinlock_t map_list_lock;
    struct mutex mutex;
    struct xsk_queue * fq_tmp;
    struct xsk_queue * cq_tmp;
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
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    u16 queue_id;
    bool zc;
    enum (anon) state;
    struct mutex mutex;
    struct xsk_queue * tx;
    struct list_head list;
    spinlock_t tx_completion_lock;
    spinlock_t rx_lock;
    u64 rx_dropped;
    struct list_head map_list;
    spinlock_t map_list_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    u16 queue_id;
    bool zc;
    enum (anon) state;
    struct mutex mutex;
    struct xsk_queue * tx;
    struct list_head list;
    spinlock_t tx_completion_lock;
    spinlock_t rx_lock;
    u64 rx_dropped;
    struct list_head map_list;
    spinlock_t map_list_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    u16 queue_id;
    bool zc;
    enum (anon) state;
    struct mutex mutex;
    struct xsk_queue * tx;
    struct list_head list;
    spinlock_t tx_completion_lock;
    spinlock_t rx_lock;
    u64 rx_dropped;
    struct list_head map_list;
    spinlock_t map_list_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    u16 queue_id;
    bool zc;
    enum (anon) state;
    struct mutex mutex;
    struct xsk_queue * tx;
    struct list_head list;
    spinlock_t tx_completion_lock;
    spinlock_t rx_lock;
    u64 rx_dropped;
    struct list_head map_list;
    spinlock_t map_list_lock;
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
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    u16 queue_id;
    bool zc;
    enum (anon) state;
    struct mutex mutex;
    struct xsk_queue * tx;
    struct list_head list;
    spinlock_t tx_completion_lock;
    spinlock_t rx_lock;
    u64 rx_dropped;
    struct list_head map_list;
    spinlock_t map_list_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    u16 queue_id;
    bool zc;
    enum (anon) state;
    struct mutex mutex;
    struct xsk_queue * tx;
    struct list_head list;
    spinlock_t tx_completion_lock;
    spinlock_t rx_lock;
    u64 rx_dropped;
    struct list_head map_list;
    spinlock_t map_list_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    u16 queue_id;
    bool zc;
    enum (anon) state;
    struct mutex mutex;
    struct xsk_queue * tx;
    struct list_head list;
    spinlock_t tx_completion_lock;
    spinlock_t rx_lock;
    u64 rx_dropped;
    struct list_head map_list;
    spinlock_t map_list_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    u16 queue_id;
    bool zc;
    enum (anon) state;
    struct mutex mutex;
    struct xsk_queue * tx;
    struct list_head list;
    spinlock_t tx_completion_lock;
    spinlock_t rx_lock;
    u64 rx_dropped;
    struct list_head map_list;
    spinlock_t map_list_lock;
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct xdp_sock {
    struct sock sk;
    struct xsk_queue * rx;
    struct net_device * dev;
    struct xdp_umem * umem;
    struct list_head flush_node;
    u16 queue_id;
    struct xsk_queue * tx;
    struct list_head list;
    bool zc;
    struct mutex mutex;
    spinlock_t tx_completion_lock;
    u64 rx_dropped;
}
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum (anon) state</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t rx_lock</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head map_list</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t map_list_lock</code>
</li>
</ul>
</details>
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
<code>struct xsk_buff_pool * pool</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head tx_list</code>
</li>
<li>
<b>Field added. </b>
<code>u64 rx_queue_full</code>
</li>
<li>
<b>Field added. </b>
<code>struct xsk_queue * fq_tmp</code>
</li>
<li>
<b>Field added. </b>
<code>struct xsk_queue * cq_tmp</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head list</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t tx_completion_lock</code>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool sg</code>
</li>
<li>
<b>Field added. </b>
<code>u32 tx_budget_spent</code>
</li>
<li>
<b>Field added. </b>
<code>struct sk_buff * skb</code>
</li>
</ul>
</details>
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
