# Struct: <code>device_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct dev_pm_ops * pm;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct dev_pm_ops * pm;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct dev_pm_ops * pm;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct dev_pm_ops * pm;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct dev_pm_ops * pm;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct dev_pm_ops * pm;
    void (*)(struct device *) coredump;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct dev_pm_ops * pm;
    void (*)(struct device *) coredump;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct dev_pm_ops * pm;
    void (*)(struct device *) coredump;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    const struct dev_pm_ops * pm;
    void (*)(struct device *) coredump;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    void (*)(struct device *) sync_state;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    const struct dev_pm_ops * pm;
    void (*)(struct device *) coredump;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    void (*)(struct device *) sync_state;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    const struct dev_pm_ops * pm;
    void (*)(struct device *) coredump;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    void (*)(struct device *) sync_state;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    const struct dev_pm_ops * pm;
    void (*)(struct device *) coredump;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    void (*)(struct device *) sync_state;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    const struct dev_pm_ops * pm;
    void (*)(struct device *) coredump;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    void (*)(struct device *) sync_state;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    const struct dev_pm_ops * pm;
    void (*)(struct device *) coredump;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    void (*)(struct device *) sync_state;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    const struct dev_pm_ops * pm;
    void (*)(struct device *) coredump;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    const struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    void (*)(struct device *) sync_state;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    const struct dev_pm_ops * pm;
    void (*)(struct device *) coredump;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    const struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    void (*)(struct device *) sync_state;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    const struct dev_pm_ops * pm;
    void (*)(struct device *) coredump;
    struct driver_private * p;
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
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    const struct dev_pm_ops * pm;
    void (*)(struct device *) coredump;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    const struct dev_pm_ops * pm;
    void (*)(struct device *) coredump;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    const struct dev_pm_ops * pm;
    void (*)(struct device *) coredump;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    const struct dev_pm_ops * pm;
    void (*)(struct device *) coredump;
    struct driver_private * p;
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
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    const struct dev_pm_ops * pm;
    void (*)(struct device *) coredump;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    const struct dev_pm_ops * pm;
    void (*)(struct device *) coredump;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    const struct dev_pm_ops * pm;
    void (*)(struct device *) coredump;
    struct driver_private * p;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct device_driver {
    const char * name;
    struct bus_type * bus;
    struct module * owner;
    const char * mod_name;
    bool suppress_bind_attrs;
    enum probe_type probe_type;
    const struct of_device_id * of_match_table;
    const struct acpi_device_id * acpi_match_table;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct attribute_group * * groups;
    const struct attribute_group * * dev_groups;
    const struct dev_pm_ops * pm;
    void (*)(struct device *) coredump;
    struct driver_private * p;
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct device *) coredump</code>
</li>
</ul>
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
<b>Field added. </b>
<code>const struct attribute_group * * dev_groups</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct device *) sync_state</code>
</li>
</ul>
</details>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct bus_type * bus</code> ➡️ <code>const struct bus_type * bus</code>
</li>
</ul>
</details>
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
