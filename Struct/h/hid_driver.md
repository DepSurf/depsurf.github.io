# Struct: <code>hid_driver</code>

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
struct hid_driver {
    char * name;
    const struct hid_device_id * id_table;
    struct list_head dyn_list;
    spinlock_t dyn_lock;
    bool (*)(struct hid_device *, bool) match;
    int (*)(struct hid_device *, const struct hid_device_id *) probe;
    void (*)(struct hid_device *) remove;
    const struct hid_report_id * report_table;
    int (*)(struct hid_device *, struct hid_report *, u8 *, int) raw_event;
    const struct hid_usage_id * usage_table;
    int (*)(struct hid_device *, struct hid_field *, struct hid_usage *, __s32) event;
    void (*)(struct hid_device *, struct hid_report *) report;
    __u8 * (*)(struct hid_device *, __u8 *, unsigned int *) report_fixup;
    int (*)(struct hid_device *, struct hid_input *, struct hid_field *, struct hid_usage *, long unsigned int * *, int *) input_mapping;
    int (*)(struct hid_device *, struct hid_input *, struct hid_field *, struct hid_usage *, long unsigned int * *, int *) input_mapped;
    int (*)(struct hid_device *, struct hid_input *) input_configured;
    void (*)(struct hid_device *, struct hid_field *, struct hid_usage *) feature_mapping;
    int (*)(struct hid_device *, pm_message_t) suspend;
    int (*)(struct hid_device *) resume;
    int (*)(struct hid_device *) reset_resume;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct hid_driver {
    char * name;
    const struct hid_device_id * id_table;
    struct list_head dyn_list;
    spinlock_t dyn_lock;
    bool (*)(struct hid_device *, bool) match;
    int (*)(struct hid_device *, const struct hid_device_id *) probe;
    void (*)(struct hid_device *) remove;
    const struct hid_report_id * report_table;
    int (*)(struct hid_device *, struct hid_report *, u8 *, int) raw_event;
    const struct hid_usage_id * usage_table;
    int (*)(struct hid_device *, struct hid_field *, struct hid_usage *, __s32) event;
    void (*)(struct hid_device *, struct hid_report *) report;
    __u8 * (*)(struct hid_device *, __u8 *, unsigned int *) report_fixup;
    int (*)(struct hid_device *, struct hid_input *, struct hid_field *, struct hid_usage *, long unsigned int * *, int *) input_mapping;
    int (*)(struct hid_device *, struct hid_input *, struct hid_field *, struct hid_usage *, long unsigned int * *, int *) input_mapped;
    int (*)(struct hid_device *, struct hid_input *) input_configured;
    void (*)(struct hid_device *, struct hid_field *, struct hid_usage *) feature_mapping;
    int (*)(struct hid_device *, pm_message_t) suspend;
    int (*)(struct hid_device *) resume;
    int (*)(struct hid_device *) reset_resume;
    struct device_driver driver;
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
struct hid_driver {
    char * name;
    const struct hid_device_id * id_table;
    struct list_head dyn_list;
    spinlock_t dyn_lock;
    bool (*)(struct hid_device *, bool) match;
    int (*)(struct hid_device *, const struct hid_device_id *) probe;
    void (*)(struct hid_device *) remove;
    const struct hid_report_id * report_table;
    int (*)(struct hid_device *, struct hid_report *, u8 *, int) raw_event;
    const struct hid_usage_id * usage_table;
    int (*)(struct hid_device *, struct hid_field *, struct hid_usage *, __s32) event;
    void (*)(struct hid_device *, struct hid_report *) report;
    __u8 * (*)(struct hid_device *, __u8 *, unsigned int *) report_fixup;
    int (*)(struct hid_device *, struct hid_input *, struct hid_field *, struct hid_usage *, long unsigned int * *, int *) input_mapping;
    int (*)(struct hid_device *, struct hid_input *, struct hid_field *, struct hid_usage *, long unsigned int * *, int *) input_mapped;
    int (*)(struct hid_device *, struct hid_input *) input_configured;
    void (*)(struct hid_device *, struct hid_field *, struct hid_usage *) feature_mapping;
    int (*)(struct hid_device *, pm_message_t) suspend;
    int (*)(struct hid_device *) resume;
    int (*)(struct hid_device *) reset_resume;
    struct device_driver driver;
}
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
