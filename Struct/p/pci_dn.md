# Struct: <code>pci_dn</code>

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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pci_dn {
    int flags;
    int busno;
    int devfn;
    int vendor_id;
    int device_id;
    int class_code;
    struct pci_dn * parent;
    struct pci_controller * phb;
    struct iommu_table_group * table_group;
    int pci_ext_config_space;
    struct eeh_dev * edev;
    unsigned int pe_number;
    int vf_index;
    u16 vfs_expanded;
    u16 num_vfs;
    unsigned int * pe_num_map;
    bool m64_single_mode;
    int[6] * m64_map;
    int last_allow_rc;
    int mps;
    struct list_head child_list;
    struct list_head list;
    struct resource[6] holes;
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct pci_dn {
    int flags;
    int busno;
    int devfn;
    int vendor_id;
    int device_id;
    int class_code;
    struct pci_dn * parent;
    struct pci_controller * phb;
    struct iommu_table_group * table_group;
    int pci_ext_config_space;
    struct eeh_dev * edev;
    unsigned int pe_number;
    int vf_index;
    u16 vfs_expanded;
    u16 num_vfs;
    unsigned int * pe_num_map;
    bool m64_single_mode;
    int[6] * m64_map;
    int last_allow_rc;
    int mps;
    struct list_head child_list;
    struct list_head list;
    struct resource[6] holes;
}
```
</details>
</li>
</ul>
