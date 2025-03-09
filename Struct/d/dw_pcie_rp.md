# Struct: <code>dw_pcie_rp</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_rp {
    bool has_msi_ctrl;
    bool cfg0_io_shared;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int[8] msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    dma_addr_t msi_data;
    struct irq_chip * msi_irq_chip;
    u32 num_vectors;
    u32[8] irq_mask;
    struct pci_host_bridge * bridge;
    raw_spinlock_t lock;
    long unsigned int[4] msi_irq_in_use;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_rp {
    bool has_msi_ctrl;
    bool cfg0_io_shared;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int[8] msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    dma_addr_t msi_data;
    struct irq_chip * msi_irq_chip;
    u32 num_vectors;
    u32[8] irq_mask;
    struct pci_host_bridge * bridge;
    raw_spinlock_t lock;
    long unsigned int[4] msi_irq_in_use;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_rp {
    bool has_msi_ctrl;
    bool cfg0_io_shared;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int[8] msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    dma_addr_t msi_data;
    struct irq_chip * msi_irq_chip;
    u32 num_vectors;
    u32[8] irq_mask;
    struct pci_host_bridge * bridge;
    raw_spinlock_t lock;
    long unsigned int[4] msi_irq_in_use;
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct dw_pcie_rp {
    bool has_msi_ctrl;
    bool cfg0_io_shared;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int[8] msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    dma_addr_t msi_data;
    struct irq_chip * msi_irq_chip;
    u32 num_vectors;
    u32[8] irq_mask;
    struct pci_host_bridge * bridge;
    raw_spinlock_t lock;
    long unsigned int[4] msi_irq_in_use;
}
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
