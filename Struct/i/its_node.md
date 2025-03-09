# Struct: <code>its_node</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct its_node {
    raw_spinlock_t lock;
    struct mutex dev_alloc_lock;
    struct list_head entry;
    void * base;
    phys_addr_t phys_base;
    struct its_cmd_block * cmd_base;
    struct its_cmd_block * cmd_write;
    struct its_baser[8] tables;
    struct its_collection * collections;
    struct fwnode_handle * fwnode_handle;
    u64 (*)(struct its_device *) get_msi_base;
    u64 cbaser_save;
    u32 ctlr_save;
    struct list_head its_device_list;
    u64 flags;
    long unsigned int list_nr;
    u32 ite_size;
    u32 device_ids;
    int numa_node;
    unsigned int msi_domain_flags;
    u32 pre_its_base;
    bool is_v4;
    int vlpi_redist_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct its_node {
    raw_spinlock_t lock;
    struct mutex dev_alloc_lock;
    struct list_head entry;
    void * base;
    phys_addr_t phys_base;
    struct its_cmd_block * cmd_base;
    struct its_cmd_block * cmd_write;
    struct its_baser[8] tables;
    struct its_collection * collections;
    struct fwnode_handle * fwnode_handle;
    u64 (*)(struct its_device *) get_msi_base;
    u64 cbaser_save;
    u32 ctlr_save;
    struct list_head its_device_list;
    u64 flags;
    long unsigned int list_nr;
    u32 ite_size;
    u32 device_ids;
    int numa_node;
    unsigned int msi_domain_flags;
    u32 pre_its_base;
    bool is_v4;
    int vlpi_redist_offset;
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct its_node {
    raw_spinlock_t lock;
    struct mutex dev_alloc_lock;
    struct list_head entry;
    void * base;
    phys_addr_t phys_base;
    struct its_cmd_block * cmd_base;
    struct its_cmd_block * cmd_write;
    struct its_baser[8] tables;
    struct its_collection * collections;
    struct fwnode_handle * fwnode_handle;
    u64 (*)(struct its_device *) get_msi_base;
    u64 cbaser_save;
    u32 ctlr_save;
    struct list_head its_device_list;
    u64 flags;
    long unsigned int list_nr;
    u32 ite_size;
    u32 device_ids;
    int numa_node;
    unsigned int msi_domain_flags;
    u32 pre_its_base;
    bool is_v4;
    int vlpi_redist_offset;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct its_node {
    raw_spinlock_t lock;
    struct mutex dev_alloc_lock;
    struct list_head entry;
    void * base;
    phys_addr_t phys_base;
    struct its_cmd_block * cmd_base;
    struct its_cmd_block * cmd_write;
    struct its_baser[8] tables;
    struct its_collection * collections;
    struct fwnode_handle * fwnode_handle;
    u64 (*)(struct its_device *) get_msi_base;
    u64 cbaser_save;
    u32 ctlr_save;
    struct list_head its_device_list;
    u64 flags;
    long unsigned int list_nr;
    u32 ite_size;
    u32 device_ids;
    int numa_node;
    unsigned int msi_domain_flags;
    u32 pre_its_base;
    bool is_v4;
    int vlpi_redist_offset;
}
```
</details>
</li>
</ul>
