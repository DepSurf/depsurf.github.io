# Struct: <code>nvmem_layout</code>

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
struct nvmem_layout {
    const char * name;
    const struct of_device_id * of_match_table;
    int (*)(struct device *, struct nvmem_device *, struct nvmem_layout *) add_cells;
    void (*)(struct nvmem_device *, struct nvmem_layout *, struct nvmem_cell_info *) fixup_cell_info;
    struct module * owner;
    struct list_head node;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nvmem_layout {
    struct device dev;
    struct nvmem_device * nvmem;
    int (*)(struct nvmem_layout *) add_cells;
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
struct nvmem_layout {
    const char * name;
    const struct of_device_id * of_match_table;
    int (*)(struct device *, struct nvmem_device *, struct nvmem_layout *) add_cells;
    void (*)(struct nvmem_device *, struct nvmem_layout *, struct nvmem_cell_info *) fixup_cell_info;
    struct module * owner;
    struct list_head node;
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
<code>struct device dev</code>
</li>
<li>
<b>Field added. </b>
<code>struct nvmem_device * nvmem</code>
</li>
<li>
<b>Field removed. </b>
<code>const char * name</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct of_device_id * of_match_table</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct nvmem_device *, struct nvmem_layout *, struct nvmem_cell_info *) fixup_cell_info</code>
</li>
<li>
<b>Field removed. </b>
<code>struct module * owner</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head node</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct device *, struct nvmem_device *, struct nvmem_layout *) add_cells</code> ➡️ <code>int (*)(struct nvmem_layout *) add_cells</code>
</li>
</ul>
</details>
</li>
</ul>
