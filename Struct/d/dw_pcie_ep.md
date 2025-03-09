# Struct: <code>dw_pcie_ep</code>

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
struct dw_pcie_ep {
    struct pci_epc * epc;
    struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int ib_window_map;
    long unsigned int ob_window_map;
    u32 num_ib_windows;
    u32 num_ob_windows;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep {
    struct pci_epc * epc;
    struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int ib_window_map;
    long unsigned int ob_window_map;
    u32 num_ib_windows;
    u32 num_ob_windows;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep {
    struct pci_epc * epc;
    struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int * ib_window_map;
    long unsigned int * ob_window_map;
    u32 num_ib_windows;
    u32 num_ob_windows;
    void * msi_mem;
    phys_addr_t msi_mem_phys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep {
    struct pci_epc * epc;
    struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int * ib_window_map;
    long unsigned int * ob_window_map;
    u32 num_ib_windows;
    u32 num_ob_windows;
    void * msi_mem;
    phys_addr_t msi_mem_phys;
    u8 msi_cap;
    u8 msix_cap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep {
    struct pci_epc * epc;
    const struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int * ib_window_map;
    long unsigned int * ob_window_map;
    u32 num_ib_windows;
    u32 num_ob_windows;
    void * msi_mem;
    phys_addr_t msi_mem_phys;
    u8 msi_cap;
    u8 msix_cap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep {
    struct pci_epc * epc;
    const struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int * ib_window_map;
    long unsigned int * ob_window_map;
    u32 num_ib_windows;
    u32 num_ob_windows;
    void * msi_mem;
    phys_addr_t msi_mem_phys;
    u8 msi_cap;
    u8 msix_cap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep {
    struct pci_epc * epc;
    const struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int * ib_window_map;
    long unsigned int * ob_window_map;
    u32 num_ib_windows;
    u32 num_ob_windows;
    void * msi_mem;
    phys_addr_t msi_mem_phys;
    u8 msi_cap;
    u8 msix_cap;
    struct pci_epf_bar *[6] epf_bar;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep {
    struct pci_epc * epc;
    struct list_head func_list;
    const struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int * ib_window_map;
    long unsigned int * ob_window_map;
    void * msi_mem;
    phys_addr_t msi_mem_phys;
    struct pci_epf_bar *[6] epf_bar;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep {
    struct pci_epc * epc;
    struct list_head func_list;
    const struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int * ib_window_map;
    long unsigned int * ob_window_map;
    void * msi_mem;
    phys_addr_t msi_mem_phys;
    struct pci_epf_bar *[6] epf_bar;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep {
    struct pci_epc * epc;
    struct list_head func_list;
    const struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int * ib_window_map;
    long unsigned int * ob_window_map;
    void * msi_mem;
    phys_addr_t msi_mem_phys;
    struct pci_epf_bar *[6] epf_bar;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep {
    struct pci_epc * epc;
    struct list_head func_list;
    const struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int * ib_window_map;
    long unsigned int * ob_window_map;
    void * msi_mem;
    phys_addr_t msi_mem_phys;
    struct pci_epf_bar *[6] epf_bar;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep {
    struct pci_epc * epc;
    struct list_head func_list;
    const struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int * ib_window_map;
    long unsigned int * ob_window_map;
    void * msi_mem;
    phys_addr_t msi_mem_phys;
    struct pci_epf_bar *[6] epf_bar;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep {
    struct pci_epc * epc;
    struct list_head func_list;
    const struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int * ib_window_map;
    long unsigned int * ob_window_map;
    void * msi_mem;
    phys_addr_t msi_mem_phys;
    struct pci_epf_bar *[6] epf_bar;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep {
    struct pci_epc * epc;
    struct list_head func_list;
    const struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int * ib_window_map;
    long unsigned int * ob_window_map;
    void * msi_mem;
    phys_addr_t msi_mem_phys;
    struct pci_epf_bar *[6] epf_bar;
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
struct dw_pcie_ep {
    struct pci_epc * epc;
    const struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int * ib_window_map;
    long unsigned int * ob_window_map;
    u32 num_ib_windows;
    u32 num_ob_windows;
    void * msi_mem;
    phys_addr_t msi_mem_phys;
    u8 msi_cap;
    u8 msix_cap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dw_pcie_ep {
    struct pci_epc * epc;
    const struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int * ib_window_map;
    long unsigned int * ob_window_map;
    u32 num_ib_windows;
    u32 num_ob_windows;
    void * msi_mem;
    phys_addr_t msi_mem_phys;
    u8 msi_cap;
    u8 msix_cap;
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
struct dw_pcie_ep {
    struct pci_epc * epc;
    const struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int * ib_window_map;
    long unsigned int * ob_window_map;
    u32 num_ib_windows;
    u32 num_ob_windows;
    void * msi_mem;
    phys_addr_t msi_mem_phys;
    u8 msi_cap;
    u8 msix_cap;
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
struct dw_pcie_ep {
    struct pci_epc * epc;
    const struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int * ib_window_map;
    long unsigned int * ob_window_map;
    u32 num_ib_windows;
    u32 num_ob_windows;
    void * msi_mem;
    phys_addr_t msi_mem_phys;
    u8 msi_cap;
    u8 msix_cap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep {
    struct pci_epc * epc;
    const struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int * ib_window_map;
    long unsigned int * ob_window_map;
    u32 num_ib_windows;
    u32 num_ob_windows;
    void * msi_mem;
    phys_addr_t msi_mem_phys;
    u8 msi_cap;
    u8 msix_cap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep {
    struct pci_epc * epc;
    const struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int * ib_window_map;
    long unsigned int * ob_window_map;
    u32 num_ib_windows;
    u32 num_ob_windows;
    void * msi_mem;
    phys_addr_t msi_mem_phys;
    u8 msi_cap;
    u8 msix_cap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep {
    struct pci_epc * epc;
    const struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int * ib_window_map;
    long unsigned int * ob_window_map;
    u32 num_ib_windows;
    u32 num_ob_windows;
    void * msi_mem;
    phys_addr_t msi_mem_phys;
    u8 msi_cap;
    u8 msix_cap;
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
struct dw_pcie_ep {
    struct pci_epc * epc;
    struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int ib_window_map;
    long unsigned int ob_window_map;
    u32 num_ib_windows;
    u32 num_ob_windows;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>size_t page_size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * msi_mem</code>
</li>
<li>
<b>Field added. </b>
<code>phys_addr_t msi_mem_phys</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int ib_window_map</code> ➡️ <code>long unsigned int * ib_window_map</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int ob_window_map</code> ➡️ <code>long unsigned int * ob_window_map</code>
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
<code>u8 msi_cap</code>
</li>
<li>
<b>Field added. </b>
<code>u8 msix_cap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct dw_pcie_ep_ops * ops</code> ➡️ <code>const struct dw_pcie_ep_ops * ops</code>
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
<b>Field added. </b>
<code>struct pci_epf_bar *[6] epf_bar</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head func_list</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 num_ib_windows</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 num_ob_windows</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 msi_cap</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 msix_cap</code>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct dw_pcie_ep {
    struct pci_epc * epc;
    const struct dw_pcie_ep_ops * ops;
    phys_addr_t phys_base;
    size_t addr_size;
    size_t page_size;
    u8[6] bar_to_atu;
    phys_addr_t * outbound_addr;
    long unsigned int * ib_window_map;
    long unsigned int * ob_window_map;
    u32 num_ib_windows;
    u32 num_ob_windows;
    void * msi_mem;
    phys_addr_t msi_mem_phys;
    u8 msi_cap;
    u8 msix_cap;
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
