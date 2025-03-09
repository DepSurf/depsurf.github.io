# Struct: <code>vmbus_connection</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct vmbus_connection {
    int connect_cpu;
    u32 msg_conn_id;
    atomic_t offer_in_progress;
    enum vmbus_connect_state conn_state;
    atomic_t next_gpadl_handle;
    struct completion unload_event;
    void * int_page;
    void * send_int_page;
    void * recv_int_page;
    struct hv_monitor_page *[2] monitor_pages;
    struct list_head chn_msg_list;
    spinlock_t channelmsg_lock;
    struct list_head chn_list;
    struct mutex channel_mutex;
    struct workqueue_struct * work_queue;
    struct workqueue_struct * handle_primary_chan_wq;
    struct workqueue_struct * handle_sub_chan_wq;
    atomic_t nr_chan_close_on_suspend;
    struct completion ready_for_suspend_event;
    atomic_t nr_chan_fixup_on_resume;
    struct completion ready_for_resume_event;
}
```
</details>
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
struct vmbus_connection {
    int connect_cpu;
    u32 msg_conn_id;
    atomic_t offer_in_progress;
    enum vmbus_connect_state conn_state;
    atomic_t next_gpadl_handle;
    struct completion unload_event;
    void * int_page;
    void * send_int_page;
    void * recv_int_page;
    struct hv_monitor_page *[2] monitor_pages;
    struct list_head chn_msg_list;
    spinlock_t channelmsg_lock;
    struct list_head chn_list;
    struct mutex channel_mutex;
    struct workqueue_struct * work_queue;
    struct workqueue_struct * handle_primary_chan_wq;
    struct workqueue_struct * handle_sub_chan_wq;
    atomic_t nr_chan_close_on_suspend;
    struct completion ready_for_suspend_event;
    atomic_t nr_chan_fixup_on_resume;
    struct completion ready_for_resume_event;
}
```
</details>
</li>
</ul>
