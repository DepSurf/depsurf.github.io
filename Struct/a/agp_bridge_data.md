# Struct: <code>agp_bridge_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
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
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct agp_bridge_data {
    const struct agp_version * version;
    const struct agp_bridge_driver * driver;
    const struct vm_operations_struct * vm_ops;
    void * previous_size;
    void * current_size;
    void * dev_private_data;
    struct pci_dev * dev;
    u32 * gatt_table;
    u32 * gatt_table_real;
    long unsigned int scratch_page;
    struct page * scratch_page_page;
    dma_addr_t scratch_page_dma;
    long unsigned int gart_bus_addr;
    long unsigned int gatt_bus_addr;
    u32 mode;
    enum chipset_type type;
    long unsigned int * key_list;
    atomic_t current_memory_agp;
    atomic_t agp_in_use;
    int max_memory_agp;
    int aperture_size_idx;
    int capndx;
    int flags;
    char major_version;
    char minor_version;
    struct list_head list;
    u32 apbase_config;
    struct list_head mapped_list;
    spinlock_t mapped_lock;
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
