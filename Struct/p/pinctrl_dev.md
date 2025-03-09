# Struct: <code>pinctrl_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct radix_tree_root pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct radix_tree_root pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct radix_tree_root pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct radix_tree_root pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct radix_tree_root pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct radix_tree_root pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct xarray pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct xarray pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct xarray pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct xarray pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct xarray pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct xarray pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct xarray pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct xarray pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct xarray pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct xarray pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct xarray pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
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
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct xarray pin_desc_tree;
    struct xarray pin_group_tree;
    unsigned int num_groups;
    struct xarray pin_function_tree;
    unsigned int num_functions;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct xarray pin_desc_tree;
    struct xarray pin_group_tree;
    unsigned int num_groups;
    struct xarray pin_function_tree;
    unsigned int num_functions;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct xarray pin_desc_tree;
    struct xarray pin_group_tree;
    unsigned int num_groups;
    struct xarray pin_function_tree;
    unsigned int num_functions;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct xarray pin_desc_tree;
    struct xarray pin_group_tree;
    unsigned int num_groups;
    struct xarray pin_function_tree;
    unsigned int num_functions;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
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
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct xarray pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct xarray pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct xarray pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pinctrl_dev {
    struct list_head node;
    struct pinctrl_desc * desc;
    struct xarray pin_desc_tree;
    struct list_head gpio_ranges;
    struct device * dev;
    struct module * owner;
    void * driver_data;
    struct pinctrl * p;
    struct pinctrl_state * hog_default;
    struct pinctrl_state * hog_sleep;
    struct mutex mutex;
    struct dentry * device_root;
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct radix_tree_root pin_desc_tree</code> ➡️ <code>struct xarray pin_desc_tree</code>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct xarray pin_group_tree</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int num_groups</code>
</li>
<li>
<b>Field added. </b>
<code>struct xarray pin_function_tree</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int num_functions</code>
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
<code>struct xarray pin_group_tree</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int num_groups</code>
</li>
<li>
<b>Field added. </b>
<code>struct xarray pin_function_tree</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int num_functions</code>
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
<code>struct xarray pin_group_tree</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int num_groups</code>
</li>
<li>
<b>Field added. </b>
<code>struct xarray pin_function_tree</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int num_functions</code>
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
<code>struct xarray pin_group_tree</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int num_groups</code>
</li>
<li>
<b>Field added. </b>
<code>struct xarray pin_function_tree</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int num_functions</code>
</li>
</ul>
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
