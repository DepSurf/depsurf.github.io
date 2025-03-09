# Struct: <code>bcma_bus</code>

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
struct bcma_bus {
    struct device * dev;
    void * mmio;
    const struct bcma_host_ops * ops;
    enum bcma_hosttype hosttype;
    bool host_is_pcie2;
    struct pci_dev * host_pci;
    struct bcma_chipinfo chipinfo;
    struct bcma_boardinfo boardinfo;
    struct bcma_device * mapped_core;
    struct list_head cores;
    u8 nr_cores;
    u8 num;
    struct bcma_drv_cc drv_cc;
    struct bcma_drv_cc_b drv_cc_b;
    struct bcma_drv_pci[2] drv_pci;
    struct bcma_drv_pcie2 drv_pcie2;
    struct bcma_drv_mips drv_mips;
    struct bcma_drv_gmac_cmn drv_gmac_cmn;
    struct ssb_sprom sprom;
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
struct bcma_bus {
    struct device * dev;
    void * mmio;
    const struct bcma_host_ops * ops;
    enum bcma_hosttype hosttype;
    bool host_is_pcie2;
    struct pci_dev * host_pci;
    struct bcma_chipinfo chipinfo;
    struct bcma_boardinfo boardinfo;
    struct bcma_device * mapped_core;
    struct list_head cores;
    u8 nr_cores;
    u8 num;
    struct bcma_drv_cc drv_cc;
    struct bcma_drv_cc_b drv_cc_b;
    struct bcma_drv_pci[2] drv_pci;
    struct bcma_drv_pcie2 drv_pcie2;
    struct bcma_drv_mips drv_mips;
    struct bcma_drv_gmac_cmn drv_gmac_cmn;
    struct ssb_sprom sprom;
}
```
</details>
</li>
</ul>
