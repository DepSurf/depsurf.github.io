# Struct: <code>pcie_port</code>

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
struct pcie_port {
    struct device * dev;
    u8 root_bus_nr;
    void * dbi_base;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    u64 cfg1_base;
    void * va_cfg1_base;
    u32 cfg1_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    u64 mem_base;
    phys_addr_t mem_bus_addr;
    u32 mem_size;
    struct resource * cfg;
    struct resource * io;
    struct resource * mem;
    struct resource * busn;
    int irq;
    u32 lanes;
    struct pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    long unsigned int msi_data;
    long unsigned int[1] msi_irq_in_use;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pcie_port {
    struct device * dev;
    u8 root_bus_nr;
    void * dbi_base;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    u64 cfg1_base;
    void * va_cfg1_base;
    u32 cfg1_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    u64 mem_base;
    phys_addr_t mem_bus_addr;
    u32 mem_size;
    struct resource * cfg;
    struct resource * io;
    struct resource * mem;
    struct resource * busn;
    int irq;
    u32 lanes;
    u32 num_viewport;
    struct pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    long unsigned int msi_data;
    u8 iatu_unroll_enabled;
    long unsigned int[1] msi_irq_in_use;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pcie_port {
    u8 root_bus_nr;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    u64 cfg1_base;
    void * va_cfg1_base;
    u32 cfg1_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    u64 mem_base;
    phys_addr_t mem_bus_addr;
    u32 mem_size;
    struct resource * cfg;
    struct resource * io;
    struct resource * mem;
    struct resource * busn;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    long unsigned int msi_data;
    long unsigned int[1] msi_irq_in_use;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pcie_port {
    u8 root_bus_nr;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    u64 cfg1_base;
    void * va_cfg1_base;
    u32 cfg1_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    u64 mem_base;
    phys_addr_t mem_bus_addr;
    u32 mem_size;
    struct resource * cfg;
    struct resource * io;
    struct resource * mem;
    struct resource * busn;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    long unsigned int msi_data;
    long unsigned int[1] msi_irq_in_use;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pcie_port {
    u8 root_bus_nr;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    u64 cfg1_base;
    void * va_cfg1_base;
    u32 cfg1_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    u64 mem_base;
    phys_addr_t mem_bus_addr;
    u32 mem_size;
    struct resource * cfg;
    struct resource * io;
    struct resource * mem;
    struct resource * busn;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    dma_addr_t msi_data;
    u32 num_vectors;
    u32[8] irq_status;
    raw_spinlock_t lock;
    long unsigned int[4] msi_irq_in_use;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pcie_port {
    u8 root_bus_nr;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    u64 cfg1_base;
    void * va_cfg1_base;
    u32 cfg1_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    u64 mem_base;
    phys_addr_t mem_bus_addr;
    u32 mem_size;
    struct resource * cfg;
    struct resource * io;
    struct resource * mem;
    struct resource * busn;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    dma_addr_t msi_data;
    u32 num_vectors;
    u32[8] irq_status;
    raw_spinlock_t lock;
    long unsigned int[4] msi_irq_in_use;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pcie_port {
    u8 root_bus_nr;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    u64 cfg1_base;
    void * va_cfg1_base;
    u32 cfg1_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    u64 mem_base;
    phys_addr_t mem_bus_addr;
    u32 mem_size;
    struct resource * cfg;
    struct resource * io;
    struct resource * mem;
    struct resource * busn;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    dma_addr_t msi_data;
    struct page * msi_page;
    struct irq_chip * msi_irq_chip;
    u32 num_vectors;
    u32[8] irq_mask;
    struct pci_bus * root_bus;
    raw_spinlock_t lock;
    long unsigned int[4] msi_irq_in_use;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pcie_port {
    u8 root_bus_nr;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    u64 cfg1_base;
    void * va_cfg1_base;
    u32 cfg1_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    u64 mem_base;
    phys_addr_t mem_bus_addr;
    u32 mem_size;
    struct resource * cfg;
    struct resource * io;
    struct resource * mem;
    struct resource * busn;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    dma_addr_t msi_data;
    struct page * msi_page;
    struct irq_chip * msi_irq_chip;
    u32 num_vectors;
    u32[8] irq_mask;
    struct pci_bus * root_bus;
    raw_spinlock_t lock;
    long unsigned int[4] msi_irq_in_use;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pcie_port {
    u8 root_bus_nr;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    u64 cfg1_base;
    void * va_cfg1_base;
    u32 cfg1_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    u64 mem_base;
    phys_addr_t mem_bus_addr;
    u32 mem_size;
    struct resource * cfg;
    struct resource * io;
    struct resource * mem;
    struct resource * busn;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    dma_addr_t msi_data;
    struct page * msi_page;
    struct irq_chip * msi_irq_chip;
    u32 num_vectors;
    u32[8] irq_mask;
    struct pci_bus * root_bus;
    raw_spinlock_t lock;
    long unsigned int[4] msi_irq_in_use;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pcie_port {
    bool has_msi_ctrl;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    u16 msi_msg;
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pcie_port {
    bool has_msi_ctrl;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    u16 msi_msg;
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pcie_port {
    bool has_msi_ctrl;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    u16 msi_msg;
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pcie_port {
    bool has_msi_ctrl;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    u16 msi_msg;
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
struct pcie_port {
    u8 root_bus_nr;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    u64 cfg1_base;
    void * va_cfg1_base;
    u32 cfg1_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    u64 mem_base;
    phys_addr_t mem_bus_addr;
    u32 mem_size;
    struct resource * cfg;
    struct resource * io;
    struct resource * mem;
    struct resource * busn;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    dma_addr_t msi_data;
    struct page * msi_page;
    struct irq_chip * msi_irq_chip;
    u32 num_vectors;
    u32[8] irq_mask;
    struct pci_bus * root_bus;
    raw_spinlock_t lock;
    long unsigned int[4] msi_irq_in_use;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pcie_port {
    u8 root_bus_nr;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    u64 cfg1_base;
    void * va_cfg1_base;
    u32 cfg1_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    u64 mem_base;
    phys_addr_t mem_bus_addr;
    u32 mem_size;
    struct resource * cfg;
    struct resource * io;
    struct resource * mem;
    struct resource * busn;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    dma_addr_t msi_data;
    struct page * msi_page;
    struct irq_chip * msi_irq_chip;
    u32 num_vectors;
    u32[8] irq_mask;
    struct pci_bus * root_bus;
    raw_spinlock_t lock;
    long unsigned int[8] msi_irq_in_use;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pcie_port {
    u8 root_bus_nr;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    u64 cfg1_base;
    void * va_cfg1_base;
    u32 cfg1_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    u64 mem_base;
    phys_addr_t mem_bus_addr;
    u32 mem_size;
    struct resource * cfg;
    struct resource * io;
    struct resource * mem;
    struct resource * busn;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    dma_addr_t msi_data;
    struct page * msi_page;
    struct irq_chip * msi_irq_chip;
    u32 num_vectors;
    u32[8] irq_mask;
    struct pci_bus * root_bus;
    raw_spinlock_t lock;
    long unsigned int[4] msi_irq_in_use;
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
struct pcie_port {
    u8 root_bus_nr;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    u64 cfg1_base;
    void * va_cfg1_base;
    u32 cfg1_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    u64 mem_base;
    phys_addr_t mem_bus_addr;
    u32 mem_size;
    struct resource * cfg;
    struct resource * io;
    struct resource * mem;
    struct resource * busn;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    dma_addr_t msi_data;
    struct page * msi_page;
    struct irq_chip * msi_irq_chip;
    u32 num_vectors;
    u32[8] irq_mask;
    struct pci_bus * root_bus;
    raw_spinlock_t lock;
    long unsigned int[4] msi_irq_in_use;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pcie_port {
    u8 root_bus_nr;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    u64 cfg1_base;
    void * va_cfg1_base;
    u32 cfg1_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    u64 mem_base;
    phys_addr_t mem_bus_addr;
    u32 mem_size;
    struct resource * cfg;
    struct resource * io;
    struct resource * mem;
    struct resource * busn;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    dma_addr_t msi_data;
    struct page * msi_page;
    struct irq_chip * msi_irq_chip;
    u32 num_vectors;
    u32[8] irq_mask;
    struct pci_bus * root_bus;
    raw_spinlock_t lock;
    long unsigned int[4] msi_irq_in_use;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pcie_port {
    u8 root_bus_nr;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    u64 cfg1_base;
    void * va_cfg1_base;
    u32 cfg1_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    u64 mem_base;
    phys_addr_t mem_bus_addr;
    u32 mem_size;
    struct resource * cfg;
    struct resource * io;
    struct resource * mem;
    struct resource * busn;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    dma_addr_t msi_data;
    struct page * msi_page;
    struct irq_chip * msi_irq_chip;
    u32 num_vectors;
    u32[8] irq_mask;
    struct pci_bus * root_bus;
    raw_spinlock_t lock;
    long unsigned int[4] msi_irq_in_use;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pcie_port {
    u8 root_bus_nr;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    u64 cfg1_base;
    void * va_cfg1_base;
    u32 cfg1_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    u64 mem_base;
    phys_addr_t mem_bus_addr;
    u32 mem_size;
    struct resource * cfg;
    struct resource * io;
    struct resource * mem;
    struct resource * busn;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    dma_addr_t msi_data;
    struct page * msi_page;
    struct irq_chip * msi_irq_chip;
    u32 num_vectors;
    u32[8] irq_mask;
    struct pci_bus * root_bus;
    raw_spinlock_t lock;
    long unsigned int[4] msi_irq_in_use;
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct pcie_port {
    struct device * dev;
    u8 root_bus_nr;
    void * dbi_base;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    u64 cfg1_base;
    void * va_cfg1_base;
    u32 cfg1_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    u64 mem_base;
    phys_addr_t mem_bus_addr;
    u32 mem_size;
    struct resource * cfg;
    struct resource * io;
    struct resource * mem;
    struct resource * busn;
    int irq;
    u32 lanes;
    struct pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    long unsigned int msi_data;
    long unsigned int[1] msi_irq_in_use;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 num_viewport</code>
</li>
<li>
<b>Field added. </b>
<code>u8 iatu_unroll_enabled</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Field removed. </b>
<code>void * dbi_base</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 lanes</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 num_viewport</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 iatu_unroll_enabled</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct pcie_host_ops * ops</code> ➡️ <code>const struct dw_pcie_host_ops * ops</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct irq_domain * msi_domain</code>
</li>
<li>
<b>Field added. </b>
<code>u32 num_vectors</code>
</li>
<li>
<b>Field added. </b>
<code>u32[8] irq_status</code>
</li>
<li>
<b>Field added. </b>
<code>raw_spinlock_t lock</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int msi_data</code> ➡️ <code>dma_addr_t msi_data</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[1] msi_irq_in_use</code> ➡️ <code>long unsigned int[4] msi_irq_in_use</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct page * msi_page</code>
</li>
<li>
<b>Field added. </b>
<code>struct irq_chip * msi_irq_chip</code>
</li>
<li>
<b>Field added. </b>
<code>u32[8] irq_mask</code>
</li>
<li>
<b>Field added. </b>
<code>struct pci_bus * root_bus</code>
</li>
<li>
<b>Field removed. </b>
<code>u32[8] irq_status</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool has_msi_ctrl</code>
</li>
<li>
<b>Field added. </b>
<code>u16 msi_msg</code>
</li>
<li>
<b>Field added. </b>
<code>struct pci_host_bridge * bridge</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 root_bus_nr</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 cfg1_base</code>
</li>
<li>
<b>Field removed. </b>
<code>void * va_cfg1_base</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 cfg1_size</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 mem_base</code>
</li>
<li>
<b>Field removed. </b>
<code>phys_addr_t mem_bus_addr</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 mem_size</code>
</li>
<li>
<b>Field removed. </b>
<code>struct resource * cfg</code>
</li>
<li>
<b>Field removed. </b>
<code>struct resource * io</code>
</li>
<li>
<b>Field removed. </b>
<code>struct resource * mem</code>
</li>
<li>
<b>Field removed. </b>
<code>struct resource * busn</code>
</li>
<li>
<b>Field removed. </b>
<code>struct page * msi_page</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pci_bus * root_bus</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct pcie_port {
    bool has_msi_ctrl;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    u16 msi_msg;
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long unsigned int[4] msi_irq_in_use</code> ➡️ <code>long unsigned int[8] msi_irq_in_use</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct pcie_port {
    u8 root_bus_nr;
    u64 cfg0_base;
    void * va_cfg0_base;
    u32 cfg0_size;
    u64 cfg1_base;
    void * va_cfg1_base;
    u32 cfg1_size;
    resource_size_t io_base;
    phys_addr_t io_bus_addr;
    u32 io_size;
    u64 mem_base;
    phys_addr_t mem_bus_addr;
    u32 mem_size;
    struct resource * cfg;
    struct resource * io;
    struct resource * mem;
    struct resource * busn;
    int irq;
    const struct dw_pcie_host_ops * ops;
    int msi_irq;
    struct irq_domain * irq_domain;
    struct irq_domain * msi_domain;
    dma_addr_t msi_data;
    struct page * msi_page;
    struct irq_chip * msi_irq_chip;
    u32 num_vectors;
    u32[8] irq_mask;
    struct pci_bus * root_bus;
    raw_spinlock_t lock;
    long unsigned int[4] msi_irq_in_use;
}
```
</details>
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
