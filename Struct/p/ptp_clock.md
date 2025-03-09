# Struct: <code>ptp_clock</code>

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
struct ptp_clock {
    struct posix_clock clock;
    struct device * dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct timestamp_event_queue tsevq;
    struct mutex tsevq_mux;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock {
    struct posix_clock clock;
    struct device * dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct timestamp_event_queue tsevq;
    struct mutex tsevq_mux;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock {
    struct posix_clock clock;
    struct device * dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct timestamp_event_queue tsevq;
    struct mutex tsevq_mux;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock {
    struct posix_clock clock;
    struct device dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct timestamp_event_queue tsevq;
    struct mutex tsevq_mux;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock {
    struct posix_clock clock;
    struct device dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct timestamp_event_queue tsevq;
    struct mutex tsevq_mux;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock {
    struct posix_clock clock;
    struct device dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct timestamp_event_queue tsevq;
    struct mutex tsevq_mux;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock {
    struct posix_clock clock;
    struct device dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct timestamp_event_queue tsevq;
    struct mutex tsevq_mux;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock {
    struct posix_clock clock;
    struct device dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct timestamp_event_queue tsevq;
    struct mutex tsevq_mux;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
    unsigned int max_vclocks;
    unsigned int n_vclocks;
    int * vclock_index;
    struct mutex n_vclocks_mux;
    bool is_virtual_clock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock {
    struct posix_clock clock;
    struct device dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct timestamp_event_queue tsevq;
    struct mutex tsevq_mux;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
    unsigned int max_vclocks;
    unsigned int n_vclocks;
    int * vclock_index;
    struct mutex n_vclocks_mux;
    bool is_virtual_clock;
    bool has_cycles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock {
    struct posix_clock clock;
    struct device dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct timestamp_event_queue tsevq;
    struct mutex tsevq_mux;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
    unsigned int max_vclocks;
    unsigned int n_vclocks;
    int * vclock_index;
    struct mutex n_vclocks_mux;
    bool is_virtual_clock;
    bool has_cycles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock {
    struct posix_clock clock;
    struct device dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct timestamp_event_queue tsevq;
    struct mutex tsevq_mux;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
    unsigned int max_vclocks;
    unsigned int n_vclocks;
    int * vclock_index;
    struct mutex n_vclocks_mux;
    bool is_virtual_clock;
    bool has_cycles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ptp_clock {
    struct posix_clock clock;
    struct device dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct list_head tsevqs;
    spinlock_t tsevqs_lock;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
    unsigned int max_vclocks;
    unsigned int n_vclocks;
    int * vclock_index;
    struct mutex n_vclocks_mux;
    bool is_virtual_clock;
    bool has_cycles;
    struct dentry * debugfs_root;
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
struct ptp_clock {
    struct posix_clock clock;
    struct device dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct timestamp_event_queue tsevq;
    struct mutex tsevq_mux;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ptp_clock {
    struct posix_clock clock;
    struct device dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct timestamp_event_queue tsevq;
    struct mutex tsevq_mux;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ptp_clock {
    struct posix_clock clock;
    struct device dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct timestamp_event_queue tsevq;
    struct mutex tsevq_mux;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ptp_clock {
    struct posix_clock clock;
    struct device dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct timestamp_event_queue tsevq;
    struct mutex tsevq_mux;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
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
struct ptp_clock {
    struct posix_clock clock;
    struct device dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct timestamp_event_queue tsevq;
    struct mutex tsevq_mux;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ptp_clock {
    struct posix_clock clock;
    struct device dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct timestamp_event_queue tsevq;
    struct mutex tsevq_mux;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ptp_clock {
    struct posix_clock clock;
    struct device dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct timestamp_event_queue tsevq;
    struct mutex tsevq_mux;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ptp_clock {
    struct posix_clock clock;
    struct device dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct timestamp_event_queue tsevq;
    struct mutex tsevq_mux;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
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
struct ptp_clock {
    struct posix_clock clock;
    struct device * dev;
    struct ptp_clock_info * info;
    dev_t devid;
    int index;
    struct pps_device * pps_source;
    long int dialed_frequency;
    struct timestamp_event_queue tsevq;
    struct mutex tsevq_mux;
    struct mutex pincfg_mux;
    wait_queue_head_t tsev_wq;
    int defunct;
    struct device_attribute * pin_dev_attr;
    struct attribute * * pin_attr;
    struct attribute_group pin_attr_group;
    const struct attribute_group *[2] pin_attr_groups;
    struct kthread_worker * kworker;
    struct kthread_delayed_work aux_work;
}
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct device * dev</code> ➡️ <code>struct device dev</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int max_vclocks</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int n_vclocks</code>
</li>
<li>
<b>Field added. </b>
<code>int * vclock_index</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex n_vclocks_mux</code>
</li>
<li>
<b>Field added. </b>
<code>bool is_virtual_clock</code>
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
<code>bool has_cycles</code>
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
<code>struct list_head tsevqs</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t tsevqs_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct dentry * debugfs_root</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timestamp_event_queue tsevq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex tsevq_mux</code>
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
