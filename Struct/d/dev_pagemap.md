# Struct: <code>dev_pagemap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dev_pagemap {
    struct vmem_altmap * altmap;
    const struct resource * res;
    struct percpu_ref * ref;
    struct device * dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dev_pagemap {
    struct vmem_altmap * altmap;
    const struct resource * res;
    struct percpu_ref * ref;
    struct device * dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dev_pagemap {
    struct vmem_altmap * altmap;
    const struct resource * res;
    struct percpu_ref * ref;
    struct device * dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dev_pagemap {
    dev_page_fault_t page_fault;
    dev_page_free_t page_free;
    struct vmem_altmap * altmap;
    const struct resource * res;
    struct percpu_ref * ref;
    struct device * dev;
    void * data;
    enum memory_type type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dev_pagemap {
    dev_page_fault_t page_fault;
    dev_page_free_t page_free;
    struct vmem_altmap altmap;
    bool altmap_valid;
    struct resource res;
    struct percpu_ref * ref;
    struct device * dev;
    void * data;
    enum memory_type type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dev_pagemap {
    dev_page_free_t page_free;
    struct vmem_altmap altmap;
    bool altmap_valid;
    struct resource res;
    struct percpu_ref * ref;
    void (*)(struct percpu_ref *) kill;
    struct device * dev;
    void * data;
    enum memory_type type;
    u64 pci_p2pdma_bus_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dev_pagemap {
    struct vmem_altmap altmap;
    struct resource res;
    struct percpu_ref * ref;
    struct percpu_ref internal_ref;
    struct completion done;
    struct device * dev;
    enum memory_type type;
    unsigned int flags;
    u64 pci_p2pdma_bus_offset;
    const struct dev_pagemap_ops * ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dev_pagemap {
    struct vmem_altmap altmap;
    struct resource res;
    struct percpu_ref * ref;
    struct percpu_ref internal_ref;
    struct completion done;
    enum memory_type type;
    unsigned int flags;
    const struct dev_pagemap_ops * ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dev_pagemap {
    struct vmem_altmap altmap;
    struct resource res;
    struct percpu_ref * ref;
    struct percpu_ref internal_ref;
    struct completion done;
    enum memory_type type;
    unsigned int flags;
    const struct dev_pagemap_ops * ops;
    void * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dev_pagemap {
    struct vmem_altmap altmap;
    struct percpu_ref * ref;
    struct percpu_ref internal_ref;
    struct completion done;
    enum memory_type type;
    unsigned int flags;
    const struct dev_pagemap_ops * ops;
    void * owner;
    int nr_range;
    struct range range;
    struct range[0] ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dev_pagemap {
    struct vmem_altmap altmap;
    struct percpu_ref * ref;
    struct percpu_ref internal_ref;
    struct completion done;
    enum memory_type type;
    unsigned int flags;
    const struct dev_pagemap_ops * ops;
    void * owner;
    int nr_range;
    struct range range;
    struct range[0] ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dev_pagemap {
    struct vmem_altmap altmap;
    struct percpu_ref * ref;
    struct percpu_ref internal_ref;
    struct completion done;
    enum memory_type type;
    unsigned int flags;
    const struct dev_pagemap_ops * ops;
    void * owner;
    int nr_range;
    struct range range;
    struct range[0] ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dev_pagemap {
    struct vmem_altmap altmap;
    struct percpu_ref ref;
    struct completion done;
    enum memory_type type;
    unsigned int flags;
    long unsigned int vmemmap_shift;
    const struct dev_pagemap_ops * ops;
    void * owner;
    int nr_range;
    struct range range;
    struct range[0] ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dev_pagemap {
    struct vmem_altmap altmap;
    struct percpu_ref ref;
    struct completion done;
    enum memory_type type;
    unsigned int flags;
    long unsigned int vmemmap_shift;
    const struct dev_pagemap_ops * ops;
    void * owner;
    int nr_range;
    struct range range;
    struct range[0] ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dev_pagemap {
    struct vmem_altmap altmap;
    struct percpu_ref ref;
    struct completion done;
    enum memory_type type;
    unsigned int flags;
    long unsigned int vmemmap_shift;
    const struct dev_pagemap_ops * ops;
    void * owner;
    int nr_range;
    struct range range;
    struct (anon) __empty_ranges;
    struct range[0] ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dev_pagemap {
    struct vmem_altmap altmap;
    struct percpu_ref ref;
    struct completion done;
    enum memory_type type;
    unsigned int flags;
    long unsigned int vmemmap_shift;
    const struct dev_pagemap_ops * ops;
    void * owner;
    int nr_range;
    struct range range;
    struct (anon) __empty_ranges;
    struct range[0] ranges;
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
struct dev_pagemap {
    struct vmem_altmap altmap;
    struct resource res;
    struct percpu_ref * ref;
    struct percpu_ref internal_ref;
    struct completion done;
    enum memory_type type;
    unsigned int flags;
    const struct dev_pagemap_ops * ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dev_pagemap {
    struct vmem_altmap altmap;
    struct resource res;
    struct percpu_ref * ref;
    struct percpu_ref internal_ref;
    struct completion done;
    enum memory_type type;
    unsigned int flags;
    const struct dev_pagemap_ops * ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dev_pagemap {
    struct vmem_altmap altmap;
    struct resource res;
    struct percpu_ref * ref;
    struct percpu_ref internal_ref;
    struct completion done;
    enum memory_type type;
    unsigned int flags;
    const struct dev_pagemap_ops * ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dev_pagemap {
    struct vmem_altmap altmap;
    struct resource res;
    struct percpu_ref * ref;
    struct percpu_ref internal_ref;
    struct completion done;
    enum memory_type type;
    unsigned int flags;
    const struct dev_pagemap_ops * ops;
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
struct dev_pagemap {
    struct vmem_altmap altmap;
    struct resource res;
    struct percpu_ref * ref;
    struct percpu_ref internal_ref;
    struct completion done;
    enum memory_type type;
    unsigned int flags;
    const struct dev_pagemap_ops * ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dev_pagemap {
    struct vmem_altmap altmap;
    struct resource res;
    struct percpu_ref * ref;
    struct percpu_ref internal_ref;
    struct completion done;
    enum memory_type type;
    unsigned int flags;
    const struct dev_pagemap_ops * ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dev_pagemap {
    struct vmem_altmap altmap;
    struct resource res;
    struct percpu_ref * ref;
    struct percpu_ref internal_ref;
    struct completion done;
    enum memory_type type;
    unsigned int flags;
    const struct dev_pagemap_ops * ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dev_pagemap {
    struct vmem_altmap altmap;
    struct resource res;
    struct percpu_ref * ref;
    struct percpu_ref internal_ref;
    struct completion done;
    enum memory_type type;
    unsigned int flags;
    const struct dev_pagemap_ops * ops;
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct dev_pagemap {
    struct vmem_altmap * altmap;
    const struct resource * res;
    struct percpu_ref * ref;
    struct device * dev;
}
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>dev_page_fault_t page_fault</code>
</li>
<li>
<b>Field added. </b>
<code>dev_page_free_t page_free</code>
</li>
<li>
<b>Field added. </b>
<code>void * data</code>
</li>
<li>
<b>Field added. </b>
<code>enum memory_type type</code>
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
<code>bool altmap_valid</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct vmem_altmap * altmap</code> ➡️ <code>struct vmem_altmap altmap</code>
</li>
<li>
<b>Field type changed. </b>
<code>const struct resource * res</code> ➡️ <code>struct resource res</code>
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
<code>void (*)(struct percpu_ref *) kill</code>
</li>
<li>
<b>Field added. </b>
<code>u64 pci_p2pdma_bus_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>dev_page_fault_t page_fault</code>
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
<code>struct percpu_ref internal_ref</code>
</li>
<li>
<b>Field added. </b>
<code>struct completion done</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Field added. </b>
<code>const struct dev_pagemap_ops * ops</code>
</li>
<li>
<b>Field removed. </b>
<code>dev_page_free_t page_free</code>
</li>
<li>
<b>Field removed. </b>
<code>bool altmap_valid</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct percpu_ref *) kill</code>
</li>
<li>
<b>Field removed. </b>
<code>void * data</code>
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
<code>struct device * dev</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 pci_p2pdma_bus_offset</code>
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
<code>void * owner</code>
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
<code>int nr_range</code>
</li>
<li>
<b>Field added. </b>
<code>struct range range</code>
</li>
<li>
<b>Field added. </b>
<code>struct range[0] ranges</code>
</li>
<li>
<b>Field removed. </b>
<code>struct resource res</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int vmemmap_shift</code>
</li>
<li>
<b>Field removed. </b>
<code>struct percpu_ref internal_ref</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct percpu_ref * ref</code> ➡️ <code>struct percpu_ref ref</code>
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
<b>Field added. </b>
<code>struct (anon) __empty_ranges</code>
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
