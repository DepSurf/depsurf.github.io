# Struct: <code>pcie_host_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pcie_host_ops {
    void (*)(struct pcie_port *, void *, u32 *) readl_rc;
    void (*)(struct pcie_port *, u32, void *) writel_rc;
    int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf;
    int (*)(struct pcie_port *, int, int, u32) wr_own_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf;
    int (*)(struct pcie_port *) link_up;
    void (*)(struct pcie_port *) host_init;
    void (*)(struct pcie_port *, int) msi_set_irq;
    void (*)(struct pcie_port *, int) msi_clear_irq;
    phys_addr_t (*)(struct pcie_port *) get_msi_addr;
    u32 (*)(struct pcie_port *, int) get_msi_data;
    void (*)(struct pcie_port *) scan_bus;
    int (*)(struct pcie_port *, struct msi_controller *) msi_host_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pcie_host_ops {
    u32 (*)(struct pcie_port *, u32) readl_rc;
    void (*)(struct pcie_port *, u32, u32) writel_rc;
    int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf;
    int (*)(struct pcie_port *, int, int, u32) wr_own_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf;
    int (*)(struct pcie_port *) link_up;
    void (*)(struct pcie_port *) host_init;
    void (*)(struct pcie_port *, int) msi_set_irq;
    void (*)(struct pcie_port *, int) msi_clear_irq;
    phys_addr_t (*)(struct pcie_port *) get_msi_addr;
    u32 (*)(struct pcie_port *, int) get_msi_data;
    void (*)(struct pcie_port *) scan_bus;
    int (*)(struct pcie_port *, struct msi_controller *) msi_host_init;
}
```
</details>
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct pcie_host_ops {
    void (*)(struct pcie_port *, void *, u32 *) readl_rc;
    void (*)(struct pcie_port *, u32, void *) writel_rc;
    int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf;
    int (*)(struct pcie_port *, int, int, u32) wr_own_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf;
    int (*)(struct pcie_port *) link_up;
    void (*)(struct pcie_port *) host_init;
    void (*)(struct pcie_port *, int) msi_set_irq;
    void (*)(struct pcie_port *, int) msi_clear_irq;
    phys_addr_t (*)(struct pcie_port *) get_msi_addr;
    u32 (*)(struct pcie_port *, int) get_msi_data;
    void (*)(struct pcie_port *) scan_bus;
    int (*)(struct pcie_port *, struct msi_controller *) msi_host_init;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void (*)(struct pcie_port *, void *, u32 *) readl_rc</code> ➡️ <code>u32 (*)(struct pcie_port *, u32) readl_rc</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct pcie_port *, u32, void *) writel_rc</code> ➡️ <code>void (*)(struct pcie_port *, u32, u32) writel_rc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct pcie_host_ops {
    u32 (*)(struct pcie_port *, u32) readl_rc;
    void (*)(struct pcie_port *, u32, u32) writel_rc;
    int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf;
    int (*)(struct pcie_port *, int, int, u32) wr_own_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf;
    int (*)(struct pcie_port *) link_up;
    void (*)(struct pcie_port *) host_init;
    void (*)(struct pcie_port *, int) msi_set_irq;
    void (*)(struct pcie_port *, int) msi_clear_irq;
    phys_addr_t (*)(struct pcie_port *) get_msi_addr;
    u32 (*)(struct pcie_port *, int) get_msi_data;
    void (*)(struct pcie_port *) scan_bus;
    int (*)(struct pcie_port *, struct msi_controller *) msi_host_init;
}
```
</details>
</li>
</ul>
