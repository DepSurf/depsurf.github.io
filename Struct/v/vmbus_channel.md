# Struct: <code>vmbus_channel</code>

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
struct vmbus_channel {
    struct list_head listentry;
    struct hv_device * device_obj;
    enum vmbus_channel_state state;
    struct vmbus_channel_offer_channel offermsg;
    u8 monitor_grp;
    u8 monitor_bit;
    bool rescind;
    struct completion rescind_event;
    u32 ringbuffer_gpadlhandle;
    struct page * ringbuffer_page;
    u32 ringbuffer_pagecount;
    u32 ringbuffer_send_offset;
    struct hv_ring_buffer_info outbound;
    struct hv_ring_buffer_info inbound;
    struct vmbus_close_msg close_msg;
    u64 interrupts;
    u64 sig_events;
    u64 intr_out_empty;
    bool out_full_flag;
    struct tasklet_struct callback_event;
    void (*)(void *) onchannel_callback;
    void * channel_callback_context;
    enum hv_callback_mode callback_mode;
    bool is_dedicated_interrupt;
    u64 sig_event;
    u32 target_vp;
    u32 target_cpu;
    struct cpumask alloced_cpus_in_node;
    int numa_node;
    void (*)(struct vmbus_channel *) sc_creation_callback;
    void (*)(struct vmbus_channel *) chn_rescind_callback;
    spinlock_t lock;
    struct list_head sc_list;
    struct vmbus_channel * primary_channel;
    void * per_channel_state;
    struct list_head percpu_list;
    struct callback_head rcu;
    struct kobject kobj;
    bool low_latency;
    enum hv_numa_policy affinity_policy;
    bool probe_done;
    struct work_struct add_channel_work;
    u64 intr_in_full;
    u64 out_full_total;
    u64 out_full_first;
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
struct vmbus_channel {
    struct list_head listentry;
    struct hv_device * device_obj;
    enum vmbus_channel_state state;
    struct vmbus_channel_offer_channel offermsg;
    u8 monitor_grp;
    u8 monitor_bit;
    bool rescind;
    struct completion rescind_event;
    u32 ringbuffer_gpadlhandle;
    struct page * ringbuffer_page;
    u32 ringbuffer_pagecount;
    u32 ringbuffer_send_offset;
    struct hv_ring_buffer_info outbound;
    struct hv_ring_buffer_info inbound;
    struct vmbus_close_msg close_msg;
    u64 interrupts;
    u64 sig_events;
    u64 intr_out_empty;
    bool out_full_flag;
    struct tasklet_struct callback_event;
    void (*)(void *) onchannel_callback;
    void * channel_callback_context;
    enum hv_callback_mode callback_mode;
    bool is_dedicated_interrupt;
    u64 sig_event;
    u32 target_vp;
    u32 target_cpu;
    struct cpumask alloced_cpus_in_node;
    int numa_node;
    void (*)(struct vmbus_channel *) sc_creation_callback;
    void (*)(struct vmbus_channel *) chn_rescind_callback;
    spinlock_t lock;
    struct list_head sc_list;
    struct vmbus_channel * primary_channel;
    void * per_channel_state;
    struct list_head percpu_list;
    struct callback_head rcu;
    struct kobject kobj;
    bool low_latency;
    enum hv_numa_policy affinity_policy;
    bool probe_done;
    struct work_struct add_channel_work;
    u64 intr_in_full;
    u64 out_full_total;
    u64 out_full_first;
}
```
</details>
</li>
</ul>
