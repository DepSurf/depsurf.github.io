# Struct: <code>acpi_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_device {
    u32 pld_crc;
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct acpi_device {
    u32 pld_crc;
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct acpi_device {
    u32 pld_crc;
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct acpi_device {
    u32 pld_crc;
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_device_software_nodes * swnodes;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
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
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
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
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
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
<code>u32 pld_crc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct acpi_device * parent</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head children</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head node</code>
</li>
<li>
<b>Field removed. </b>
<code>struct acpi_driver * driver</code>
</li>
</ul>
</details>
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
<code>struct acpi_device_software_nodes * swnodes</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct acpi_device {
    int device_type;
    acpi_handle handle;
    struct fwnode_handle fwnode;
    struct acpi_device * parent;
    struct list_head children;
    struct list_head node;
    struct list_head wakeup_list;
    struct list_head del_list;
    struct acpi_device_status status;
    struct acpi_device_flags flags;
    struct acpi_device_pnp pnp;
    struct acpi_device_power power;
    struct acpi_device_wakeup wakeup;
    struct acpi_device_perf performance;
    struct acpi_device_dir dir;
    struct acpi_device_data data;
    struct acpi_scan_handler * handler;
    struct acpi_hotplug_context * hp;
    struct acpi_driver * driver;
    const struct acpi_gpio_mapping * driver_gpios;
    void * driver_data;
    struct device dev;
    unsigned int physical_node_count;
    unsigned int dep_unmet;
    struct list_head physical_node_list;
    struct mutex physical_node_lock;
    void (*)(struct acpi_device *) remove;
}
```
</details>
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
