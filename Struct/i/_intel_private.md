# Struct: <code>_intel_private</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    unsigned int stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    unsigned int stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    unsigned int stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    unsigned int stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    unsigned int stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    resource_size_t stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    resource_size_t stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    resource_size_t stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    resource_size_t stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    resource_size_t stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    resource_size_t stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    resource_size_t stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    resource_size_t stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    resource_size_t stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    resource_size_t stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    resource_size_t stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    resource_size_t stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    resource_size_t stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    resource_size_t stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    resource_size_t stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    resource_size_t stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<code>unsigned int stolen_size</code> ➡️ <code>resource_size_t stolen_size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    resource_size_t stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    resource_size_t stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    resource_size_t stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct _intel_private {
    const struct intel_gtt_driver * driver;
    struct pci_dev * pcidev;
    struct pci_dev * bridge_dev;
    u8 * registers;
    phys_addr_t gtt_phys_addr;
    u32 PGETBL_save;
    u32 * gtt;
    bool clear_fake_agp;
    int num_dcache_entries;
    void * i9xx_flush_page;
    char * i81x_gtt_table;
    struct resource ifp_resource;
    int resource_valid;
    struct page * scratch_page;
    phys_addr_t scratch_page_dma;
    int refcount;
    unsigned int needs_dmar;
    phys_addr_t gma_bus_addr;
    resource_size_t stolen_size;
    unsigned int gtt_total_entries;
    unsigned int gtt_mappable_entries;
}
```
</details>
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
