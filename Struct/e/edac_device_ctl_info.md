# Struct: <code>edac_device_ctl_info</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_counter counters;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_counter counters;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_counter counters;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_counter counters;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_counter counters;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_counter counters;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_counter counters;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_counter counters;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_counter counters;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_counter counters;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_block * blocks;
    struct edac_dev_sysfs_block_attribute * attribs;
    struct edac_device_counter counters;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_block * blocks;
    struct edac_dev_sysfs_block_attribute * attribs;
    struct edac_device_counter counters;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_block * blocks;
    struct edac_dev_sysfs_block_attribute * attribs;
    struct edac_device_counter counters;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    const struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_block * blocks;
    struct edac_dev_sysfs_block_attribute * attribs;
    struct edac_device_counter counters;
    struct kobject kobj;
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
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_counter counters;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_counter counters;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_counter counters;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_counter counters;
    struct kobject kobj;
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
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_counter counters;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_counter counters;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_counter counters;
    struct kobject kobj;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_counter counters;
    struct kobject kobj;
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct edac_device_ctl_info {
    struct list_head link;
    struct module * owner;
    int dev_idx;
    int log_ue;
    int log_ce;
    int panic_on_ue;
    unsigned int poll_msec;
    long unsigned int delay;
    struct edac_dev_sysfs_attribute * sysfs_attributes;
    struct bus_type * edac_subsys;
    int op_state;
    struct delayed_work work;
    void (*)(struct edac_device_ctl_info *) edac_check;
    struct device * dev;
    const char * mod_name;
    const char * ctl_name;
    const char * dev_name;
    void * pvt_info;
    long unsigned int start_time;
    struct completion removal_complete;
    char[32] name;
    u32 nr_instances;
    struct edac_device_instance * instances;
    struct edac_device_counter counters;
    struct kobject kobj;
}
```
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
<code>struct edac_device_block * blocks</code>
</li>
<li>
<b>Field added. </b>
<code>struct edac_dev_sysfs_block_attribute * attribs</code>
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
<b>Field type changed. </b>
<code>struct bus_type * edac_subsys</code> ➡️ <code>const struct bus_type * edac_subsys</code>
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
