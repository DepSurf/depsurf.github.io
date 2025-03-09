# Struct: <code>mfd_cell</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    atomic_t * usage_count;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    const struct property_set * pset;
    const char * of_compatible;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    atomic_t * usage_count;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    struct property_entry * properties;
    const char * of_compatible;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    atomic_t * usage_count;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    struct property_entry * properties;
    const char * of_compatible;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    atomic_t * usage_count;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    struct property_entry * properties;
    const char * of_compatible;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    atomic_t * usage_count;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    struct property_entry * properties;
    const char * of_compatible;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    atomic_t * usage_count;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    struct property_entry * properties;
    const char * of_compatible;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    atomic_t * usage_count;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    struct property_entry * properties;
    const char * of_compatible;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    atomic_t * usage_count;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    struct property_entry * properties;
    const char * of_compatible;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    atomic_t * usage_count;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    struct property_entry * properties;
    const char * of_compatible;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    const struct property_entry * properties;
    const char * of_compatible;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    int level;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    const struct property_entry * properties;
    const char * of_compatible;
    const u64 of_reg;
    bool use_of_reg;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    int level;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    const struct software_node * swnode;
    const char * of_compatible;
    const u64 of_reg;
    bool use_of_reg;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    int level;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    const struct software_node * swnode;
    const char * of_compatible;
    const u64 of_reg;
    bool use_of_reg;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    int level;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    const struct software_node * swnode;
    const char * of_compatible;
    const u64 of_reg;
    bool use_of_reg;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    int level;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    const struct software_node * swnode;
    const char * of_compatible;
    const u64 of_reg;
    bool use_of_reg;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    int level;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    const struct mfd_cell_acpi_match * acpi_match;
    const struct software_node * swnode;
    const char * of_compatible;
    const u64 of_reg;
    bool use_of_reg;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    int num_parent_supplies;
    const const char * * parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    int level;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    const struct mfd_cell_acpi_match * acpi_match;
    const struct software_node * swnode;
    const char * of_compatible;
    u64 of_reg;
    bool use_of_reg;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    int num_parent_supplies;
    const const char * * parent_supplies;
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
struct mfd_cell {
    const char * name;
    int id;
    atomic_t * usage_count;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    struct property_entry * properties;
    const char * of_compatible;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    atomic_t * usage_count;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    struct property_entry * properties;
    const char * of_compatible;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    atomic_t * usage_count;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    struct property_entry * properties;
    const char * of_compatible;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    atomic_t * usage_count;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    struct property_entry * properties;
    const char * of_compatible;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
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
struct mfd_cell {
    const char * name;
    int id;
    atomic_t * usage_count;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    struct property_entry * properties;
    const char * of_compatible;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    atomic_t * usage_count;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    struct property_entry * properties;
    const char * of_compatible;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    atomic_t * usage_count;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    struct property_entry * properties;
    const char * of_compatible;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mfd_cell {
    const char * name;
    int id;
    atomic_t * usage_count;
    int (*)(struct platform_device *) enable;
    int (*)(struct platform_device *) disable;
    int (*)(struct platform_device *) suspend;
    int (*)(struct platform_device *) resume;
    void * platform_data;
    size_t pdata_size;
    struct property_entry * properties;
    const char * of_compatible;
    const struct mfd_cell_acpi_match * acpi_match;
    int num_resources;
    const struct resource * resources;
    bool ignore_resource_conflicts;
    bool pm_runtime_no_callbacks;
    const const char * * parent_supplies;
    int num_parent_supplies;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct property_entry * properties</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct property_set * pset</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>atomic_t * usage_count</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct property_entry * properties</code> ➡️ <code>const struct property_entry * properties</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int level</code>
</li>
<li>
<b>Field added. </b>
<code>const u64 of_reg</code>
</li>
<li>
<b>Field added. </b>
<code>bool use_of_reg</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct software_node * swnode</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct property_entry * properties</code>
</li>
</ul>
</details>
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
<b>Field removed. </b>
<code>int (*)(struct platform_device *) enable</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct platform_device *) disable</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>const u64 of_reg</code> ➡️ <code>u64 of_reg</code>
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
