# Struct: <code>acpi_nfit_desc</code>

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
struct acpi_nfit_desc {
    struct nvdimm_bus_descriptor nd_desc;
    struct acpi_table_header acpi_header;
    struct mutex init_mutex;
    struct list_head memdevs;
    struct list_head flushes;
    struct list_head dimms;
    struct list_head spas;
    struct list_head dcrs;
    struct list_head bdws;
    struct list_head idts;
    struct nvdimm_bus * nvdimm_bus;
    struct device * dev;
    struct nd_cmd_ars_status * ars_status;
    struct nfit_spa * scrub_spa;
    struct delayed_work dwork;
    struct list_head list;
    struct kernfs_node * scrub_count_state;
    unsigned int max_ars;
    unsigned int scrub_count;
    unsigned int scrub_mode;
    long unsigned int scrub_flags;
    long unsigned int dimm_cmd_force_en;
    long unsigned int bus_cmd_force_en;
    long unsigned int bus_nfit_cmd_force_en;
    unsigned int platform_cap;
    unsigned int scrub_tmo;
    int (*)(struct nd_blk_region *, resource_size_t, void *, u64, int) blk_do_io;
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
struct acpi_nfit_desc {
    struct nvdimm_bus_descriptor nd_desc;
    struct acpi_table_header acpi_header;
    struct mutex init_mutex;
    struct list_head memdevs;
    struct list_head flushes;
    struct list_head dimms;
    struct list_head spas;
    struct list_head dcrs;
    struct list_head bdws;
    struct list_head idts;
    struct nvdimm_bus * nvdimm_bus;
    struct device * dev;
    struct nd_cmd_ars_status * ars_status;
    struct nfit_spa * scrub_spa;
    struct delayed_work dwork;
    struct list_head list;
    struct kernfs_node * scrub_count_state;
    unsigned int max_ars;
    unsigned int scrub_count;
    unsigned int scrub_mode;
    long unsigned int scrub_flags;
    long unsigned int dimm_cmd_force_en;
    long unsigned int bus_cmd_force_en;
    long unsigned int bus_nfit_cmd_force_en;
    unsigned int platform_cap;
    unsigned int scrub_tmo;
    int (*)(struct nd_blk_region *, resource_size_t, void *, u64, int) blk_do_io;
}
```
</details>
</li>
</ul>
