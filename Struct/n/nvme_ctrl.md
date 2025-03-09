# Struct: <code>nvme_ctrl</code>

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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct nvme_ctrl {
    bool comp_seen;
    enum nvme_ctrl_state state;
    bool identified;
    spinlock_t lock;
    struct mutex scan_lock;
    const struct nvme_ctrl_ops * ops;
    struct request_queue * admin_q;
    struct request_queue * connect_q;
    struct request_queue * fabrics_q;
    struct device * dev;
    int instance;
    int numa_node;
    struct blk_mq_tag_set * tagset;
    struct blk_mq_tag_set * admin_tagset;
    struct list_head namespaces;
    struct rw_semaphore namespaces_rwsem;
    struct device ctrl_device;
    struct device * device;
    struct cdev cdev;
    struct work_struct reset_work;
    struct work_struct delete_work;
    wait_queue_head_t state_wq;
    struct nvme_subsystem * subsys;
    struct list_head subsys_entry;
    struct opal_dev * opal_dev;
    char[12] name;
    u16 cntlid;
    u32 ctrl_config;
    u16 mtfa;
    u32 queue_count;
    u64 cap;
    u32 page_size;
    u32 max_hw_sectors;
    u32 max_segments;
    u16[3] crdt;
    u16 oncs;
    u16 oacs;
    u16 nssa;
    u16 nr_streams;
    u16 sqsize;
    u32 max_namespaces;
    atomic_t abort_limit;
    u8 vwc;
    u32 vs;
    u32 sgls;
    u16 kas;
    u8 npss;
    u8 apsta;
    u32 oaes;
    u32 aen_result;
    u32 ctratt;
    unsigned int shutdown_timeout;
    unsigned int kato;
    bool subsystem;
    long unsigned int quirks;
    struct nvme_id_power_state[32] psd;
    struct nvme_effects_log * effects;
    struct work_struct scan_work;
    struct work_struct async_event_work;
    struct delayed_work ka_work;
    struct nvme_command ka_cmd;
    struct work_struct fw_act_work;
    long unsigned int events;
    u8 anacap;
    u8 anatt;
    u32 anagrpmax;
    u32 nanagrpid;
    struct mutex ana_lock;
    struct nvme_ana_rsp_hdr * ana_log_buf;
    size_t ana_log_size;
    struct timer_list anatt_timer;
    struct work_struct ana_work;
    u64 ps_max_latency_us;
    bool apst_enabled;
    u32 hmpre;
    u32 hmmin;
    u32 hmminds;
    u16 hmmaxd;
    u32 ioccsz;
    u32 iorcsz;
    u16 icdoff;
    u16 maxcmd;
    int nr_reconnects;
    struct nvmf_ctrl_options * opts;
    struct page * discard_page;
    long unsigned int discard_page_busy;
    struct nvme_fault_inject fault_inject;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nvme_ctrl {
    bool comp_seen;
    enum nvme_ctrl_state state;
    bool identified;
    spinlock_t lock;
    struct mutex scan_lock;
    const struct nvme_ctrl_ops * ops;
    struct request_queue * admin_q;
    struct request_queue * connect_q;
    struct request_queue * fabrics_q;
    struct device * dev;
    int instance;
    int numa_node;
    struct blk_mq_tag_set * tagset;
    struct blk_mq_tag_set * admin_tagset;
    struct list_head namespaces;
    struct rw_semaphore namespaces_rwsem;
    struct device ctrl_device;
    struct device * device;
    struct cdev cdev;
    struct work_struct reset_work;
    struct work_struct delete_work;
    wait_queue_head_t state_wq;
    struct nvme_subsystem * subsys;
    struct list_head subsys_entry;
    struct opal_dev * opal_dev;
    char[12] name;
    u16 cntlid;
    u32 ctrl_config;
    u16 mtfa;
    u32 queue_count;
    u64 cap;
    u32 page_size;
    u32 max_hw_sectors;
    u32 max_segments;
    u16[3] crdt;
    u16 oncs;
    u16 oacs;
    u16 nssa;
    u16 nr_streams;
    u16 sqsize;
    u32 max_namespaces;
    atomic_t abort_limit;
    u8 vwc;
    u32 vs;
    u32 sgls;
    u16 kas;
    u8 npss;
    u8 apsta;
    u32 oaes;
    u32 aen_result;
    u32 ctratt;
    unsigned int shutdown_timeout;
    unsigned int kato;
    bool subsystem;
    long unsigned int quirks;
    struct nvme_id_power_state[32] psd;
    struct nvme_effects_log * effects;
    struct work_struct scan_work;
    struct work_struct async_event_work;
    struct delayed_work ka_work;
    struct nvme_command ka_cmd;
    struct work_struct fw_act_work;
    long unsigned int events;
    u8 anacap;
    u8 anatt;
    u32 anagrpmax;
    u32 nanagrpid;
    struct mutex ana_lock;
    struct nvme_ana_rsp_hdr * ana_log_buf;
    size_t ana_log_size;
    struct timer_list anatt_timer;
    struct work_struct ana_work;
    u64 ps_max_latency_us;
    bool apst_enabled;
    u32 hmpre;
    u32 hmmin;
    u32 hmminds;
    u16 hmmaxd;
    u32 ioccsz;
    u32 iorcsz;
    u16 icdoff;
    u16 maxcmd;
    int nr_reconnects;
    struct nvmf_ctrl_options * opts;
    struct page * discard_page;
    long unsigned int discard_page_busy;
    struct nvme_fault_inject fault_inject;
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➕</summary>

```c
struct nvme_ctrl {
    bool comp_seen;
    enum nvme_ctrl_state state;
    bool identified;
    spinlock_t lock;
    struct mutex scan_lock;
    const struct nvme_ctrl_ops * ops;
    struct request_queue * admin_q;
    struct request_queue * connect_q;
    struct request_queue * fabrics_q;
    struct device * dev;
    int instance;
    int numa_node;
    struct blk_mq_tag_set * tagset;
    struct blk_mq_tag_set * admin_tagset;
    struct list_head namespaces;
    struct rw_semaphore namespaces_rwsem;
    struct device ctrl_device;
    struct device * device;
    struct cdev cdev;
    struct work_struct reset_work;
    struct work_struct delete_work;
    wait_queue_head_t state_wq;
    struct nvme_subsystem * subsys;
    struct list_head subsys_entry;
    struct opal_dev * opal_dev;
    char[12] name;
    u16 cntlid;
    u32 ctrl_config;
    u16 mtfa;
    u32 queue_count;
    u64 cap;
    u32 page_size;
    u32 max_hw_sectors;
    u32 max_segments;
    u16[3] crdt;
    u16 oncs;
    u16 oacs;
    u16 nssa;
    u16 nr_streams;
    u16 sqsize;
    u32 max_namespaces;
    atomic_t abort_limit;
    u8 vwc;
    u32 vs;
    u32 sgls;
    u16 kas;
    u8 npss;
    u8 apsta;
    u32 oaes;
    u32 aen_result;
    u32 ctratt;
    unsigned int shutdown_timeout;
    unsigned int kato;
    bool subsystem;
    long unsigned int quirks;
    struct nvme_id_power_state[32] psd;
    struct nvme_effects_log * effects;
    struct work_struct scan_work;
    struct work_struct async_event_work;
    struct delayed_work ka_work;
    struct nvme_command ka_cmd;
    struct work_struct fw_act_work;
    long unsigned int events;
    u8 anacap;
    u8 anatt;
    u32 anagrpmax;
    u32 nanagrpid;
    struct mutex ana_lock;
    struct nvme_ana_rsp_hdr * ana_log_buf;
    size_t ana_log_size;
    struct timer_list anatt_timer;
    struct work_struct ana_work;
    u64 ps_max_latency_us;
    bool apst_enabled;
    u32 hmpre;
    u32 hmmin;
    u32 hmminds;
    u16 hmmaxd;
    u32 ioccsz;
    u32 iorcsz;
    u16 icdoff;
    u16 maxcmd;
    int nr_reconnects;
    struct nvmf_ctrl_options * opts;
    struct page * discard_page;
    long unsigned int discard_page_busy;
    struct nvme_fault_inject fault_inject;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
struct nvme_ctrl {
    bool comp_seen;
    enum nvme_ctrl_state state;
    bool identified;
    spinlock_t lock;
    struct mutex scan_lock;
    const struct nvme_ctrl_ops * ops;
    struct request_queue * admin_q;
    struct request_queue * connect_q;
    struct request_queue * fabrics_q;
    struct device * dev;
    int instance;
    int numa_node;
    struct blk_mq_tag_set * tagset;
    struct blk_mq_tag_set * admin_tagset;
    struct list_head namespaces;
    struct rw_semaphore namespaces_rwsem;
    struct device ctrl_device;
    struct device * device;
    struct cdev cdev;
    struct work_struct reset_work;
    struct work_struct delete_work;
    wait_queue_head_t state_wq;
    struct nvme_subsystem * subsys;
    struct list_head subsys_entry;
    struct opal_dev * opal_dev;
    char[12] name;
    u16 cntlid;
    u32 ctrl_config;
    u16 mtfa;
    u32 queue_count;
    u64 cap;
    u32 page_size;
    u32 max_hw_sectors;
    u32 max_segments;
    u16[3] crdt;
    u16 oncs;
    u16 oacs;
    u16 nssa;
    u16 nr_streams;
    u16 sqsize;
    u32 max_namespaces;
    atomic_t abort_limit;
    u8 vwc;
    u32 vs;
    u32 sgls;
    u16 kas;
    u8 npss;
    u8 apsta;
    u32 oaes;
    u32 aen_result;
    u32 ctratt;
    unsigned int shutdown_timeout;
    unsigned int kato;
    bool subsystem;
    long unsigned int quirks;
    struct nvme_id_power_state[32] psd;
    struct nvme_effects_log * effects;
    struct work_struct scan_work;
    struct work_struct async_event_work;
    struct delayed_work ka_work;
    struct nvme_command ka_cmd;
    struct work_struct fw_act_work;
    long unsigned int events;
    u8 anacap;
    u8 anatt;
    u32 anagrpmax;
    u32 nanagrpid;
    struct mutex ana_lock;
    struct nvme_ana_rsp_hdr * ana_log_buf;
    size_t ana_log_size;
    struct timer_list anatt_timer;
    struct work_struct ana_work;
    u64 ps_max_latency_us;
    bool apst_enabled;
    u32 hmpre;
    u32 hmmin;
    u32 hmminds;
    u16 hmmaxd;
    u32 ioccsz;
    u32 iorcsz;
    u16 icdoff;
    u16 maxcmd;
    int nr_reconnects;
    struct nvmf_ctrl_options * opts;
    struct page * discard_page;
    long unsigned int discard_page_busy;
    struct nvme_fault_inject fault_inject;
}
```
</details>
</li>
</ul>
