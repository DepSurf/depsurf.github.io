# Struct: <code>dev_dax</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dev_dax {
    struct dax_region * region;
    struct dax_device * dax_dev;
    int target_node;
    struct device dev;
    struct dev_pagemap pgmap;
    struct resource * dax_kmem_res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dev_dax {
    struct dax_region * region;
    struct dax_device * dax_dev;
    int target_node;
    struct device dev;
    struct dev_pagemap pgmap;
    struct resource * dax_kmem_res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dev_dax {
    struct dax_region * region;
    struct dax_device * dax_dev;
    int target_node;
    struct device dev;
    struct dev_pagemap pgmap;
    struct resource * dax_kmem_res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dev_dax {
    struct dax_region * region;
    struct dax_device * dax_dev;
    unsigned int align;
    int target_node;
    int id;
    struct ida ida;
    struct device dev;
    struct dev_pagemap * pgmap;
    int nr_range;
    struct dev_dax_range * ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dev_dax {
    struct dax_region * region;
    struct dax_device * dax_dev;
    unsigned int align;
    int target_node;
    int id;
    struct ida ida;
    struct device dev;
    struct dev_pagemap * pgmap;
    int nr_range;
    struct dev_dax_range * ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dev_dax {
    struct dax_region * region;
    struct dax_device * dax_dev;
    unsigned int align;
    int target_node;
    int id;
    struct ida ida;
    struct device dev;
    struct dev_pagemap * pgmap;
    int nr_range;
    struct dev_dax_range * ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dev_dax {
    struct dax_region * region;
    struct dax_device * dax_dev;
    unsigned int align;
    int target_node;
    int id;
    struct ida ida;
    struct device dev;
    struct dev_pagemap * pgmap;
    int nr_range;
    struct dev_dax_range * ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dev_dax {
    struct dax_region * region;
    struct dax_device * dax_dev;
    unsigned int align;
    int target_node;
    int id;
    struct ida ida;
    struct device dev;
    struct dev_pagemap * pgmap;
    int nr_range;
    struct dev_dax_range * ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dev_dax {
    struct dax_region * region;
    struct dax_device * dax_dev;
    unsigned int align;
    int target_node;
    bool dyn_id;
    int id;
    struct ida ida;
    struct device dev;
    struct dev_pagemap * pgmap;
    int nr_range;
    struct dev_dax_range * ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dev_dax {
    struct dax_region * region;
    struct dax_device * dax_dev;
    unsigned int align;
    int target_node;
    bool dyn_id;
    int id;
    struct ida ida;
    struct device dev;
    struct dev_pagemap * pgmap;
    bool memmap_on_memory;
    int nr_range;
    struct dev_dax_range * ranges;
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
struct dev_dax {
    struct dax_region * region;
    struct dax_device * dax_dev;
    int target_node;
    struct device dev;
    struct dev_pagemap pgmap;
    struct resource * dax_kmem_res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dev_dax {
    struct dax_region * region;
    struct dax_device * dax_dev;
    int target_node;
    struct device dev;
    struct dev_pagemap pgmap;
    struct resource * dax_kmem_res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dev_dax {
    struct dax_region * region;
    struct dax_device * dax_dev;
    int target_node;
    struct device dev;
    struct dev_pagemap pgmap;
    struct resource * dax_kmem_res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dev_dax {
    struct dax_region * region;
    struct dax_device * dax_dev;
    int target_node;
    struct device dev;
    struct dev_pagemap pgmap;
    struct resource * dax_kmem_res;
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
struct dev_dax {
    struct dax_region * region;
    struct dax_device * dax_dev;
    int target_node;
    struct device dev;
    struct dev_pagemap pgmap;
    struct resource * dax_kmem_res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dev_dax {
    struct dax_region * region;
    struct dax_device * dax_dev;
    int target_node;
    struct device dev;
    struct dev_pagemap pgmap;
    struct resource * dax_kmem_res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dev_dax {
    struct dax_region * region;
    struct dax_device * dax_dev;
    int target_node;
    struct device dev;
    struct dev_pagemap pgmap;
    struct resource * dax_kmem_res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dev_dax {
    struct dax_region * region;
    struct dax_device * dax_dev;
    int target_node;
    struct device dev;
    struct dev_pagemap pgmap;
    struct resource * dax_kmem_res;
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct dev_dax {
    struct dax_region * region;
    struct dax_device * dax_dev;
    int target_node;
    struct device dev;
    struct dev_pagemap pgmap;
    struct resource * dax_kmem_res;
}
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int align</code>
</li>
<li>
<b>Field added. </b>
<code>int id</code>
</li>
<li>
<b>Field added. </b>
<code>struct ida ida</code>
</li>
<li>
<b>Field added. </b>
<code>int nr_range</code>
</li>
<li>
<b>Field added. </b>
<code>struct dev_dax_range * ranges</code>
</li>
<li>
<b>Field removed. </b>
<code>struct resource * dax_kmem_res</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct dev_pagemap pgmap</code> ➡️ <code>struct dev_pagemap * pgmap</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool dyn_id</code>
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
<code>bool memmap_on_memory</code>
</li>
</ul>
</details>
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
