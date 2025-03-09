# Struct: <code>nfit_mem</code>

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
struct nfit_mem {
    struct nvdimm * nvdimm;
    struct acpi_nfit_memory_map * memdev_dcr;
    struct acpi_nfit_memory_map * memdev_pmem;
    struct acpi_nfit_memory_map * memdev_bdw;
    struct acpi_nfit_control_region * dcr;
    struct acpi_nfit_data_region * bdw;
    struct acpi_nfit_system_address * spa_dcr;
    struct acpi_nfit_system_address * spa_bdw;
    struct acpi_nfit_interleave * idt_dcr;
    struct acpi_nfit_interleave * idt_bdw;
    struct kernfs_node * flags_attr;
    struct nfit_flush * nfit_flush;
    struct list_head list;
    struct acpi_device * adev;
    struct acpi_nfit_desc * acpi_desc;
    char[23] id;
    struct resource * flush_wpq;
    long unsigned int dsm_mask;
    long unsigned int flags;
    u32 dirty_shutdown;
    int family;
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
struct nfit_mem {
    struct nvdimm * nvdimm;
    struct acpi_nfit_memory_map * memdev_dcr;
    struct acpi_nfit_memory_map * memdev_pmem;
    struct acpi_nfit_memory_map * memdev_bdw;
    struct acpi_nfit_control_region * dcr;
    struct acpi_nfit_data_region * bdw;
    struct acpi_nfit_system_address * spa_dcr;
    struct acpi_nfit_system_address * spa_bdw;
    struct acpi_nfit_interleave * idt_dcr;
    struct acpi_nfit_interleave * idt_bdw;
    struct kernfs_node * flags_attr;
    struct nfit_flush * nfit_flush;
    struct list_head list;
    struct acpi_device * adev;
    struct acpi_nfit_desc * acpi_desc;
    char[23] id;
    struct resource * flush_wpq;
    long unsigned int dsm_mask;
    long unsigned int flags;
    u32 dirty_shutdown;
    int family;
}
```
</details>
</li>
</ul>
