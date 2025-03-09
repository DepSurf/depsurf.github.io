# Struct: <code>page_pool</code>

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
struct page_pool {
    struct callback_head rcu;
    struct page_pool_params p;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct page_pool {
    struct callback_head rcu;
    struct page_pool_params p;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct page_pool {
    struct page_pool_params p;
    u32 pages_state_hold_cnt;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
    atomic_t pages_state_release_cnt;
    refcount_t user_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct page_pool {
    struct page_pool_params p;
    struct delayed_work release_dw;
    void (*)(void *) disconnect;
    long unsigned int defer_start;
    long unsigned int defer_warn;
    u32 pages_state_hold_cnt;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
    atomic_t pages_state_release_cnt;
    refcount_t user_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct page_pool {
    struct page_pool_params p;
    struct delayed_work release_dw;
    void (*)(void *) disconnect;
    long unsigned int defer_start;
    long unsigned int defer_warn;
    u32 pages_state_hold_cnt;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
    atomic_t pages_state_release_cnt;
    refcount_t user_cnt;
    u64 destroy_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct page_pool {
    struct page_pool_params p;
    struct delayed_work release_dw;
    void (*)(void *) disconnect;
    long unsigned int defer_start;
    long unsigned int defer_warn;
    u32 pages_state_hold_cnt;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
    atomic_t pages_state_release_cnt;
    refcount_t user_cnt;
    u64 destroy_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct page_pool {
    struct page_pool_params p;
    struct delayed_work release_dw;
    void (*)(void *) disconnect;
    long unsigned int defer_start;
    long unsigned int defer_warn;
    u32 pages_state_hold_cnt;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
    atomic_t pages_state_release_cnt;
    refcount_t user_cnt;
    u64 destroy_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct page_pool {
    struct page_pool_params p;
    struct delayed_work release_dw;
    void (*)(void *) disconnect;
    long unsigned int defer_start;
    long unsigned int defer_warn;
    u32 pages_state_hold_cnt;
    unsigned int frag_offset;
    struct page * frag_page;
    long int frag_users;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
    atomic_t pages_state_release_cnt;
    refcount_t user_cnt;
    u64 destroy_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct page_pool {
    struct page_pool_params p;
    struct delayed_work release_dw;
    void (*)(void *) disconnect;
    long unsigned int defer_start;
    long unsigned int defer_warn;
    u32 pages_state_hold_cnt;
    unsigned int frag_offset;
    struct page * frag_page;
    long int frag_users;
    u32 xdp_mem_id;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
    atomic_t pages_state_release_cnt;
    refcount_t user_cnt;
    u64 destroy_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct page_pool {
    struct page_pool_params p;
    struct delayed_work release_dw;
    void (*)(void *) disconnect;
    long unsigned int defer_start;
    long unsigned int defer_warn;
    u32 pages_state_hold_cnt;
    unsigned int frag_offset;
    struct page * frag_page;
    long int frag_users;
    u32 xdp_mem_id;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
    atomic_t pages_state_release_cnt;
    refcount_t user_cnt;
    u64 destroy_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct page_pool {
    struct page_pool_params p;
    struct delayed_work release_dw;
    void (*)(void *) disconnect;
    long unsigned int defer_start;
    long unsigned int defer_warn;
    u32 pages_state_hold_cnt;
    unsigned int frag_offset;
    struct page * frag_page;
    long int frag_users;
    struct page_pool_alloc_stats alloc_stats;
    u32 xdp_mem_id;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
    struct page_pool_recycle_stats * recycle_stats;
    atomic_t pages_state_release_cnt;
    refcount_t user_cnt;
    u64 destroy_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct page_pool {
    struct page_pool_params_fast p;
    bool has_init_callback;
    long int frag_users;
    struct page * frag_page;
    unsigned int frag_offset;
    u32 pages_state_hold_cnt;
    struct delayed_work release_dw;
    void (*)(void *) disconnect;
    long unsigned int defer_start;
    long unsigned int defer_warn;
    struct page_pool_alloc_stats alloc_stats;
    u32 xdp_mem_id;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
    struct page_pool_recycle_stats * recycle_stats;
    atomic_t pages_state_release_cnt;
    refcount_t user_cnt;
    u64 destroy_cnt;
    struct page_pool_params_slow slow;
    struct (anon) user;
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
struct page_pool {
    struct page_pool_params p;
    struct delayed_work release_dw;
    void (*)(void *) disconnect;
    long unsigned int defer_start;
    long unsigned int defer_warn;
    u32 pages_state_hold_cnt;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
    atomic_t pages_state_release_cnt;
    refcount_t user_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct page_pool {
    struct page_pool_params p;
    struct delayed_work release_dw;
    void (*)(void *) disconnect;
    long unsigned int defer_start;
    long unsigned int defer_warn;
    u32 pages_state_hold_cnt;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
    atomic_t pages_state_release_cnt;
    refcount_t user_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct page_pool {
    struct page_pool_params p;
    struct delayed_work release_dw;
    void (*)(void *) disconnect;
    long unsigned int defer_start;
    long unsigned int defer_warn;
    u32 pages_state_hold_cnt;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
    atomic_t pages_state_release_cnt;
    refcount_t user_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct page_pool {
    struct page_pool_params p;
    struct delayed_work release_dw;
    void (*)(void *) disconnect;
    long unsigned int defer_start;
    long unsigned int defer_warn;
    u32 pages_state_hold_cnt;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
    atomic_t pages_state_release_cnt;
    refcount_t user_cnt;
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
struct page_pool {
    struct page_pool_params p;
    struct delayed_work release_dw;
    void (*)(void *) disconnect;
    long unsigned int defer_start;
    long unsigned int defer_warn;
    u32 pages_state_hold_cnt;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
    atomic_t pages_state_release_cnt;
    refcount_t user_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct page_pool {
    struct page_pool_params p;
    struct delayed_work release_dw;
    void (*)(void *) disconnect;
    long unsigned int defer_start;
    long unsigned int defer_warn;
    u32 pages_state_hold_cnt;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
    atomic_t pages_state_release_cnt;
    refcount_t user_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct page_pool {
    struct page_pool_params p;
    struct delayed_work release_dw;
    void (*)(void *) disconnect;
    long unsigned int defer_start;
    long unsigned int defer_warn;
    u32 pages_state_hold_cnt;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
    atomic_t pages_state_release_cnt;
    refcount_t user_cnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct page_pool {
    struct page_pool_params p;
    struct delayed_work release_dw;
    void (*)(void *) disconnect;
    long unsigned int defer_start;
    long unsigned int defer_warn;
    u32 pages_state_hold_cnt;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
    atomic_t pages_state_release_cnt;
    refcount_t user_cnt;
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
struct page_pool {
    struct callback_head rcu;
    struct page_pool_params p;
    struct pp_alloc_cache alloc;
    struct ptr_ring ring;
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
<code>u32 pages_state_hold_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t pages_state_release_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>refcount_t user_cnt</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head rcu</code>
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
<code>struct delayed_work release_dw</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(void *) disconnect</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int defer_start</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int defer_warn</code>
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
<code>u64 destroy_cnt</code>
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
<code>unsigned int frag_offset</code>
</li>
<li>
<b>Field added. </b>
<code>struct page * frag_page</code>
</li>
<li>
<b>Field added. </b>
<code>long int frag_users</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 xdp_mem_id</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct page_pool_alloc_stats alloc_stats</code>
</li>
<li>
<b>Field added. </b>
<code>struct page_pool_recycle_stats * recycle_stats</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool has_init_callback</code>
</li>
<li>
<b>Field added. </b>
<code>struct page_pool_params_slow slow</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) user</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct page_pool_params p</code> ➡️ <code>struct page_pool_params_fast p</code>
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
