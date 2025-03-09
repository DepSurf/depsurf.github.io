# Struct: <code>pci_epc_ops</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, enum pci_barno, dma_addr_t, size_t, int) set_bar;
    void (*)(struct pci_epc *, enum pci_barno) clear_bar;
    int (*)(struct pci_epc *, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8) set_msi;
    int (*)(struct pci_epc *) get_msi;
    int (*)(struct pci_epc *, enum pci_epc_irq_type, u8) raise_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, enum pci_barno, dma_addr_t, size_t, int) set_bar;
    void (*)(struct pci_epc *, enum pci_barno) clear_bar;
    int (*)(struct pci_epc *, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8) set_msi;
    int (*)(struct pci_epc *) get_msi;
    int (*)(struct pci_epc *, enum pci_epc_irq_type, u8) raise_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, u8, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, u8, struct pci_epf_bar *) set_bar;
    void (*)(struct pci_epc *, u8, struct pci_epf_bar *) clear_bar;
    int (*)(struct pci_epc *, u8, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, u8, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8, u8) set_msi;
    int (*)(struct pci_epc *, u8) get_msi;
    int (*)(struct pci_epc *, u8, enum pci_epc_irq_type, u8) raise_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, u8, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, u8, struct pci_epf_bar *) set_bar;
    void (*)(struct pci_epc *, u8, struct pci_epf_bar *) clear_bar;
    int (*)(struct pci_epc *, u8, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, u8, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8, u8) set_msi;
    int (*)(struct pci_epc *, u8) get_msi;
    int (*)(struct pci_epc *, u8, u16) set_msix;
    int (*)(struct pci_epc *, u8) get_msix;
    int (*)(struct pci_epc *, u8, enum pci_epc_irq_type, u16) raise_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, u8, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, u8, struct pci_epf_bar *) set_bar;
    void (*)(struct pci_epc *, u8, struct pci_epf_bar *) clear_bar;
    int (*)(struct pci_epc *, u8, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, u8, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8, u8) set_msi;
    int (*)(struct pci_epc *, u8) get_msi;
    int (*)(struct pci_epc *, u8, u16) set_msix;
    int (*)(struct pci_epc *, u8) get_msix;
    int (*)(struct pci_epc *, u8, enum pci_epc_irq_type, u16) raise_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    const struct pci_epc_features * (*)(struct pci_epc *, u8) get_features;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, u8, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, u8, struct pci_epf_bar *) set_bar;
    void (*)(struct pci_epc *, u8, struct pci_epf_bar *) clear_bar;
    int (*)(struct pci_epc *, u8, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, u8, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8, u8) set_msi;
    int (*)(struct pci_epc *, u8) get_msi;
    int (*)(struct pci_epc *, u8, u16) set_msix;
    int (*)(struct pci_epc *, u8) get_msix;
    int (*)(struct pci_epc *, u8, enum pci_epc_irq_type, u16) raise_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    const struct pci_epc_features * (*)(struct pci_epc *, u8) get_features;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, u8, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, u8, struct pci_epf_bar *) set_bar;
    void (*)(struct pci_epc *, u8, struct pci_epf_bar *) clear_bar;
    int (*)(struct pci_epc *, u8, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, u8, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8, u8) set_msi;
    int (*)(struct pci_epc *, u8) get_msi;
    int (*)(struct pci_epc *, u8, u16, enum pci_barno, u32) set_msix;
    int (*)(struct pci_epc *, u8) get_msix;
    int (*)(struct pci_epc *, u8, enum pci_epc_irq_type, u16) raise_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    const struct pci_epc_features * (*)(struct pci_epc *, u8) get_features;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, u8, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, u8, struct pci_epf_bar *) set_bar;
    void (*)(struct pci_epc *, u8, struct pci_epf_bar *) clear_bar;
    int (*)(struct pci_epc *, u8, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, u8, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8, u8) set_msi;
    int (*)(struct pci_epc *, u8) get_msi;
    int (*)(struct pci_epc *, u8, u16, enum pci_barno, u32) set_msix;
    int (*)(struct pci_epc *, u8) get_msix;
    int (*)(struct pci_epc *, u8, enum pci_epc_irq_type, u16) raise_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    const struct pci_epc_features * (*)(struct pci_epc *, u8) get_features;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, u8, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, u8, struct pci_epf_bar *) set_bar;
    void (*)(struct pci_epc *, u8, struct pci_epf_bar *) clear_bar;
    int (*)(struct pci_epc *, u8, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, u8, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8, u8) set_msi;
    int (*)(struct pci_epc *, u8) get_msi;
    int (*)(struct pci_epc *, u8, u16, enum pci_barno, u32) set_msix;
    int (*)(struct pci_epc *, u8) get_msix;
    int (*)(struct pci_epc *, u8, enum pci_epc_irq_type, u16) raise_irq;
    int (*)(struct pci_epc *, u8, phys_addr_t, u8, u32, u32 *, u32 *) map_msi_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    const struct pci_epc_features * (*)(struct pci_epc *, u8) get_features;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, u8, u8, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, u8, u8, struct pci_epf_bar *) set_bar;
    void (*)(struct pci_epc *, u8, u8, struct pci_epf_bar *) clear_bar;
    int (*)(struct pci_epc *, u8, u8, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, u8, u8, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8, u8, u8) set_msi;
    int (*)(struct pci_epc *, u8, u8) get_msi;
    int (*)(struct pci_epc *, u8, u8, u16, enum pci_barno, u32) set_msix;
    int (*)(struct pci_epc *, u8, u8) get_msix;
    int (*)(struct pci_epc *, u8, u8, enum pci_epc_irq_type, u16) raise_irq;
    int (*)(struct pci_epc *, u8, u8, phys_addr_t, u8, u32, u32 *, u32 *) map_msi_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    const struct pci_epc_features * (*)(struct pci_epc *, u8, u8) get_features;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, u8, u8, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, u8, u8, struct pci_epf_bar *) set_bar;
    void (*)(struct pci_epc *, u8, u8, struct pci_epf_bar *) clear_bar;
    int (*)(struct pci_epc *, u8, u8, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, u8, u8, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8, u8, u8) set_msi;
    int (*)(struct pci_epc *, u8, u8) get_msi;
    int (*)(struct pci_epc *, u8, u8, u16, enum pci_barno, u32) set_msix;
    int (*)(struct pci_epc *, u8, u8) get_msix;
    int (*)(struct pci_epc *, u8, u8, enum pci_epc_irq_type, u16) raise_irq;
    int (*)(struct pci_epc *, u8, u8, phys_addr_t, u8, u32, u32 *, u32 *) map_msi_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    const struct pci_epc_features * (*)(struct pci_epc *, u8, u8) get_features;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, u8, u8, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, u8, u8, struct pci_epf_bar *) set_bar;
    void (*)(struct pci_epc *, u8, u8, struct pci_epf_bar *) clear_bar;
    int (*)(struct pci_epc *, u8, u8, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, u8, u8, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8, u8, u8) set_msi;
    int (*)(struct pci_epc *, u8, u8) get_msi;
    int (*)(struct pci_epc *, u8, u8, u16, enum pci_barno, u32) set_msix;
    int (*)(struct pci_epc *, u8, u8) get_msix;
    int (*)(struct pci_epc *, u8, u8, enum pci_epc_irq_type, u16) raise_irq;
    int (*)(struct pci_epc *, u8, u8, phys_addr_t, u8, u32, u32 *, u32 *) map_msi_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    const struct pci_epc_features * (*)(struct pci_epc *, u8, u8) get_features;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, u8, u8, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, u8, u8, struct pci_epf_bar *) set_bar;
    void (*)(struct pci_epc *, u8, u8, struct pci_epf_bar *) clear_bar;
    int (*)(struct pci_epc *, u8, u8, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, u8, u8, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8, u8, u8) set_msi;
    int (*)(struct pci_epc *, u8, u8) get_msi;
    int (*)(struct pci_epc *, u8, u8, u16, enum pci_barno, u32) set_msix;
    int (*)(struct pci_epc *, u8, u8) get_msix;
    int (*)(struct pci_epc *, u8, u8, enum pci_epc_irq_type, u16) raise_irq;
    int (*)(struct pci_epc *, u8, u8, phys_addr_t, u8, u32, u32 *, u32 *) map_msi_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    const struct pci_epc_features * (*)(struct pci_epc *, u8, u8) get_features;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, u8, u8, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, u8, u8, struct pci_epf_bar *) set_bar;
    void (*)(struct pci_epc *, u8, u8, struct pci_epf_bar *) clear_bar;
    int (*)(struct pci_epc *, u8, u8, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, u8, u8, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8, u8, u8) set_msi;
    int (*)(struct pci_epc *, u8, u8) get_msi;
    int (*)(struct pci_epc *, u8, u8, u16, enum pci_barno, u32) set_msix;
    int (*)(struct pci_epc *, u8, u8) get_msix;
    int (*)(struct pci_epc *, u8, u8, unsigned int, u16) raise_irq;
    int (*)(struct pci_epc *, u8, u8, phys_addr_t, u8, u32, u32 *, u32 *) map_msi_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    const struct pci_epc_features * (*)(struct pci_epc *, u8, u8) get_features;
    struct module * owner;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, u8, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, u8, struct pci_epf_bar *) set_bar;
    void (*)(struct pci_epc *, u8, struct pci_epf_bar *) clear_bar;
    int (*)(struct pci_epc *, u8, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, u8, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8, u8) set_msi;
    int (*)(struct pci_epc *, u8) get_msi;
    int (*)(struct pci_epc *, u8, u16) set_msix;
    int (*)(struct pci_epc *, u8) get_msix;
    int (*)(struct pci_epc *, u8, enum pci_epc_irq_type, u16) raise_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    const struct pci_epc_features * (*)(struct pci_epc *, u8) get_features;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, u8, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, u8, struct pci_epf_bar *) set_bar;
    void (*)(struct pci_epc *, u8, struct pci_epf_bar *) clear_bar;
    int (*)(struct pci_epc *, u8, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, u8, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8, u8) set_msi;
    int (*)(struct pci_epc *, u8) get_msi;
    int (*)(struct pci_epc *, u8, u16) set_msix;
    int (*)(struct pci_epc *, u8) get_msix;
    int (*)(struct pci_epc *, u8, enum pci_epc_irq_type, u16) raise_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    const struct pci_epc_features * (*)(struct pci_epc *, u8) get_features;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, u8, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, u8, struct pci_epf_bar *) set_bar;
    void (*)(struct pci_epc *, u8, struct pci_epf_bar *) clear_bar;
    int (*)(struct pci_epc *, u8, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, u8, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8, u8) set_msi;
    int (*)(struct pci_epc *, u8) get_msi;
    int (*)(struct pci_epc *, u8, u16) set_msix;
    int (*)(struct pci_epc *, u8) get_msix;
    int (*)(struct pci_epc *, u8, enum pci_epc_irq_type, u16) raise_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    const struct pci_epc_features * (*)(struct pci_epc *, u8) get_features;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, u8, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, u8, struct pci_epf_bar *) set_bar;
    void (*)(struct pci_epc *, u8, struct pci_epf_bar *) clear_bar;
    int (*)(struct pci_epc *, u8, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, u8, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8, u8) set_msi;
    int (*)(struct pci_epc *, u8) get_msi;
    int (*)(struct pci_epc *, u8, u16) set_msix;
    int (*)(struct pci_epc *, u8) get_msix;
    int (*)(struct pci_epc *, u8, enum pci_epc_irq_type, u16) raise_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    const struct pci_epc_features * (*)(struct pci_epc *, u8) get_features;
    struct module * owner;
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
struct pci_epc_ops {
    int (*)(struct pci_epc *, u8, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, u8, struct pci_epf_bar *) set_bar;
    void (*)(struct pci_epc *, u8, struct pci_epf_bar *) clear_bar;
    int (*)(struct pci_epc *, u8, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, u8, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8, u8) set_msi;
    int (*)(struct pci_epc *, u8) get_msi;
    int (*)(struct pci_epc *, u8, u16) set_msix;
    int (*)(struct pci_epc *, u8) get_msix;
    int (*)(struct pci_epc *, u8, enum pci_epc_irq_type, u16) raise_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    const struct pci_epc_features * (*)(struct pci_epc *, u8) get_features;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, u8, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, u8, struct pci_epf_bar *) set_bar;
    void (*)(struct pci_epc *, u8, struct pci_epf_bar *) clear_bar;
    int (*)(struct pci_epc *, u8, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, u8, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8, u8) set_msi;
    int (*)(struct pci_epc *, u8) get_msi;
    int (*)(struct pci_epc *, u8, u16) set_msix;
    int (*)(struct pci_epc *, u8) get_msix;
    int (*)(struct pci_epc *, u8, enum pci_epc_irq_type, u16) raise_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    const struct pci_epc_features * (*)(struct pci_epc *, u8) get_features;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, u8, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, u8, struct pci_epf_bar *) set_bar;
    void (*)(struct pci_epc *, u8, struct pci_epf_bar *) clear_bar;
    int (*)(struct pci_epc *, u8, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, u8, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8, u8) set_msi;
    int (*)(struct pci_epc *, u8) get_msi;
    int (*)(struct pci_epc *, u8, u16) set_msix;
    int (*)(struct pci_epc *, u8) get_msix;
    int (*)(struct pci_epc *, u8, enum pci_epc_irq_type, u16) raise_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    const struct pci_epc_features * (*)(struct pci_epc *, u8) get_features;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, u8, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, u8, struct pci_epf_bar *) set_bar;
    void (*)(struct pci_epc *, u8, struct pci_epf_bar *) clear_bar;
    int (*)(struct pci_epc *, u8, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, u8, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8, u8) set_msi;
    int (*)(struct pci_epc *, u8) get_msi;
    int (*)(struct pci_epc *, u8, u16) set_msix;
    int (*)(struct pci_epc *, u8) get_msix;
    int (*)(struct pci_epc *, u8, enum pci_epc_irq_type, u16) raise_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    const struct pci_epc_features * (*)(struct pci_epc *, u8) get_features;
    struct module * owner;
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct pci_epc_ops {
    int (*)(struct pci_epc *, struct pci_epf_header *) write_header;
    int (*)(struct pci_epc *, enum pci_barno, dma_addr_t, size_t, int) set_bar;
    void (*)(struct pci_epc *, enum pci_barno) clear_bar;
    int (*)(struct pci_epc *, phys_addr_t, u64, size_t) map_addr;
    void (*)(struct pci_epc *, phys_addr_t) unmap_addr;
    int (*)(struct pci_epc *, u8) set_msi;
    int (*)(struct pci_epc *) get_msi;
    int (*)(struct pci_epc *, enum pci_epc_irq_type, u8) raise_irq;
    int (*)(struct pci_epc *) start;
    void (*)(struct pci_epc *) stop;
    struct module * owner;
}
```
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
<b>Field type changed. </b>
<code>int (*)(struct pci_epc *, struct pci_epf_header *) write_header</code> ➡️ <code>int (*)(struct pci_epc *, u8, struct pci_epf_header *) write_header</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pci_epc *, enum pci_barno, dma_addr_t, size_t, int) set_bar</code> ➡️ <code>int (*)(struct pci_epc *, u8, struct pci_epf_bar *) set_bar</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct pci_epc *, enum pci_barno) clear_bar</code> ➡️ <code>void (*)(struct pci_epc *, u8, struct pci_epf_bar *) clear_bar</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pci_epc *, phys_addr_t, u64, size_t) map_addr</code> ➡️ <code>int (*)(struct pci_epc *, u8, phys_addr_t, u64, size_t) map_addr</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct pci_epc *, phys_addr_t) unmap_addr</code> ➡️ <code>void (*)(struct pci_epc *, u8, phys_addr_t) unmap_addr</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pci_epc *, u8) set_msi</code> ➡️ <code>int (*)(struct pci_epc *, u8, u8) set_msi</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pci_epc *) get_msi</code> ➡️ <code>int (*)(struct pci_epc *, u8) get_msi</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pci_epc *, enum pci_epc_irq_type, u8) raise_irq</code> ➡️ <code>int (*)(struct pci_epc *, u8, enum pci_epc_irq_type, u8) raise_irq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct pci_epc *, u8, u16) set_msix</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct pci_epc *, u8) get_msix</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pci_epc *, u8, enum pci_epc_irq_type, u8) raise_irq</code> ➡️ <code>int (*)(struct pci_epc *, u8, enum pci_epc_irq_type, u16) raise_irq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct pci_epc_features * (*)(struct pci_epc *, u8) get_features</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pci_epc *, u8, u16) set_msix</code> ➡️ <code>int (*)(struct pci_epc *, u8, u16, enum pci_barno, u32) set_msix</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct pci_epc *, u8, phys_addr_t, u8, u32, u32 *, u32 *) map_msi_irq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pci_epc *, u8, struct pci_epf_header *) write_header</code> ➡️ <code>int (*)(struct pci_epc *, u8, u8, struct pci_epf_header *) write_header</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pci_epc *, u8, struct pci_epf_bar *) set_bar</code> ➡️ <code>int (*)(struct pci_epc *, u8, u8, struct pci_epf_bar *) set_bar</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct pci_epc *, u8, struct pci_epf_bar *) clear_bar</code> ➡️ <code>void (*)(struct pci_epc *, u8, u8, struct pci_epf_bar *) clear_bar</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pci_epc *, u8, phys_addr_t, u64, size_t) map_addr</code> ➡️ <code>int (*)(struct pci_epc *, u8, u8, phys_addr_t, u64, size_t) map_addr</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct pci_epc *, u8, phys_addr_t) unmap_addr</code> ➡️ <code>void (*)(struct pci_epc *, u8, u8, phys_addr_t) unmap_addr</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pci_epc *, u8, u8) set_msi</code> ➡️ <code>int (*)(struct pci_epc *, u8, u8, u8) set_msi</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pci_epc *, u8) get_msi</code> ➡️ <code>int (*)(struct pci_epc *, u8, u8) get_msi</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pci_epc *, u8, u16, enum pci_barno, u32) set_msix</code> ➡️ <code>int (*)(struct pci_epc *, u8, u8, u16, enum pci_barno, u32) set_msix</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pci_epc *, u8) get_msix</code> ➡️ <code>int (*)(struct pci_epc *, u8, u8) get_msix</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pci_epc *, u8, enum pci_epc_irq_type, u16) raise_irq</code> ➡️ <code>int (*)(struct pci_epc *, u8, u8, enum pci_epc_irq_type, u16) raise_irq</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pci_epc *, u8, phys_addr_t, u8, u32, u32 *, u32 *) map_msi_irq</code> ➡️ <code>int (*)(struct pci_epc *, u8, u8, phys_addr_t, u8, u32, u32 *, u32 *) map_msi_irq</code>
</li>
<li>
<b>Field type changed. </b>
<code>const struct pci_epc_features * (*)(struct pci_epc *, u8) get_features</code> ➡️ <code>const struct pci_epc_features * (*)(struct pci_epc *, u8, u8) get_features</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pci_epc *, u8, u8, enum pci_epc_irq_type, u16) raise_irq</code> ➡️ <code>int (*)(struct pci_epc *, u8, u8, unsigned int, u16) raise_irq</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
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
