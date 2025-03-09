# Struct: <code>hid_device</code>

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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct hid_device {
    __u8 * dev_rdesc;
    unsigned int dev_rsize;
    __u8 * rdesc;
    unsigned int rsize;
    struct hid_collection * collection;
    unsigned int collection_size;
    unsigned int maxcollection;
    unsigned int maxapplication;
    __u16 bus;
    __u16 group;
    __u32 vendor;
    __u32 product;
    __u32 version;
    enum hid_type type;
    unsigned int country;
    struct hid_report_enum[3] report_enum;
    struct work_struct led_work;
    struct semaphore driver_input_lock;
    struct device dev;
    struct hid_driver * driver;
    void * devres_group_id;
    const struct hid_ll_driver * ll_driver;
    struct mutex ll_open_lock;
    unsigned int ll_open_count;
    struct power_supply * battery;
    __s32 battery_capacity;
    __s32 battery_min;
    __s32 battery_max;
    __s32 battery_report_type;
    __s32 battery_report_id;
    __s32 battery_charge_status;
    enum hid_battery_status battery_status;
    bool battery_avoid_query;
    ktime_t battery_ratelimit_time;
    long unsigned int status;
    unsigned int claimed;
    unsigned int quirks;
    unsigned int initial_quirks;
    bool io_started;
    struct list_head inputs;
    void * hiddev;
    void * hidraw;
    char[128] name;
    char[64] phys;
    char[64] uniq;
    void * driver_data;
    int (*)(struct hid_device *) ff_init;
    int (*)(struct hid_device *, unsigned int) hiddev_connect;
    void (*)(struct hid_device *) hiddev_disconnect;
    void (*)(struct hid_device *, struct hid_field *, struct hid_usage *, __s32) hiddev_hid_event;
    void (*)(struct hid_device *, struct hid_report *) hiddev_report_event;
    short unsigned int debug;
    struct dentry * debug_dir;
    struct dentry * debug_rdesc;
    struct dentry * debug_events;
    struct list_head debug_list;
    spinlock_t debug_list_lock;
    wait_queue_head_t debug_wait;
    unsigned int id;
    struct hid_bpf bpf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct hid_device {
    __u8 * dev_rdesc;
    unsigned int dev_rsize;
    __u8 * rdesc;
    unsigned int rsize;
    struct hid_collection * collection;
    unsigned int collection_size;
    unsigned int maxcollection;
    unsigned int maxapplication;
    __u16 bus;
    __u16 group;
    __u32 vendor;
    __u32 product;
    __u32 version;
    enum hid_type type;
    unsigned int country;
    struct hid_report_enum[3] report_enum;
    struct work_struct led_work;
    struct semaphore driver_input_lock;
    struct device dev;
    struct hid_driver * driver;
    void * devres_group_id;
    const struct hid_ll_driver * ll_driver;
    struct mutex ll_open_lock;
    unsigned int ll_open_count;
    struct power_supply * battery;
    __s32 battery_capacity;
    __s32 battery_min;
    __s32 battery_max;
    __s32 battery_report_type;
    __s32 battery_report_id;
    __s32 battery_charge_status;
    enum hid_battery_status battery_status;
    bool battery_avoid_query;
    ktime_t battery_ratelimit_time;
    long unsigned int status;
    unsigned int claimed;
    unsigned int quirks;
    unsigned int initial_quirks;
    bool io_started;
    struct list_head inputs;
    void * hiddev;
    void * hidraw;
    char[128] name;
    char[64] phys;
    char[64] uniq;
    void * driver_data;
    int (*)(struct hid_device *) ff_init;
    int (*)(struct hid_device *, unsigned int) hiddev_connect;
    void (*)(struct hid_device *) hiddev_disconnect;
    void (*)(struct hid_device *, struct hid_field *, struct hid_usage *, __s32) hiddev_hid_event;
    void (*)(struct hid_device *, struct hid_report *) hiddev_report_event;
    short unsigned int debug;
    struct dentry * debug_dir;
    struct dentry * debug_rdesc;
    struct dentry * debug_events;
    struct list_head debug_list;
    spinlock_t debug_list_lock;
    wait_queue_head_t debug_wait;
    struct kref ref;
    unsigned int id;
    struct hid_bpf bpf;
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct hid_device {
    __u8 * dev_rdesc;
    unsigned int dev_rsize;
    __u8 * rdesc;
    unsigned int rsize;
    struct hid_collection * collection;
    unsigned int collection_size;
    unsigned int maxcollection;
    unsigned int maxapplication;
    __u16 bus;
    __u16 group;
    __u32 vendor;
    __u32 product;
    __u32 version;
    enum hid_type type;
    unsigned int country;
    struct hid_report_enum[3] report_enum;
    struct work_struct led_work;
    struct semaphore driver_input_lock;
    struct device dev;
    struct hid_driver * driver;
    void * devres_group_id;
    const struct hid_ll_driver * ll_driver;
    struct mutex ll_open_lock;
    unsigned int ll_open_count;
    struct power_supply * battery;
    __s32 battery_capacity;
    __s32 battery_min;
    __s32 battery_max;
    __s32 battery_report_type;
    __s32 battery_report_id;
    __s32 battery_charge_status;
    enum hid_battery_status battery_status;
    bool battery_avoid_query;
    ktime_t battery_ratelimit_time;
    long unsigned int status;
    unsigned int claimed;
    unsigned int quirks;
    unsigned int initial_quirks;
    bool io_started;
    struct list_head inputs;
    void * hiddev;
    void * hidraw;
    char[128] name;
    char[64] phys;
    char[64] uniq;
    void * driver_data;
    int (*)(struct hid_device *) ff_init;
    int (*)(struct hid_device *, unsigned int) hiddev_connect;
    void (*)(struct hid_device *) hiddev_disconnect;
    void (*)(struct hid_device *, struct hid_field *, struct hid_usage *, __s32) hiddev_hid_event;
    void (*)(struct hid_device *, struct hid_report *) hiddev_report_event;
    short unsigned int debug;
    struct dentry * debug_dir;
    struct dentry * debug_rdesc;
    struct dentry * debug_events;
    struct list_head debug_list;
    spinlock_t debug_list_lock;
    wait_queue_head_t debug_wait;
    unsigned int id;
    struct hid_bpf bpf;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct kref ref</code>
</li>
</ul>
</details>
</li>
</ul>
