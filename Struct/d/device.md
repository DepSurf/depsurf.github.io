# Struct: <code>device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct device {
    struct device * parent;
    struct device_private * p;
    struct kobject kobj;
    const char * init_name;
    const struct device_type * type;
    struct mutex mutex;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct irq_domain * msi_domain;
    struct dev_pin_info * pins;
    struct list_head msi_list;
    int numa_node;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    long unsigned int dma_pfn_offset;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct dma_coherent_mem * dma_mem;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct klist_node knode_class;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    bool offline_disabled;
    bool offline;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct device {
    struct device * parent;
    struct device_private * p;
    struct kobject kobj;
    const char * init_name;
    const struct device_type * type;
    struct mutex mutex;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct irq_domain * msi_domain;
    struct dev_pin_info * pins;
    struct list_head msi_list;
    int numa_node;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    long unsigned int dma_pfn_offset;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct dma_coherent_mem * dma_mem;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct klist_node knode_class;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    bool offline_disabled;
    bool offline;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct device {
    struct device * parent;
    struct device_private * p;
    struct kobject kobj;
    const char * init_name;
    const struct device_type * type;
    struct mutex mutex;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct irq_domain * msi_domain;
    struct dev_pin_info * pins;
    struct list_head msi_list;
    int numa_node;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    long unsigned int dma_pfn_offset;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct dma_coherent_mem * dma_mem;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct klist_node knode_class;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct iommu_fwspec * iommu_fwspec;
    bool offline_disabled;
    bool offline;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct device {
    struct device * parent;
    struct device_private * p;
    struct kobject kobj;
    const char * init_name;
    const struct device_type * type;
    struct mutex mutex;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct irq_domain * msi_domain;
    struct dev_pin_info * pins;
    struct list_head msi_list;
    int numa_node;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    long unsigned int dma_pfn_offset;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct dma_coherent_mem * dma_mem;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct klist_node knode_class;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct iommu_fwspec * iommu_fwspec;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct device {
    struct device * parent;
    struct device_private * p;
    struct kobject kobj;
    const char * init_name;
    const struct device_type * type;
    struct mutex mutex;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct irq_domain * msi_domain;
    struct dev_pin_info * pins;
    struct list_head msi_list;
    int numa_node;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    long unsigned int dma_pfn_offset;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct dma_coherent_mem * dma_mem;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct klist_node knode_class;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct iommu_fwspec * iommu_fwspec;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct device {
    struct device * parent;
    struct device_private * p;
    struct kobject kobj;
    const char * init_name;
    const struct device_type * type;
    struct mutex mutex;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct irq_domain * msi_domain;
    struct dev_pin_info * pins;
    struct list_head msi_list;
    int numa_node;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    long unsigned int dma_pfn_offset;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct dma_coherent_mem * dma_mem;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct klist_node knode_class;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct iommu_fwspec * iommu_fwspec;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
    bool dma_32bit_limit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct device {
    struct device * parent;
    struct device_private * p;
    struct kobject kobj;
    const char * init_name;
    const struct device_type * type;
    struct mutex mutex;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct irq_domain * msi_domain;
    struct dev_pin_info * pins;
    struct list_head msi_list;
    int numa_node;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    u64 bus_dma_mask;
    long unsigned int dma_pfn_offset;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct dma_coherent_mem * dma_mem;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct klist_node knode_class;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct iommu_fwspec * iommu_fwspec;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct device {
    struct kobject kobj;
    struct device * parent;
    struct device_private * p;
    const char * init_name;
    const struct device_type * type;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct mutex mutex;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct irq_domain * msi_domain;
    struct dev_pin_info * pins;
    struct list_head msi_list;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    u64 bus_dma_mask;
    long unsigned int dma_pfn_offset;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct dma_coherent_mem * dma_mem;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    int numa_node;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct iommu_fwspec * iommu_fwspec;
    struct iommu_param * iommu_param;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct device {
    struct kobject kobj;
    struct device * parent;
    struct device_private * p;
    const char * init_name;
    const struct device_type * type;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct mutex mutex;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct irq_domain * msi_domain;
    struct dev_pin_info * pins;
    struct list_head msi_list;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    u64 bus_dma_mask;
    long unsigned int dma_pfn_offset;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    int numa_node;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct iommu_fwspec * iommu_fwspec;
    struct iommu_param * iommu_param;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct device {
    struct kobject kobj;
    struct device * parent;
    struct device_private * p;
    const char * init_name;
    const struct device_type * type;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct mutex mutex;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct irq_domain * msi_domain;
    struct dev_pin_info * pins;
    struct list_head msi_list;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    u64 bus_dma_limit;
    long unsigned int dma_pfn_offset;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    int numa_node;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct dev_iommu * iommu;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
    bool state_synced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct device {
    struct kobject kobj;
    struct device * parent;
    struct device_private * p;
    const char * init_name;
    const struct device_type * type;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct mutex mutex;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct em_perf_domain * em_pd;
    struct irq_domain * msi_domain;
    struct dev_pin_info * pins;
    struct list_head msi_list;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    u64 bus_dma_limit;
    const struct bus_dma_region * dma_range_map;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    int numa_node;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct dev_iommu * iommu;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
    bool state_synced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct device {
    struct kobject kobj;
    struct device * parent;
    struct device_private * p;
    const char * init_name;
    const struct device_type * type;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct mutex mutex;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct em_perf_domain * em_pd;
    struct irq_domain * msi_domain;
    struct dev_pin_info * pins;
    raw_spinlock_t msi_lock;
    struct list_head msi_list;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    u64 bus_dma_limit;
    const struct bus_dma_region * dma_range_map;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    int numa_node;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct dev_iommu * iommu;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
    bool state_synced;
    bool can_match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct device {
    struct kobject kobj;
    struct device * parent;
    struct device_private * p;
    const char * init_name;
    const struct device_type * type;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct mutex mutex;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct em_perf_domain * em_pd;
    struct irq_domain * msi_domain;
    struct dev_pin_info * pins;
    raw_spinlock_t msi_lock;
    struct list_head msi_list;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    u64 bus_dma_limit;
    const struct bus_dma_region * dma_range_map;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct io_tlb_mem * dma_io_tlb_mem;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    int numa_node;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct dev_iommu * iommu;
    enum device_removable removable;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
    bool state_synced;
    bool can_match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct device {
    struct kobject kobj;
    struct device * parent;
    struct device_private * p;
    const char * init_name;
    const struct device_type * type;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct mutex mutex;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct em_perf_domain * em_pd;
    struct dev_pin_info * pins;
    struct dev_msi_info msi;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    u64 bus_dma_limit;
    const struct bus_dma_region * dma_range_map;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct io_tlb_mem * dma_io_tlb_mem;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    int numa_node;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct dev_iommu * iommu;
    struct device_physical_location * physical_location;
    enum device_removable removable;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
    bool state_synced;
    bool can_match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct device {
    struct kobject kobj;
    struct device * parent;
    struct device_private * p;
    const char * init_name;
    const struct device_type * type;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct mutex mutex;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct em_perf_domain * em_pd;
    struct dev_pin_info * pins;
    struct dev_msi_info msi;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    u64 bus_dma_limit;
    const struct bus_dma_region * dma_range_map;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct io_tlb_mem * dma_io_tlb_mem;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    int numa_node;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct dev_iommu * iommu;
    struct device_physical_location * physical_location;
    enum device_removable removable;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
    bool state_synced;
    bool can_match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct device {
    struct kobject kobj;
    struct device * parent;
    struct device_private * p;
    const char * init_name;
    const struct device_type * type;
    const struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct mutex mutex;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct em_perf_domain * em_pd;
    struct dev_pin_info * pins;
    struct dev_msi_info msi;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    u64 bus_dma_limit;
    const struct bus_dma_region * dma_range_map;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct io_tlb_mem * dma_io_tlb_mem;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    int numa_node;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    const struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct dev_iommu * iommu;
    struct device_physical_location * physical_location;
    enum device_removable removable;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
    bool state_synced;
    bool can_match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct device {
    struct kobject kobj;
    struct device * parent;
    struct device_private * p;
    const char * init_name;
    const struct device_type * type;
    const struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct mutex mutex;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct em_perf_domain * em_pd;
    struct dev_pin_info * pins;
    struct dev_msi_info msi;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    u64 bus_dma_limit;
    const struct bus_dma_region * dma_range_map;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct io_tlb_mem * dma_io_tlb_mem;
    struct list_head dma_io_tlb_pools;
    spinlock_t dma_io_tlb_lock;
    bool dma_uses_io_tlb;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    int numa_node;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    const struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct dev_iommu * iommu;
    struct device_physical_location * physical_location;
    enum device_removable removable;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
    bool state_synced;
    bool can_match;
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
struct device {
    struct kobject kobj;
    struct device * parent;
    struct device_private * p;
    const char * init_name;
    const struct device_type * type;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct mutex mutex;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct irq_domain * msi_domain;
    struct dev_pin_info * pins;
    struct list_head msi_list;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    u64 bus_dma_mask;
    long unsigned int dma_pfn_offset;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct dma_coherent_mem * dma_mem;
    struct cma * cma_area;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    int numa_node;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct iommu_fwspec * iommu_fwspec;
    struct iommu_param * iommu_param;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
    bool dma_coherent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct device {
    struct kobject kobj;
    struct device * parent;
    struct device_private * p;
    const char * init_name;
    const struct device_type * type;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct mutex mutex;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct irq_domain * msi_domain;
    struct dev_pin_info * pins;
    struct list_head msi_list;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    u64 bus_dma_mask;
    long unsigned int dma_pfn_offset;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct dma_coherent_mem * dma_mem;
    struct cma * cma_area;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct iommu_fwspec * iommu_fwspec;
    struct iommu_param * iommu_param;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct device {
    struct kobject kobj;
    struct device * parent;
    struct device_private * p;
    const char * init_name;
    const struct device_type * type;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct mutex mutex;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct dev_pin_info * pins;
    struct list_head msi_list;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    u64 bus_dma_mask;
    long unsigned int dma_pfn_offset;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct dma_coherent_mem * dma_mem;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    int numa_node;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct iommu_fwspec * iommu_fwspec;
    struct iommu_param * iommu_param;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct device {
    struct kobject kobj;
    struct device * parent;
    struct device_private * p;
    const char * init_name;
    const struct device_type * type;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct mutex mutex;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct irq_domain * msi_domain;
    struct dev_pin_info * pins;
    struct list_head msi_list;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    u64 bus_dma_mask;
    long unsigned int dma_pfn_offset;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct dma_coherent_mem * dma_mem;
    struct cma * cma_area;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct iommu_fwspec * iommu_fwspec;
    struct iommu_param * iommu_param;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
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
struct device {
    struct kobject kobj;
    struct device * parent;
    struct device_private * p;
    const char * init_name;
    const struct device_type * type;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct mutex mutex;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct irq_domain * msi_domain;
    struct dev_pin_info * pins;
    struct list_head msi_list;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    u64 bus_dma_mask;
    long unsigned int dma_pfn_offset;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct cma * cma_area;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    int numa_node;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct iommu_fwspec * iommu_fwspec;
    struct iommu_param * iommu_param;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct device {
    struct kobject kobj;
    struct device * parent;
    struct device_private * p;
    const char * init_name;
    const struct device_type * type;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct mutex mutex;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct irq_domain * msi_domain;
    struct dev_pin_info * pins;
    struct list_head msi_list;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    u64 bus_dma_mask;
    long unsigned int dma_pfn_offset;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    int numa_node;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct iommu_fwspec * iommu_fwspec;
    struct iommu_param * iommu_param;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct device {
    struct kobject kobj;
    struct device * parent;
    struct device_private * p;
    const char * init_name;
    const struct device_type * type;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct mutex mutex;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct irq_domain * msi_domain;
    struct dev_pin_info * pins;
    struct list_head msi_list;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    u64 bus_dma_mask;
    long unsigned int dma_pfn_offset;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    int numa_node;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct iommu_fwspec * iommu_fwspec;
    struct iommu_param * iommu_param;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct device {
    struct kobject kobj;
    struct device * parent;
    struct device_private * p;
    const char * init_name;
    const struct device_type * type;
    struct bus_type * bus;
    struct device_driver * driver;
    void * platform_data;
    void * driver_data;
    struct mutex mutex;
    struct dev_links_info links;
    struct dev_pm_info power;
    struct dev_pm_domain * pm_domain;
    struct irq_domain * msi_domain;
    struct dev_pin_info * pins;
    struct list_head msi_list;
    const struct dma_map_ops * dma_ops;
    u64 * dma_mask;
    u64 coherent_dma_mask;
    u64 bus_dma_mask;
    long unsigned int dma_pfn_offset;
    struct device_dma_parameters * dma_parms;
    struct list_head dma_pools;
    struct dev_archdata archdata;
    struct device_node * of_node;
    struct fwnode_handle * fwnode;
    int numa_node;
    dev_t devt;
    u32 id;
    spinlock_t devres_lock;
    struct list_head devres_head;
    struct class * class;
    const struct attribute_group * * groups;
    void (*)(struct device *) release;
    struct iommu_group * iommu_group;
    struct iommu_fwspec * iommu_fwspec;
    struct iommu_param * iommu_param;
    bool offline_disabled;
    bool offline;
    bool of_node_reused;
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
<code>struct dev_links_info links</code>
</li>
<li>
<b>Field added. </b>
<code>struct iommu_fwspec * iommu_fwspec</code>
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
<code>const struct dma_map_ops * dma_ops</code>
</li>
<li>
<b>Field added. </b>
<code>bool of_node_reused</code>
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
<code>bool dma_32bit_limit</code>
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
<code>u64 bus_dma_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>bool dma_32bit_limit</code>
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
<code>struct iommu_param * iommu_param</code>
</li>
<li>
<b>Field removed. </b>
<code>struct klist_node knode_class</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct dma_coherent_mem * dma_mem</code> ➡️ <code>struct dma_coherent_mem * dma_mem</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct dma_coherent_mem * dma_mem</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 bus_dma_limit</code>
</li>
<li>
<b>Field added. </b>
<code>struct dev_iommu * iommu</code>
</li>
<li>
<b>Field added. </b>
<code>bool state_synced</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 bus_dma_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>struct iommu_fwspec * iommu_fwspec</code>
</li>
<li>
<b>Field removed. </b>
<code>struct iommu_param * iommu_param</code>
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
<code>struct em_perf_domain * em_pd</code>
</li>
<li>
<b>Field added. </b>
<code>const struct bus_dma_region * dma_range_map</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int dma_pfn_offset</code>
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
<code>raw_spinlock_t msi_lock</code>
</li>
<li>
<b>Field added. </b>
<code>bool can_match</code>
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
<code>struct io_tlb_mem * dma_io_tlb_mem</code>
</li>
<li>
<b>Field added. </b>
<code>enum device_removable removable</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct dev_msi_info msi</code>
</li>
<li>
<b>Field added. </b>
<code>struct device_physical_location * physical_location</code>
</li>
<li>
<b>Field removed. </b>
<code>struct irq_domain * msi_domain</code>
</li>
<li>
<b>Field removed. </b>
<code>raw_spinlock_t msi_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head msi_list</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct bus_type * bus</code> ➡️ <code>const struct bus_type * bus</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct class * class</code> ➡️ <code>const struct class * class</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head dma_io_tlb_pools</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t dma_io_tlb_lock</code>
</li>
<li>
<b>Field added. </b>
<code>bool dma_uses_io_tlb</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct dma_coherent_mem * dma_mem</code>
</li>
<li>
<b>Field added. </b>
<code>struct cma * cma_area</code>
</li>
<li>
<b>Field added. </b>
<code>bool dma_coherent</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct dma_coherent_mem * dma_mem</code>
</li>
<li>
<b>Field added. </b>
<code>struct cma * cma_area</code>
</li>
<li>
<b>Field removed. </b>
<code>int numa_node</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct dma_coherent_mem * dma_mem</code>
</li>
<li>
<b>Field removed. </b>
<code>struct irq_domain * msi_domain</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct dma_coherent_mem * dma_mem</code>
</li>
<li>
<b>Field added. </b>
<code>struct cma * cma_area</code>
</li>
<li>
<b>Field removed. </b>
<code>int numa_node</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct iommu_param * iommu_param</code> ➡️ <code>struct iommu_param * iommu_param</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct cma * cma_area</code>
</li>
</ul>
</details>
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
