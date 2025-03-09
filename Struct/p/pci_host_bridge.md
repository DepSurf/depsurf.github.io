# Struct: <code>pci_host_bridge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct list_head windows;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    unsigned int ignore_reset_delay;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct list_head windows;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    unsigned int ignore_reset_delay;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    void * sysdata;
    int busnr;
    struct list_head windows;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    struct msi_controller * msi;
    unsigned int ignore_reset_delay;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    void * sysdata;
    int busnr;
    struct list_head windows;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    struct msi_controller * msi;
    unsigned int ignore_reset_delay;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    void * sysdata;
    int busnr;
    struct list_head windows;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    struct msi_controller * msi;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    void * sysdata;
    int busnr;
    struct list_head windows;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    struct msi_controller * msi;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    unsigned int native_aer;
    unsigned int native_pcie_hotplug;
    unsigned int native_shpc_hotplug;
    unsigned int native_pme;
    unsigned int native_ltr;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    void * sysdata;
    int busnr;
    struct list_head windows;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    struct msi_controller * msi;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    unsigned int native_aer;
    unsigned int native_pcie_hotplug;
    unsigned int native_shpc_hotplug;
    unsigned int native_pme;
    unsigned int native_ltr;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    void * sysdata;
    int busnr;
    struct list_head windows;
    struct list_head dma_ranges;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    struct msi_controller * msi;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    unsigned int native_aer;
    unsigned int native_pcie_hotplug;
    unsigned int native_shpc_hotplug;
    unsigned int native_pme;
    unsigned int native_ltr;
    unsigned int preserve_config;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    void * sysdata;
    int busnr;
    struct list_head windows;
    struct list_head dma_ranges;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    struct msi_controller * msi;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    unsigned int native_aer;
    unsigned int native_pcie_hotplug;
    unsigned int native_shpc_hotplug;
    unsigned int native_pme;
    unsigned int native_ltr;
    unsigned int preserve_config;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    void * sysdata;
    int busnr;
    struct list_head windows;
    struct list_head dma_ranges;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    struct msi_controller * msi;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    unsigned int native_aer;
    unsigned int native_pcie_hotplug;
    unsigned int native_shpc_hotplug;
    unsigned int native_pme;
    unsigned int native_ltr;
    unsigned int native_dpc;
    unsigned int preserve_config;
    unsigned int size_windows;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    struct pci_ops * child_ops;
    void * sysdata;
    int busnr;
    struct list_head windows;
    struct list_head dma_ranges;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    struct msi_controller * msi;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    unsigned int native_aer;
    unsigned int native_pcie_hotplug;
    unsigned int native_shpc_hotplug;
    unsigned int native_pme;
    unsigned int native_ltr;
    unsigned int native_dpc;
    unsigned int preserve_config;
    unsigned int size_windows;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    struct pci_ops * child_ops;
    void * sysdata;
    int busnr;
    struct list_head windows;
    struct list_head dma_ranges;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    unsigned int native_aer;
    unsigned int native_pcie_hotplug;
    unsigned int native_shpc_hotplug;
    unsigned int native_pme;
    unsigned int native_ltr;
    unsigned int native_dpc;
    unsigned int preserve_config;
    unsigned int size_windows;
    unsigned int msi_domain;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    struct pci_ops * child_ops;
    void * sysdata;
    int busnr;
    int domain_nr;
    struct list_head windows;
    struct list_head dma_ranges;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    unsigned int native_aer;
    unsigned int native_pcie_hotplug;
    unsigned int native_shpc_hotplug;
    unsigned int native_pme;
    unsigned int native_ltr;
    unsigned int native_dpc;
    unsigned int preserve_config;
    unsigned int size_windows;
    unsigned int msi_domain;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    struct pci_ops * child_ops;
    void * sysdata;
    int busnr;
    int domain_nr;
    struct list_head windows;
    struct list_head dma_ranges;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    unsigned int native_aer;
    unsigned int native_pcie_hotplug;
    unsigned int native_shpc_hotplug;
    unsigned int native_pme;
    unsigned int native_ltr;
    unsigned int native_dpc;
    unsigned int preserve_config;
    unsigned int size_windows;
    unsigned int msi_domain;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    struct pci_ops * child_ops;
    void * sysdata;
    int busnr;
    int domain_nr;
    struct list_head windows;
    struct list_head dma_ranges;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    unsigned int no_inc_mrrs;
    unsigned int native_aer;
    unsigned int native_pcie_hotplug;
    unsigned int native_shpc_hotplug;
    unsigned int native_pme;
    unsigned int native_ltr;
    unsigned int native_dpc;
    unsigned int preserve_config;
    unsigned int size_windows;
    unsigned int msi_domain;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    struct pci_ops * child_ops;
    void * sysdata;
    int busnr;
    int domain_nr;
    struct list_head windows;
    struct list_head dma_ranges;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    unsigned int no_inc_mrrs;
    unsigned int native_aer;
    unsigned int native_pcie_hotplug;
    unsigned int native_shpc_hotplug;
    unsigned int native_pme;
    unsigned int native_ltr;
    unsigned int native_dpc;
    unsigned int native_cxl_error;
    unsigned int preserve_config;
    unsigned int size_windows;
    unsigned int msi_domain;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    struct pci_ops * child_ops;
    void * sysdata;
    int busnr;
    int domain_nr;
    struct list_head windows;
    struct list_head dma_ranges;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    unsigned int no_inc_mrrs;
    unsigned int native_aer;
    unsigned int native_pcie_hotplug;
    unsigned int native_shpc_hotplug;
    unsigned int native_pme;
    unsigned int native_ltr;
    unsigned int native_dpc;
    unsigned int native_cxl_error;
    unsigned int preserve_config;
    unsigned int size_windows;
    unsigned int msi_domain;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
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
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    void * sysdata;
    int busnr;
    struct list_head windows;
    struct list_head dma_ranges;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    struct msi_controller * msi;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    unsigned int native_aer;
    unsigned int native_pcie_hotplug;
    unsigned int native_shpc_hotplug;
    unsigned int native_pme;
    unsigned int native_ltr;
    unsigned int preserve_config;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    void * sysdata;
    int busnr;
    struct list_head windows;
    struct list_head dma_ranges;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    struct msi_controller * msi;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    unsigned int native_aer;
    unsigned int native_pcie_hotplug;
    unsigned int native_shpc_hotplug;
    unsigned int native_pme;
    unsigned int native_ltr;
    unsigned int preserve_config;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    void * sysdata;
    int busnr;
    struct list_head windows;
    struct list_head dma_ranges;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    struct msi_controller * msi;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    unsigned int native_aer;
    unsigned int native_pcie_hotplug;
    unsigned int native_shpc_hotplug;
    unsigned int native_pme;
    unsigned int native_ltr;
    unsigned int preserve_config;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    void * sysdata;
    int busnr;
    struct list_head windows;
    struct list_head dma_ranges;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    struct msi_controller * msi;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    unsigned int native_aer;
    unsigned int native_pcie_hotplug;
    unsigned int native_shpc_hotplug;
    unsigned int native_pme;
    unsigned int native_ltr;
    unsigned int preserve_config;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
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
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    void * sysdata;
    int busnr;
    struct list_head windows;
    struct list_head dma_ranges;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    struct msi_controller * msi;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    unsigned int native_aer;
    unsigned int native_pcie_hotplug;
    unsigned int native_shpc_hotplug;
    unsigned int native_pme;
    unsigned int native_ltr;
    unsigned int preserve_config;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    void * sysdata;
    int busnr;
    struct list_head windows;
    struct list_head dma_ranges;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    struct msi_controller * msi;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    unsigned int native_aer;
    unsigned int native_pcie_hotplug;
    unsigned int native_shpc_hotplug;
    unsigned int native_pme;
    unsigned int native_ltr;
    unsigned int preserve_config;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    void * sysdata;
    int busnr;
    struct list_head windows;
    struct list_head dma_ranges;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    struct msi_controller * msi;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    unsigned int native_aer;
    unsigned int native_pcie_hotplug;
    unsigned int native_shpc_hotplug;
    unsigned int native_pme;
    unsigned int native_ltr;
    unsigned int preserve_config;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pci_host_bridge {
    struct device dev;
    struct pci_bus * bus;
    struct pci_ops * ops;
    void * sysdata;
    int busnr;
    struct list_head windows;
    struct list_head dma_ranges;
    u8 (*)(struct pci_dev *, u8 *) swizzle_irq;
    int (*)(const struct pci_dev *, u8, u8) map_irq;
    void (*)(struct pci_host_bridge *) release_fn;
    void * release_data;
    struct msi_controller * msi;
    unsigned int ignore_reset_delay;
    unsigned int no_ext_tags;
    unsigned int native_aer;
    unsigned int native_pcie_hotplug;
    unsigned int native_shpc_hotplug;
    unsigned int native_pme;
    unsigned int native_ltr;
    unsigned int preserve_config;
    resource_size_t (*)(struct pci_dev *, const struct resource *, resource_size_t, resource_size_t, resource_size_t) align_resource;
    long unsigned int[0] private;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct pci_ops * ops</code>
</li>
<li>
<b>Field added. </b>
<code>void * sysdata</code>
</li>
<li>
<b>Field added. </b>
<code>int busnr</code>
</li>
<li>
<b>Field added. </b>
<code>struct msi_controller * msi</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[0] private</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 (*)(struct pci_dev *, u8 *) swizzle_irq</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(const struct pci_dev *, u8, u8) map_irq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int no_ext_tags</code>
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
<code>unsigned int native_aer</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int native_pcie_hotplug</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int native_shpc_hotplug</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int native_pme</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int native_ltr</code>
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
<code>struct list_head dma_ranges</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int preserve_config</code>
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
<code>unsigned int native_dpc</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int size_windows</code>
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
<code>struct pci_ops * child_ops</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int msi_domain</code>
</li>
<li>
<b>Field removed. </b>
<code>struct msi_controller * msi</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int domain_nr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int no_inc_mrrs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int native_cxl_error</code>
</li>
</ul>
</details>
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
