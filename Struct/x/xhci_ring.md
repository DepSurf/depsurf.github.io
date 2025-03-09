# Struct: <code>xhci_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    unsigned int enq_updates;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    unsigned int deq_updates;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct radix_tree_root * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    unsigned int enq_updates;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    unsigned int deq_updates;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct radix_tree_root * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    unsigned int enq_updates;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    unsigned int deq_updates;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct radix_tree_root * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct radix_tree_root * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct radix_tree_root * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct radix_tree_root * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int err_count;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct xarray * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int err_count;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct xarray * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int err_count;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct xarray * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int err_count;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct xarray * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int err_count;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct xarray * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int err_count;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct xarray * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int err_count;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct xarray * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int err_count;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct xarray * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct xarray * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct xarray * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct xarray * trb_address_map;
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
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int err_count;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct xarray * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int err_count;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct xarray * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int err_count;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct xarray * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int err_count;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct xarray * trb_address_map;
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
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int err_count;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct xarray * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int err_count;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct xarray * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int err_count;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct xarray * trb_address_map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct xhci_ring {
    struct xhci_segment * first_seg;
    struct xhci_segment * last_seg;
    union xhci_trb * enqueue;
    struct xhci_segment * enq_seg;
    union xhci_trb * dequeue;
    struct xhci_segment * deq_seg;
    struct list_head td_list;
    u32 cycle_state;
    unsigned int err_count;
    unsigned int stream_id;
    unsigned int num_segs;
    unsigned int num_trbs_free;
    unsigned int num_trbs_free_temp;
    unsigned int bounce_buf_len;
    enum xhci_ring_type type;
    bool last_td_was_short;
    struct xarray * trb_address_map;
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
<code>unsigned int bounce_buf_len</code>
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
<b>Field removed. </b>
<code>unsigned int enq_updates</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int deq_updates</code>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int err_count</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct radix_tree_root * trb_address_map</code> ➡️ <code>struct xarray * trb_address_map</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int err_count</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int num_trbs_free_temp</code>
</li>
</ul>
</details>
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
