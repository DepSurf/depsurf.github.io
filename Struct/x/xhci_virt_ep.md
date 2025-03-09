# Struct: <code>xhci_virt_ep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct xhci_td * stopped_td;
    unsigned int stopped_stream;
    struct timer_list stop_cmd_timer;
    int stop_cmds_pending;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct xhci_td * stopped_td;
    unsigned int stopped_stream;
    struct timer_list stop_cmd_timer;
    int stop_cmds_pending;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct xhci_td * stopped_td;
    unsigned int stopped_stream;
    struct timer_list stop_cmd_timer;
    int stop_cmds_pending;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct timer_list stop_cmd_timer;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct timer_list stop_cmd_timer;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct timer_list stop_cmd_timer;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct timer_list stop_cmd_timer;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct timer_list stop_cmd_timer;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct timer_list stop_cmd_timer;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct timer_list stop_cmd_timer;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct timer_list stop_cmd_timer;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_virt_device * vdev;
    unsigned int ep_index;
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct timer_list stop_cmd_timer;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_virt_device * vdev;
    unsigned int ep_index;
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct timer_list stop_cmd_timer;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_virt_device * vdev;
    unsigned int ep_index;
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_virt_device * vdev;
    unsigned int ep_index;
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int err_count;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_virt_device * vdev;
    unsigned int ep_index;
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int err_count;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_virt_device * vdev;
    unsigned int ep_index;
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int err_count;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
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
struct xhci_virt_ep {
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct timer_list stop_cmd_timer;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct timer_list stop_cmd_timer;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct timer_list stop_cmd_timer;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct timer_list stop_cmd_timer;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
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
struct xhci_virt_ep {
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct timer_list stop_cmd_timer;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct timer_list stop_cmd_timer;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct timer_list stop_cmd_timer;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct xhci_virt_ep {
    struct xhci_ring * ring;
    struct xhci_stream_info * stream_info;
    struct xhci_ring * new_ring;
    unsigned int ep_state;
    struct list_head cancelled_td_list;
    struct timer_list stop_cmd_timer;
    struct xhci_hcd * xhci;
    struct xhci_segment * queued_deq_seg;
    union xhci_trb * queued_deq_ptr;
    bool skip;
    struct xhci_bw_info bw_info;
    struct list_head bw_endpoint_list;
    int next_frame_id;
    bool use_extended_tbc;
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
<b>Field removed. </b>
<code>struct xhci_td * stopped_td</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int stopped_stream</code>
</li>
<li>
<b>Field removed. </b>
<code>int stop_cmds_pending</code>
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct xhci_virt_device * vdev</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int ep_index</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct timer_list stop_cmd_timer</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int err_count</code>
</li>
</ul>
</details>
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
