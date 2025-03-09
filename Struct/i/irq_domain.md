# Struct: <code>irq_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_direct_max_irq;
    unsigned int revmap_size;
    struct radix_tree_root revmap_tree;
    unsigned int[0] linear_revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_direct_max_irq;
    unsigned int revmap_size;
    struct radix_tree_root revmap_tree;
    unsigned int[0] linear_revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_direct_max_irq;
    unsigned int revmap_size;
    struct radix_tree_root revmap_tree;
    unsigned int[0] linear_revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_direct_max_irq;
    unsigned int revmap_size;
    struct radix_tree_root revmap_tree;
    unsigned int[0] linear_revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_direct_max_irq;
    unsigned int revmap_size;
    struct radix_tree_root revmap_tree;
    struct mutex revmap_tree_mutex;
    unsigned int[0] linear_revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_direct_max_irq;
    unsigned int revmap_size;
    struct radix_tree_root revmap_tree;
    struct mutex revmap_tree_mutex;
    unsigned int[0] linear_revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_direct_max_irq;
    unsigned int revmap_size;
    struct xarray revmap_tree;
    struct mutex revmap_tree_mutex;
    unsigned int[0] linear_revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_direct_max_irq;
    unsigned int revmap_size;
    struct xarray revmap_tree;
    struct mutex revmap_tree_mutex;
    unsigned int[0] linear_revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_direct_max_irq;
    unsigned int revmap_size;
    struct xarray revmap_tree;
    struct mutex revmap_tree_mutex;
    unsigned int[0] linear_revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_direct_max_irq;
    unsigned int revmap_size;
    struct xarray revmap_tree;
    struct mutex revmap_tree_mutex;
    unsigned int[0] linear_revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_direct_max_irq;
    unsigned int revmap_size;
    struct xarray revmap_tree;
    struct mutex revmap_tree_mutex;
    unsigned int[0] linear_revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_direct_max_irq;
    unsigned int revmap_size;
    struct xarray revmap_tree;
    struct mutex revmap_tree_mutex;
    unsigned int[0] linear_revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_size;
    struct xarray revmap_tree;
    struct mutex revmap_mutex;
    struct irq_data *[0] revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct device * dev;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_size;
    struct xarray revmap_tree;
    struct mutex revmap_mutex;
    struct irq_data *[0] revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct device * dev;
    struct device * pm_dev;
    struct irq_domain * parent;
    const struct msi_parent_ops * msi_parent_ops;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_size;
    struct xarray revmap_tree;
    struct mutex revmap_mutex;
    struct irq_data *[0] revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct mutex mutex;
    struct irq_domain * root;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct device * dev;
    struct device * pm_dev;
    struct irq_domain * parent;
    const struct msi_parent_ops * msi_parent_ops;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_size;
    struct xarray revmap_tree;
    struct irq_data *[0] revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct mutex mutex;
    struct irq_domain * root;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct device * dev;
    struct device * pm_dev;
    struct irq_domain * parent;
    const struct msi_parent_ops * msi_parent_ops;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_size;
    struct xarray revmap_tree;
    struct irq_data *[0] revmap;
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
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_direct_max_irq;
    unsigned int revmap_size;
    struct xarray revmap_tree;
    struct mutex revmap_tree_mutex;
    unsigned int[0] linear_revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_direct_max_irq;
    unsigned int revmap_size;
    struct xarray revmap_tree;
    struct mutex revmap_tree_mutex;
    unsigned int[0] linear_revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_direct_max_irq;
    unsigned int revmap_size;
    struct xarray revmap_tree;
    struct mutex revmap_tree_mutex;
    unsigned int[0] linear_revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_direct_max_irq;
    unsigned int revmap_size;
    struct xarray revmap_tree;
    struct mutex revmap_tree_mutex;
    unsigned int[0] linear_revmap;
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
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_direct_max_irq;
    unsigned int revmap_size;
    struct xarray revmap_tree;
    struct mutex revmap_tree_mutex;
    unsigned int[0] linear_revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_direct_max_irq;
    unsigned int revmap_size;
    struct xarray revmap_tree;
    struct mutex revmap_tree_mutex;
    unsigned int[0] linear_revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_direct_max_irq;
    unsigned int revmap_size;
    struct xarray revmap_tree;
    struct mutex revmap_tree_mutex;
    unsigned int[0] linear_revmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct irq_domain {
    struct list_head link;
    const char * name;
    const struct irq_domain_ops * ops;
    void * host_data;
    unsigned int flags;
    unsigned int mapcount;
    struct fwnode_handle * fwnode;
    enum irq_domain_bus_token bus_token;
    struct irq_domain_chip_generic * gc;
    struct irq_domain * parent;
    irq_hw_number_t hwirq_max;
    unsigned int revmap_direct_max_irq;
    unsigned int revmap_size;
    struct xarray revmap_tree;
    struct mutex revmap_tree_mutex;
    unsigned int[0] linear_revmap;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int mapcount</code>
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
<code>struct mutex revmap_tree_mutex</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct radix_tree_root revmap_tree</code> ➡️ <code>struct xarray revmap_tree</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct mutex revmap_mutex</code>
</li>
<li>
<b>Field added. </b>
<code>struct irq_data *[0] revmap</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int revmap_direct_max_irq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex revmap_tree_mutex</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int[0] linear_revmap</code>
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
<code>struct device * dev</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct device * pm_dev</code>
</li>
<li>
<b>Field added. </b>
<code>const struct msi_parent_ops * msi_parent_ops</code>
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
<code>struct mutex mutex</code>
</li>
<li>
<b>Field added. </b>
<code>struct irq_domain * root</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex revmap_mutex</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct irq_domain * parent</code>
</li>
</ul>
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
