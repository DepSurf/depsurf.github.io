# Struct: <code>iproc_pcie</code>

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
struct iproc_pcie {
    struct device * dev;
    enum iproc_pcie_type type;
    u16 * reg_offsets;
    void * base;
    phys_addr_t base_addr;
    struct resource mem;
    struct pci_bus * root_bus;
    struct phy * phy;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    bool ep_is_internal;
    bool iproc_cfg_read;
    bool rej_unconfig_pf;
    bool has_apb_err_disable;
    bool fix_paxc_cap;
    bool need_ob_cfg;
    struct iproc_pcie_ob ob;
    const struct iproc_pcie_ob_map * ob_map;
    bool need_ib_cfg;
    struct iproc_pcie_ib ib;
    const struct iproc_pcie_ib_map * ib_map;
    bool need_msi_steer;
    struct iproc_msi * msi;
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
struct iproc_pcie {
    struct device * dev;
    enum iproc_pcie_type type;
    u16 * reg_offsets;
    void * base;
    phys_addr_t base_addr;
    struct resource mem;
    struct pci_bus * root_bus;
    struct phy * phy;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    bool ep_is_internal;
    bool iproc_cfg_read;
    bool rej_unconfig_pf;
    bool has_apb_err_disable;
    bool fix_paxc_cap;
    bool need_ob_cfg;
    struct iproc_pcie_ob ob;
    const struct iproc_pcie_ob_map * ob_map;
    bool need_ib_cfg;
    struct iproc_pcie_ib ib;
    const struct iproc_pcie_ib_map * ib_map;
    bool need_msi_steer;
    struct iproc_msi * msi;
}
```
</details>
</li>
</ul>
