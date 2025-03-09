# Struct: <code>pci_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *, pm_message_t) suspend_late;
    int (*)(struct pci_dev *) resume_early;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    const struct pci_error_handlers * err_handler;
    struct device_driver driver;
    struct pci_dynids dynids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *, pm_message_t) suspend_late;
    int (*)(struct pci_dev *) resume_early;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    const struct pci_error_handlers * err_handler;
    struct device_driver driver;
    struct pci_dynids dynids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *, pm_message_t) suspend_late;
    int (*)(struct pci_dev *) resume_early;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    const struct pci_error_handlers * err_handler;
    struct device_driver driver;
    struct pci_dynids dynids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *, pm_message_t) suspend_late;
    int (*)(struct pci_dev *) resume_early;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    const struct pci_error_handlers * err_handler;
    struct device_driver driver;
    struct pci_dynids dynids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *, pm_message_t) suspend_late;
    int (*)(struct pci_dev *) resume_early;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    struct device_driver driver;
    struct pci_dynids dynids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *, pm_message_t) suspend_late;
    int (*)(struct pci_dev *) resume_early;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    struct device_driver driver;
    struct pci_dynids dynids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *, pm_message_t) suspend_late;
    int (*)(struct pci_dev *) resume_early;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    struct device_driver driver;
    struct pci_dynids dynids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *, pm_message_t) suspend_late;
    int (*)(struct pci_dev *) resume_early;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    struct device_driver driver;
    struct pci_dynids dynids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *, pm_message_t) suspend_late;
    int (*)(struct pci_dev *) resume_early;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    struct device_driver driver;
    struct pci_dynids dynids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    struct device_driver driver;
    struct pci_dynids dynids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    struct device_driver driver;
    struct pci_dynids dynids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    int (*)(struct pci_dev *, int) sriov_set_msix_vec_count;
    u32 (*)(struct pci_dev *) sriov_get_vf_total_msix;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    struct device_driver driver;
    struct pci_dynids dynids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    int (*)(struct pci_dev *, int) sriov_set_msix_vec_count;
    u32 (*)(struct pci_dev *) sriov_get_vf_total_msix;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    struct device_driver driver;
    struct pci_dynids dynids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    int (*)(struct pci_dev *, int) sriov_set_msix_vec_count;
    u32 (*)(struct pci_dev *) sriov_get_vf_total_msix;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    struct device_driver driver;
    struct pci_dynids dynids;
    bool driver_managed_dma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    int (*)(struct pci_dev *, int) sriov_set_msix_vec_count;
    u32 (*)(struct pci_dev *) sriov_get_vf_total_msix;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    struct device_driver driver;
    struct pci_dynids dynids;
    bool driver_managed_dma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    int (*)(struct pci_dev *, int) sriov_set_msix_vec_count;
    u32 (*)(struct pci_dev *) sriov_get_vf_total_msix;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    struct device_driver driver;
    struct pci_dynids dynids;
    bool driver_managed_dma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pci_driver {
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    int (*)(struct pci_dev *, int) sriov_set_msix_vec_count;
    u32 (*)(struct pci_dev *) sriov_get_vf_total_msix;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    struct device_driver driver;
    struct pci_dynids dynids;
    bool driver_managed_dma;
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
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *, pm_message_t) suspend_late;
    int (*)(struct pci_dev *) resume_early;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    struct device_driver driver;
    struct pci_dynids dynids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *, pm_message_t) suspend_late;
    int (*)(struct pci_dev *) resume_early;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    struct device_driver driver;
    struct pci_dynids dynids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *, pm_message_t) suspend_late;
    int (*)(struct pci_dev *) resume_early;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    struct device_driver driver;
    struct pci_dynids dynids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *, pm_message_t) suspend_late;
    int (*)(struct pci_dev *) resume_early;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    struct device_driver driver;
    struct pci_dynids dynids;
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
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *, pm_message_t) suspend_late;
    int (*)(struct pci_dev *) resume_early;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    struct device_driver driver;
    struct pci_dynids dynids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *, pm_message_t) suspend_late;
    int (*)(struct pci_dev *) resume_early;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    struct device_driver driver;
    struct pci_dynids dynids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *, pm_message_t) suspend_late;
    int (*)(struct pci_dev *) resume_early;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    struct device_driver driver;
    struct pci_dynids dynids;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pci_driver {
    struct list_head node;
    const char * name;
    const struct pci_device_id * id_table;
    int (*)(struct pci_dev *, const struct pci_device_id *) probe;
    void (*)(struct pci_dev *) remove;
    int (*)(struct pci_dev *, pm_message_t) suspend;
    int (*)(struct pci_dev *, pm_message_t) suspend_late;
    int (*)(struct pci_dev *) resume_early;
    int (*)(struct pci_dev *) resume;
    void (*)(struct pci_dev *) shutdown;
    int (*)(struct pci_dev *, int) sriov_configure;
    const struct pci_error_handlers * err_handler;
    const struct attribute_group * * groups;
    struct device_driver driver;
    struct pci_dynids dynids;
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct attribute_group * * groups</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct pci_dev *, pm_message_t) suspend_late</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct pci_dev *) resume_early</code>
</li>
</ul>
</details>
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
<code>int (*)(struct pci_dev *, int) sriov_set_msix_vec_count</code>
</li>
<li>
<b>Field added. </b>
<code>u32 (*)(struct pci_dev *) sriov_get_vf_total_msix</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct attribute_group * * dev_groups</code>
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
<code>bool driver_managed_dma</code>
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
<b>Field removed. </b>
<code>struct list_head node</code>
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
