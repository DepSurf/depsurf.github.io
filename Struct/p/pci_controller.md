# Struct: <code>pci_controller</code>

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
struct pci_controller {
    struct pci_bus * bus;
    char is_dynamic;
    int node;
    struct device_node * dn;
    struct list_head list_node;
    struct device * parent;
    int first_busno;
    int last_busno;
    int self_busno;
    struct resource busn;
    void * io_base_virt;
    void * io_base_alloc;
    resource_size_t io_base_phys;
    resource_size_t pci_io_size;
    resource_size_t isa_mem_phys;
    resource_size_t isa_mem_size;
    struct pci_controller_ops controller_ops;
    struct pci_ops * ops;
    unsigned int * cfg_addr;
    void * cfg_data;
    u32 indirect_type;
    struct resource io_resource;
    struct resource[3] mem_resources;
    resource_size_t[3] mem_offset;
    int global_number;
    resource_size_t dma_window_base_cur;
    resource_size_t dma_window_size;
    long unsigned int buid;
    struct pci_dn * pci_data;
    void * private_data;
    struct npu * npu;
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
struct pci_controller {
    struct pci_bus * bus;
    char is_dynamic;
    int node;
    struct device_node * dn;
    struct list_head list_node;
    struct device * parent;
    int first_busno;
    int last_busno;
    int self_busno;
    struct resource busn;
    void * io_base_virt;
    void * io_base_alloc;
    resource_size_t io_base_phys;
    resource_size_t pci_io_size;
    resource_size_t isa_mem_phys;
    resource_size_t isa_mem_size;
    struct pci_controller_ops controller_ops;
    struct pci_ops * ops;
    unsigned int * cfg_addr;
    void * cfg_data;
    u32 indirect_type;
    struct resource io_resource;
    struct resource[3] mem_resources;
    resource_size_t[3] mem_offset;
    int global_number;
    resource_size_t dma_window_base_cur;
    resource_size_t dma_window_size;
    long unsigned int buid;
    struct pci_dn * pci_data;
    void * private_data;
    struct npu * npu;
}
```
</details>
</li>
</ul>
