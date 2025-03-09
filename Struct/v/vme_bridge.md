# Struct: <code>vme_bridge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(int)) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(int)) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
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
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
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
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct vme_bridge {
    char[16] name;
    int num;
    struct list_head master_resources;
    struct list_head slave_resources;
    struct list_head dma_resources;
    struct list_head lm_resources;
    struct list_head vme_error_handlers;
    struct list_head devices;
    struct device * parent;
    void * driver_priv;
    struct list_head bus_list;
    struct vme_irq[7] irq;
    struct mutex irq_mtx;
    int (*)(struct vme_slave_resource *, int *, long long unsigned int *, long long unsigned int *, dma_addr_t *, u32 *, u32 *) slave_get;
    int (*)(struct vme_slave_resource *, int, long long unsigned int, long long unsigned int, dma_addr_t, u32, u32) slave_set;
    int (*)(struct vme_master_resource *, int *, long long unsigned int *, long long unsigned int *, u32 *, u32 *, u32 *) master_get;
    int (*)(struct vme_master_resource *, int, long long unsigned int, long long unsigned int, u32, u32, u32) master_set;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_read;
    ssize_t (*)(struct vme_master_resource *, void *, size_t, loff_t) master_write;
    unsigned int (*)(struct vme_master_resource *, unsigned int, unsigned int, unsigned int, loff_t) master_rmw;
    int (*)(struct vme_dma_list *, struct vme_dma_attr *, struct vme_dma_attr *, size_t) dma_list_add;
    int (*)(struct vme_dma_list *) dma_list_exec;
    int (*)(struct vme_dma_list *) dma_list_empty;
    void (*)(struct vme_bridge *, int, int, int) irq_set;
    int (*)(struct vme_bridge *, int, int) irq_generate;
    int (*)(struct vme_lm_resource *, long long unsigned int, u32, u32) lm_set;
    int (*)(struct vme_lm_resource *, long long unsigned int *, u32 *, u32 *) lm_get;
    int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach;
    int (*)(struct vme_lm_resource *, int) lm_detach;
    int (*)(struct vme_bridge *) slot_get;
    void * (*)(struct device *, size_t, dma_addr_t *) alloc_consistent;
    void (*)(struct device *, size_t, void *, dma_addr_t) free_consistent;
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
<b>Field type changed. </b>
<code>int (*)(struct vme_lm_resource *, int, void (*)(int)) lm_attach</code> ➡️ <code>int (*)(struct vme_lm_resource *, int, void (*)(void *), void *) lm_attach</code>
</li>
</ul>
</details>
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
