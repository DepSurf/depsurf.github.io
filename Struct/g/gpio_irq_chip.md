# Struct: <code>gpio_irq_chip</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    const struct irq_domain_ops * domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    bool need_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    const struct irq_domain_ops * domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    bool need_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    const struct irq_domain_ops * domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    unsigned int num_parents;
    unsigned int parent_irq;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    bool need_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    const struct irq_domain_ops * domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    bool need_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    const struct irq_domain_ops * domain_ops;
    struct fwnode_handle * fwnode;
    struct irq_domain * parent_domain;
    int (*)(struct gpio_chip *, unsigned int, unsigned int, unsigned int *, unsigned int *) child_to_parent_hwirq;
    void (*)(struct gpio_chip *, struct irq_fwspec *, unsigned int, unsigned int) populate_parent_fwspec;
    unsigned int (*)(struct gpio_chip *, unsigned int) child_offset_to_irq;
    struct irq_domain_ops child_irq_domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    int (*)(struct gpio_chip *) init_hw;
    void (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    const struct irq_domain_ops * domain_ops;
    struct fwnode_handle * fwnode;
    struct irq_domain * parent_domain;
    int (*)(struct gpio_chip *, unsigned int, unsigned int, unsigned int *, unsigned int *) child_to_parent_hwirq;
    void * (*)(struct gpio_chip *, unsigned int, unsigned int) populate_parent_alloc_arg;
    unsigned int (*)(struct gpio_chip *, unsigned int) child_offset_to_irq;
    struct irq_domain_ops child_irq_domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    int (*)(struct gpio_chip *) init_hw;
    void (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    const struct irq_domain_ops * domain_ops;
    struct fwnode_handle * fwnode;
    struct irq_domain * parent_domain;
    int (*)(struct gpio_chip *, unsigned int, unsigned int, unsigned int *, unsigned int *) child_to_parent_hwirq;
    void * (*)(struct gpio_chip *, unsigned int, unsigned int) populate_parent_alloc_arg;
    unsigned int (*)(struct gpio_chip *, unsigned int) child_offset_to_irq;
    struct irq_domain_ops child_irq_domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    int (*)(struct gpio_chip *) init_hw;
    void (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    const struct irq_domain_ops * domain_ops;
    struct fwnode_handle * fwnode;
    struct irq_domain * parent_domain;
    int (*)(struct gpio_chip *, unsigned int, unsigned int, unsigned int *, unsigned int *) child_to_parent_hwirq;
    void * (*)(struct gpio_chip *, unsigned int, unsigned int) populate_parent_alloc_arg;
    unsigned int (*)(struct gpio_chip *, unsigned int) child_offset_to_irq;
    struct irq_domain_ops child_irq_domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    int (*)(struct gpio_chip *) init_hw;
    void (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    const struct irq_domain_ops * domain_ops;
    struct fwnode_handle * fwnode;
    struct irq_domain * parent_domain;
    int (*)(struct gpio_chip *, unsigned int, unsigned int, unsigned int *, unsigned int *) child_to_parent_hwirq;
    void * (*)(struct gpio_chip *, unsigned int, unsigned int) populate_parent_alloc_arg;
    unsigned int (*)(struct gpio_chip *, unsigned int) child_offset_to_irq;
    struct irq_domain_ops child_irq_domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    int (*)(struct gpio_chip *) init_hw;
    void (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    const struct irq_domain_ops * domain_ops;
    struct fwnode_handle * fwnode;
    struct irq_domain * parent_domain;
    int (*)(struct gpio_chip *, unsigned int, unsigned int, unsigned int *, unsigned int *) child_to_parent_hwirq;
    void * (*)(struct gpio_chip *, unsigned int, unsigned int) populate_parent_alloc_arg;
    unsigned int (*)(struct gpio_chip *, unsigned int) child_offset_to_irq;
    struct irq_domain_ops child_irq_domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    void * * parent_handler_data_array;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    bool per_parent_data;
    bool initialized;
    int (*)(struct gpio_chip *) init_hw;
    void (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    const struct irq_domain_ops * domain_ops;
    struct fwnode_handle * fwnode;
    struct irq_domain * parent_domain;
    int (*)(struct gpio_chip *, unsigned int, unsigned int, unsigned int *, unsigned int *) child_to_parent_hwirq;
    int (*)(struct gpio_chip *, union gpio_irq_fwspec *, unsigned int, unsigned int) populate_parent_alloc_arg;
    unsigned int (*)(struct gpio_chip *, unsigned int) child_offset_to_irq;
    struct irq_domain_ops child_irq_domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    void * * parent_handler_data_array;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    bool per_parent_data;
    bool initialized;
    int (*)(struct gpio_chip *) init_hw;
    void (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    struct fwnode_handle * fwnode;
    struct irq_domain * parent_domain;
    int (*)(struct gpio_chip *, unsigned int, unsigned int, unsigned int *, unsigned int *) child_to_parent_hwirq;
    int (*)(struct gpio_chip *, union gpio_irq_fwspec *, unsigned int, unsigned int) populate_parent_alloc_arg;
    unsigned int (*)(struct gpio_chip *, unsigned int) child_offset_to_irq;
    struct irq_domain_ops child_irq_domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    void * * parent_handler_data_array;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    bool per_parent_data;
    bool initialized;
    bool domain_is_allocated_externally;
    int (*)(struct gpio_chip *) init_hw;
    void (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    struct fwnode_handle * fwnode;
    struct irq_domain * parent_domain;
    int (*)(struct gpio_chip *, unsigned int, unsigned int, unsigned int *, unsigned int *) child_to_parent_hwirq;
    int (*)(struct gpio_chip *, union gpio_irq_fwspec *, unsigned int, unsigned int) populate_parent_alloc_arg;
    unsigned int (*)(struct gpio_chip *, unsigned int) child_offset_to_irq;
    struct irq_domain_ops child_irq_domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    void * * parent_handler_data_array;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    bool per_parent_data;
    bool initialized;
    bool domain_is_allocated_externally;
    int (*)(struct gpio_chip *) init_hw;
    void (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
    void (*)(struct irq_data *) irq_unmask;
    void (*)(struct irq_data *) irq_mask;
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
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    const struct irq_domain_ops * domain_ops;
    struct fwnode_handle * fwnode;
    struct irq_domain * parent_domain;
    int (*)(struct gpio_chip *, unsigned int, unsigned int, unsigned int *, unsigned int *) child_to_parent_hwirq;
    void (*)(struct gpio_chip *, struct irq_fwspec *, unsigned int, unsigned int) populate_parent_fwspec;
    unsigned int (*)(struct gpio_chip *, unsigned int) child_offset_to_irq;
    struct irq_domain_ops child_irq_domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    int (*)(struct gpio_chip *) init_hw;
    void (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    const struct irq_domain_ops * domain_ops;
    struct fwnode_handle * fwnode;
    struct irq_domain * parent_domain;
    int (*)(struct gpio_chip *, unsigned int, unsigned int, unsigned int *, unsigned int *) child_to_parent_hwirq;
    void (*)(struct gpio_chip *, struct irq_fwspec *, unsigned int, unsigned int) populate_parent_fwspec;
    unsigned int (*)(struct gpio_chip *, unsigned int) child_offset_to_irq;
    struct irq_domain_ops child_irq_domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    int (*)(struct gpio_chip *) init_hw;
    void (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    const struct irq_domain_ops * domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    int (*)(struct gpio_chip *) init_hw;
    void (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    const struct irq_domain_ops * domain_ops;
    struct fwnode_handle * fwnode;
    struct irq_domain * parent_domain;
    int (*)(struct gpio_chip *, unsigned int, unsigned int, unsigned int *, unsigned int *) child_to_parent_hwirq;
    void (*)(struct gpio_chip *, struct irq_fwspec *, unsigned int, unsigned int) populate_parent_fwspec;
    unsigned int (*)(struct gpio_chip *, unsigned int) child_offset_to_irq;
    struct irq_domain_ops child_irq_domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    int (*)(struct gpio_chip *) init_hw;
    void (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
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
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    const struct irq_domain_ops * domain_ops;
    struct fwnode_handle * fwnode;
    struct irq_domain * parent_domain;
    int (*)(struct gpio_chip *, unsigned int, unsigned int, unsigned int *, unsigned int *) child_to_parent_hwirq;
    void (*)(struct gpio_chip *, struct irq_fwspec *, unsigned int, unsigned int) populate_parent_fwspec;
    unsigned int (*)(struct gpio_chip *, unsigned int) child_offset_to_irq;
    struct irq_domain_ops child_irq_domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    int (*)(struct gpio_chip *) init_hw;
    void (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    const struct irq_domain_ops * domain_ops;
    struct fwnode_handle * fwnode;
    struct irq_domain * parent_domain;
    int (*)(struct gpio_chip *, unsigned int, unsigned int, unsigned int *, unsigned int *) child_to_parent_hwirq;
    void (*)(struct gpio_chip *, struct irq_fwspec *, unsigned int, unsigned int) populate_parent_fwspec;
    unsigned int (*)(struct gpio_chip *, unsigned int) child_offset_to_irq;
    struct irq_domain_ops child_irq_domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    int (*)(struct gpio_chip *) init_hw;
    void (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    const struct irq_domain_ops * domain_ops;
    struct fwnode_handle * fwnode;
    struct irq_domain * parent_domain;
    int (*)(struct gpio_chip *, unsigned int, unsigned int, unsigned int *, unsigned int *) child_to_parent_hwirq;
    void (*)(struct gpio_chip *, struct irq_fwspec *, unsigned int, unsigned int) populate_parent_fwspec;
    unsigned int (*)(struct gpio_chip *, unsigned int) child_offset_to_irq;
    struct irq_domain_ops child_irq_domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    int (*)(struct gpio_chip *) init_hw;
    void (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    const struct irq_domain_ops * domain_ops;
    struct fwnode_handle * fwnode;
    struct irq_domain * parent_domain;
    int (*)(struct gpio_chip *, unsigned int, unsigned int, unsigned int *, unsigned int *) child_to_parent_hwirq;
    void (*)(struct gpio_chip *, struct irq_fwspec *, unsigned int, unsigned int) populate_parent_fwspec;
    unsigned int (*)(struct gpio_chip *, unsigned int) child_offset_to_irq;
    struct irq_domain_ops child_irq_domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    int (*)(struct gpio_chip *) init_hw;
    void (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
    void (*)(struct irq_data *) irq_enable;
    void (*)(struct irq_data *) irq_disable;
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct gpio_irq_chip {
    struct irq_chip * chip;
    struct irq_domain * domain;
    const struct irq_domain_ops * domain_ops;
    irq_flow_handler_t handler;
    unsigned int default_type;
    struct lock_class_key * lock_key;
    struct lock_class_key * request_key;
    irq_flow_handler_t parent_handler;
    void * parent_handler_data;
    unsigned int num_parents;
    unsigned int * parents;
    unsigned int * map;
    bool threaded;
    bool need_valid_mask;
    long unsigned int * valid_mask;
    unsigned int first;
}
```
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
<b>Field added. </b>
<code>unsigned int parent_irq</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct irq_data *) irq_enable</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct irq_data *) irq_disable</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int parent_irq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct fwnode_handle * fwnode</code>
</li>
<li>
<b>Field added. </b>
<code>struct irq_domain * parent_domain</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct gpio_chip *, unsigned int, unsigned int, unsigned int *, unsigned int *) child_to_parent_hwirq</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct gpio_chip *, struct irq_fwspec *, unsigned int, unsigned int) populate_parent_fwspec</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int (*)(struct gpio_chip *, unsigned int) child_offset_to_irq</code>
</li>
<li>
<b>Field added. </b>
<code>struct irq_domain_ops child_irq_domain_ops</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct gpio_chip *) init_hw</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>bool need_valid_mask</code>
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
<code>void * (*)(struct gpio_chip *, unsigned int, unsigned int) populate_parent_alloc_arg</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct irq_data *) irq_unmask</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct irq_data *) irq_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct gpio_chip *, struct irq_fwspec *, unsigned int, unsigned int) populate_parent_fwspec</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * * parent_handler_data_array</code>
</li>
<li>
<b>Field added. </b>
<code>bool per_parent_data</code>
</li>
<li>
<b>Field added. </b>
<code>bool initialized</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void * (*)(struct gpio_chip *, unsigned int, unsigned int) populate_parent_alloc_arg</code> ➡️ <code>int (*)(struct gpio_chip *, union gpio_irq_fwspec *, unsigned int, unsigned int) populate_parent_alloc_arg</code>
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
<code>bool domain_is_allocated_externally</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct irq_domain_ops * domain_ops</code>
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
<code>struct fwnode_handle * fwnode</code>
</li>
<li>
<b>Field removed. </b>
<code>struct irq_domain * parent_domain</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct gpio_chip *, unsigned int, unsigned int, unsigned int *, unsigned int *) child_to_parent_hwirq</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct gpio_chip *, struct irq_fwspec *, unsigned int, unsigned int) populate_parent_fwspec</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int (*)(struct gpio_chip *, unsigned int) child_offset_to_irq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct irq_domain_ops child_irq_domain_ops</code>
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
