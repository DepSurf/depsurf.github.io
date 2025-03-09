# Struct: <code>xsk_buff_pool</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xsk_buff_pool {
    struct xsk_queue * fq;
    struct list_head free_list;
    dma_addr_t * dma_pages;
    struct xdp_buff_xsk * heads;
    u64 chunk_mask;
    u64 addrs_cnt;
    u32 free_list_cnt;
    u32 dma_pages_cnt;
    u32 heads_cnt;
    u32 free_heads_cnt;
    u32 headroom;
    u32 chunk_size;
    u32 frame_len;
    bool dma_need_sync;
    bool unaligned;
    void * addrs;
    struct device * dev;
    struct xdp_buff_xsk *[0] free_heads;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct xsk_buff_pool {
    struct device * dev;
    struct net_device * netdev;
    struct list_head xsk_tx_list;
    spinlock_t xsk_tx_list_lock;
    refcount_t users;
    struct xdp_umem * umem;
    struct work_struct work;
    struct list_head free_list;
    u32 heads_cnt;
    u16 queue_id;
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    dma_addr_t * dma_pages;
    struct xdp_buff_xsk * heads;
    u64 chunk_mask;
    u64 addrs_cnt;
    u32 free_list_cnt;
    u32 dma_pages_cnt;
    u32 free_heads_cnt;
    u32 headroom;
    u32 chunk_size;
    u32 frame_len;
    u8 cached_need_wakeup;
    bool uses_need_wakeup;
    bool dma_need_sync;
    bool unaligned;
    void * addrs;
    spinlock_t cq_lock;
    struct xdp_buff_xsk *[0] free_heads;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct xsk_buff_pool {
    struct device * dev;
    struct net_device * netdev;
    struct list_head xsk_tx_list;
    spinlock_t xsk_tx_list_lock;
    refcount_t users;
    struct xdp_umem * umem;
    struct work_struct work;
    struct list_head free_list;
    u32 heads_cnt;
    u16 queue_id;
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    dma_addr_t * dma_pages;
    struct xdp_buff_xsk * heads;
    u64 chunk_mask;
    u64 addrs_cnt;
    u32 free_list_cnt;
    u32 dma_pages_cnt;
    u32 free_heads_cnt;
    u32 headroom;
    u32 chunk_size;
    u32 frame_len;
    u8 cached_need_wakeup;
    bool uses_need_wakeup;
    bool dma_need_sync;
    bool unaligned;
    void * addrs;
    spinlock_t cq_lock;
    struct xdp_buff_xsk *[0] free_heads;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct xsk_buff_pool {
    struct device * dev;
    struct net_device * netdev;
    struct list_head xsk_tx_list;
    spinlock_t xsk_tx_list_lock;
    refcount_t users;
    struct xdp_umem * umem;
    struct work_struct work;
    struct list_head free_list;
    u32 heads_cnt;
    u16 queue_id;
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    dma_addr_t * dma_pages;
    struct xdp_buff_xsk * heads;
    u64 chunk_mask;
    u64 addrs_cnt;
    u32 free_list_cnt;
    u32 dma_pages_cnt;
    u32 free_heads_cnt;
    u32 headroom;
    u32 chunk_size;
    u32 frame_len;
    u8 cached_need_wakeup;
    bool uses_need_wakeup;
    bool dma_need_sync;
    bool unaligned;
    void * addrs;
    spinlock_t cq_lock;
    struct xdp_buff_xsk *[0] free_heads;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct xsk_buff_pool {
    struct device * dev;
    struct net_device * netdev;
    struct list_head xsk_tx_list;
    spinlock_t xsk_tx_list_lock;
    refcount_t users;
    struct xdp_umem * umem;
    struct work_struct work;
    struct list_head free_list;
    u32 heads_cnt;
    u16 queue_id;
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    dma_addr_t * dma_pages;
    struct xdp_buff_xsk * heads;
    struct xdp_desc * tx_descs;
    u64 chunk_mask;
    u64 addrs_cnt;
    u32 free_list_cnt;
    u32 dma_pages_cnt;
    u32 free_heads_cnt;
    u32 headroom;
    u32 chunk_size;
    u32 chunk_shift;
    u32 frame_len;
    u8 cached_need_wakeup;
    bool uses_need_wakeup;
    bool dma_need_sync;
    bool unaligned;
    void * addrs;
    spinlock_t cq_lock;
    struct xdp_buff_xsk *[0] free_heads;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct xsk_buff_pool {
    struct device * dev;
    struct net_device * netdev;
    struct list_head xsk_tx_list;
    spinlock_t xsk_tx_list_lock;
    refcount_t users;
    struct xdp_umem * umem;
    struct work_struct work;
    struct list_head free_list;
    u32 heads_cnt;
    u16 queue_id;
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    dma_addr_t * dma_pages;
    struct xdp_buff_xsk * heads;
    struct xdp_desc * tx_descs;
    u64 chunk_mask;
    u64 addrs_cnt;
    u32 free_list_cnt;
    u32 dma_pages_cnt;
    u32 free_heads_cnt;
    u32 headroom;
    u32 chunk_size;
    u32 chunk_shift;
    u32 frame_len;
    u8 cached_need_wakeup;
    bool uses_need_wakeup;
    bool dma_need_sync;
    bool unaligned;
    void * addrs;
    spinlock_t cq_lock;
    struct xdp_buff_xsk *[0] free_heads;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct xsk_buff_pool {
    struct device * dev;
    struct net_device * netdev;
    struct list_head xsk_tx_list;
    spinlock_t xsk_tx_list_lock;
    refcount_t users;
    struct xdp_umem * umem;
    struct work_struct work;
    struct list_head free_list;
    u32 heads_cnt;
    u16 queue_id;
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    dma_addr_t * dma_pages;
    struct xdp_buff_xsk * heads;
    struct xdp_desc * tx_descs;
    u64 chunk_mask;
    u64 addrs_cnt;
    u32 free_list_cnt;
    u32 dma_pages_cnt;
    u32 free_heads_cnt;
    u32 headroom;
    u32 chunk_size;
    u32 chunk_shift;
    u32 frame_len;
    u8 cached_need_wakeup;
    bool uses_need_wakeup;
    bool dma_need_sync;
    bool unaligned;
    void * addrs;
    spinlock_t cq_lock;
    struct xdp_buff_xsk *[0] free_heads;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct xsk_buff_pool {
    struct device * dev;
    struct net_device * netdev;
    struct list_head xsk_tx_list;
    spinlock_t xsk_tx_list_lock;
    refcount_t users;
    struct xdp_umem * umem;
    struct work_struct work;
    struct list_head free_list;
    struct list_head xskb_list;
    u32 heads_cnt;
    u16 queue_id;
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    dma_addr_t * dma_pages;
    struct xdp_buff_xsk * heads;
    struct xdp_desc * tx_descs;
    u64 chunk_mask;
    u64 addrs_cnt;
    u32 free_list_cnt;
    u32 dma_pages_cnt;
    u32 free_heads_cnt;
    u32 headroom;
    u32 chunk_size;
    u32 chunk_shift;
    u32 frame_len;
    u8 tx_metadata_len;
    u8 cached_need_wakeup;
    bool uses_need_wakeup;
    bool dma_need_sync;
    bool unaligned;
    bool tx_sw_csum;
    void * addrs;
    spinlock_t cq_lock;
    struct xdp_buff_xsk *[0] free_heads;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct xsk_buff_pool {
    struct xsk_queue * fq;
    struct list_head free_list;
    dma_addr_t * dma_pages;
    struct xdp_buff_xsk * heads;
    u64 chunk_mask;
    u64 addrs_cnt;
    u32 free_list_cnt;
    u32 dma_pages_cnt;
    u32 heads_cnt;
    u32 free_heads_cnt;
    u32 headroom;
    u32 chunk_size;
    u32 frame_len;
    bool dma_need_sync;
    bool unaligned;
    void * addrs;
    struct device * dev;
    struct xdp_buff_xsk *[0] free_heads;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct net_device * netdev</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head xsk_tx_list</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t xsk_tx_list_lock</code>
</li>
<li>
<b>Field added. </b>
<code>refcount_t users</code>
</li>
<li>
<b>Field added. </b>
<code>struct xdp_umem * umem</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct work</code>
</li>
<li>
<b>Field added. </b>
<code>u16 queue_id</code>
</li>
<li>
<b>Field added. </b>
<code>struct xsk_queue * cq</code>
</li>
<li>
<b>Field added. </b>
<code>u8 cached_need_wakeup</code>
</li>
<li>
<b>Field added. </b>
<code>bool uses_need_wakeup</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t cq_lock</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct xdp_desc * tx_descs</code>
</li>
<li>
<b>Field added. </b>
<code>u32 chunk_shift</code>
</li>
</ul>
</details>
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
<code>struct list_head xskb_list</code>
</li>
<li>
<b>Field added. </b>
<code>u8 tx_metadata_len</code>
</li>
<li>
<b>Field added. </b>
<code>bool tx_sw_csum</code>
</li>
</ul>
</details>
</li>
</ul>
