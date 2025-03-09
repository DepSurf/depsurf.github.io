# Struct: <code>xdp_umem</code>

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
struct xdp_umem {
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    struct xdp_umem_page * pages;
    struct xdp_umem_props props;
    u32 headroom;
    u32 chunk_size_nohr;
    struct user_struct * user;
    struct pid * pid;
    long unsigned int address;
    refcount_t users;
    struct work_struct work;
    struct page * * pgs;
    u32 npgs;
    struct net_device * dev;
    u16 queue_id;
    bool zc;
    spinlock_t xsk_list_lock;
    struct list_head xsk_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct xdp_umem {
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    struct xdp_umem_page * pages;
    u64 chunk_mask;
    u64 size;
    u32 headroom;
    u32 chunk_size_nohr;
    struct user_struct * user;
    struct pid * pid;
    long unsigned int address;
    refcount_t users;
    struct work_struct work;
    struct page * * pgs;
    u32 npgs;
    struct net_device * dev;
    struct xdp_umem_fq_reuse * fq_reuse;
    u16 queue_id;
    bool zc;
    spinlock_t xsk_list_lock;
    struct list_head xsk_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct xdp_umem {
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    struct xdp_umem_page * pages;
    u64 chunk_mask;
    u64 size;
    u32 headroom;
    u32 chunk_size_nohr;
    struct user_struct * user;
    long unsigned int address;
    refcount_t users;
    struct work_struct work;
    struct page * * pgs;
    u32 npgs;
    int id;
    struct net_device * dev;
    struct xdp_umem_fq_reuse * fq_reuse;
    u16 queue_id;
    bool zc;
    spinlock_t xsk_list_lock;
    struct list_head xsk_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct xdp_umem {
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    struct xdp_umem_page * pages;
    u64 chunk_mask;
    u64 size;
    u32 headroom;
    u32 chunk_size_nohr;
    struct user_struct * user;
    long unsigned int address;
    refcount_t users;
    struct work_struct work;
    struct page * * pgs;
    u32 npgs;
    u16 queue_id;
    u8 need_wakeup;
    u8 flags;
    int id;
    struct net_device * dev;
    struct xdp_umem_fq_reuse * fq_reuse;
    bool zc;
    spinlock_t xsk_list_lock;
    struct list_head xsk_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xdp_umem {
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    struct xsk_buff_pool * pool;
    u64 size;
    u32 headroom;
    u32 chunk_size;
    struct user_struct * user;
    refcount_t users;
    struct work_struct work;
    struct page * * pgs;
    u32 npgs;
    u16 queue_id;
    u8 need_wakeup;
    u8 flags;
    int id;
    struct net_device * dev;
    bool zc;
    spinlock_t xsk_tx_list_lock;
    struct list_head xsk_tx_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct xdp_umem {
    void * addrs;
    u64 size;
    u32 headroom;
    u32 chunk_size;
    u32 chunks;
    u32 npgs;
    struct user_struct * user;
    refcount_t users;
    u8 flags;
    bool zc;
    struct page * * pgs;
    int id;
    struct list_head xsk_dma_list;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct xdp_umem {
    void * addrs;
    u64 size;
    u32 headroom;
    u32 chunk_size;
    u32 chunks;
    u32 npgs;
    struct user_struct * user;
    refcount_t users;
    u8 flags;
    bool zc;
    struct page * * pgs;
    int id;
    struct list_head xsk_dma_list;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct xdp_umem {
    void * addrs;
    u64 size;
    u32 headroom;
    u32 chunk_size;
    u32 chunks;
    u32 npgs;
    struct user_struct * user;
    refcount_t users;
    u8 flags;
    bool zc;
    struct page * * pgs;
    int id;
    struct list_head xsk_dma_list;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct xdp_umem {
    void * addrs;
    u64 size;
    u32 headroom;
    u32 chunk_size;
    u32 chunks;
    u32 npgs;
    struct user_struct * user;
    refcount_t users;
    u8 flags;
    bool zc;
    struct page * * pgs;
    int id;
    struct list_head xsk_dma_list;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct xdp_umem {
    void * addrs;
    u64 size;
    u32 headroom;
    u32 chunk_size;
    u32 chunks;
    u32 npgs;
    struct user_struct * user;
    refcount_t users;
    u8 flags;
    bool zc;
    struct page * * pgs;
    int id;
    struct list_head xsk_dma_list;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct xdp_umem {
    void * addrs;
    u64 size;
    u32 headroom;
    u32 chunk_size;
    u32 chunks;
    u32 npgs;
    struct user_struct * user;
    refcount_t users;
    u8 flags;
    bool zc;
    struct page * * pgs;
    int id;
    struct list_head xsk_dma_list;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct xdp_umem {
    void * addrs;
    u64 size;
    u32 headroom;
    u32 chunk_size;
    u32 chunks;
    u32 npgs;
    struct user_struct * user;
    refcount_t users;
    u8 flags;
    u8 tx_metadata_len;
    bool zc;
    struct page * * pgs;
    int id;
    struct list_head xsk_dma_list;
    struct work_struct work;
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
struct xdp_umem {
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    struct xdp_umem_page * pages;
    u64 chunk_mask;
    u64 size;
    u32 headroom;
    u32 chunk_size_nohr;
    struct user_struct * user;
    long unsigned int address;
    refcount_t users;
    struct work_struct work;
    struct page * * pgs;
    u32 npgs;
    u16 queue_id;
    u8 need_wakeup;
    u8 flags;
    int id;
    struct net_device * dev;
    struct xdp_umem_fq_reuse * fq_reuse;
    bool zc;
    spinlock_t xsk_list_lock;
    struct list_head xsk_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct xdp_umem {
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    struct xdp_umem_page * pages;
    u64 chunk_mask;
    u64 size;
    u32 headroom;
    u32 chunk_size_nohr;
    struct user_struct * user;
    long unsigned int address;
    refcount_t users;
    struct work_struct work;
    struct page * * pgs;
    u32 npgs;
    u16 queue_id;
    u8 need_wakeup;
    u8 flags;
    int id;
    struct net_device * dev;
    struct xdp_umem_fq_reuse * fq_reuse;
    bool zc;
    spinlock_t xsk_list_lock;
    struct list_head xsk_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct xdp_umem {
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    struct xdp_umem_page * pages;
    u64 chunk_mask;
    u64 size;
    u32 headroom;
    u32 chunk_size_nohr;
    struct user_struct * user;
    long unsigned int address;
    refcount_t users;
    struct work_struct work;
    struct page * * pgs;
    u32 npgs;
    u16 queue_id;
    u8 need_wakeup;
    u8 flags;
    int id;
    struct net_device * dev;
    struct xdp_umem_fq_reuse * fq_reuse;
    bool zc;
    spinlock_t xsk_list_lock;
    struct list_head xsk_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct xdp_umem {
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    struct xdp_umem_page * pages;
    u64 chunk_mask;
    u64 size;
    u32 headroom;
    u32 chunk_size_nohr;
    struct user_struct * user;
    long unsigned int address;
    refcount_t users;
    struct work_struct work;
    struct page * * pgs;
    u32 npgs;
    u16 queue_id;
    u8 need_wakeup;
    u8 flags;
    int id;
    struct net_device * dev;
    struct xdp_umem_fq_reuse * fq_reuse;
    bool zc;
    spinlock_t xsk_list_lock;
    struct list_head xsk_list;
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
struct xdp_umem {
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    struct xdp_umem_page * pages;
    u64 chunk_mask;
    u64 size;
    u32 headroom;
    u32 chunk_size_nohr;
    struct user_struct * user;
    long unsigned int address;
    refcount_t users;
    struct work_struct work;
    struct page * * pgs;
    u32 npgs;
    u16 queue_id;
    u8 need_wakeup;
    u8 flags;
    int id;
    struct net_device * dev;
    struct xdp_umem_fq_reuse * fq_reuse;
    bool zc;
    spinlock_t xsk_list_lock;
    struct list_head xsk_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct xdp_umem {
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    struct xdp_umem_page * pages;
    u64 chunk_mask;
    u64 size;
    u32 headroom;
    u32 chunk_size_nohr;
    struct user_struct * user;
    long unsigned int address;
    refcount_t users;
    struct work_struct work;
    struct page * * pgs;
    u32 npgs;
    u16 queue_id;
    u8 need_wakeup;
    u8 flags;
    int id;
    struct net_device * dev;
    struct xdp_umem_fq_reuse * fq_reuse;
    bool zc;
    spinlock_t xsk_list_lock;
    struct list_head xsk_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct xdp_umem {
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    struct xdp_umem_page * pages;
    u64 chunk_mask;
    u64 size;
    u32 headroom;
    u32 chunk_size_nohr;
    struct user_struct * user;
    long unsigned int address;
    refcount_t users;
    struct work_struct work;
    struct page * * pgs;
    u32 npgs;
    u16 queue_id;
    u8 need_wakeup;
    u8 flags;
    int id;
    struct net_device * dev;
    struct xdp_umem_fq_reuse * fq_reuse;
    bool zc;
    spinlock_t xsk_list_lock;
    struct list_head xsk_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct xdp_umem {
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    struct xdp_umem_page * pages;
    u64 chunk_mask;
    u64 size;
    u32 headroom;
    u32 chunk_size_nohr;
    struct user_struct * user;
    long unsigned int address;
    refcount_t users;
    struct work_struct work;
    struct page * * pgs;
    u32 npgs;
    u16 queue_id;
    u8 need_wakeup;
    u8 flags;
    int id;
    struct net_device * dev;
    struct xdp_umem_fq_reuse * fq_reuse;
    bool zc;
    spinlock_t xsk_list_lock;
    struct list_head xsk_list;
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
struct xdp_umem {
    struct xsk_queue * fq;
    struct xsk_queue * cq;
    struct xdp_umem_page * pages;
    struct xdp_umem_props props;
    u32 headroom;
    u32 chunk_size_nohr;
    struct user_struct * user;
    struct pid * pid;
    long unsigned int address;
    refcount_t users;
    struct work_struct work;
    struct page * * pgs;
    u32 npgs;
    struct net_device * dev;
    u16 queue_id;
    bool zc;
    spinlock_t xsk_list_lock;
    struct list_head xsk_list;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 chunk_mask</code>
</li>
<li>
<b>Field added. </b>
<code>u64 size</code>
</li>
<li>
<b>Field added. </b>
<code>struct xdp_umem_fq_reuse * fq_reuse</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xdp_umem_props props</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int id</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pid * pid</code>
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
<code>u8 need_wakeup</code>
</li>
<li>
<b>Field added. </b>
<code>u8 flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct xsk_buff_pool * pool</code>
</li>
<li>
<b>Field added. </b>
<code>u32 chunk_size</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t xsk_tx_list_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head xsk_tx_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xdp_umem_page * pages</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 chunk_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 chunk_size_nohr</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int address</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xdp_umem_fq_reuse * fq_reuse</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t xsk_list_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head xsk_list</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * addrs</code>
</li>
<li>
<b>Field added. </b>
<code>u32 chunks</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head xsk_dma_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xsk_queue * fq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xsk_queue * cq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xsk_buff_pool * pool</code>
</li>
<li>
<b>Field removed. </b>
<code>u16 queue_id</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 need_wakeup</code>
</li>
<li>
<b>Field removed. </b>
<code>struct net_device * dev</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t xsk_tx_list_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head xsk_tx_list</code>
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
<code>u8 tx_metadata_len</code>
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
