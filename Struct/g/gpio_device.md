# Struct: <code>gpio_device</code>

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
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    char * label;
    void * data;
    struct list_head list;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    char * label;
    void * data;
    struct list_head list;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    char * label;
    void * data;
    struct list_head list;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    char * label;
    void * data;
    struct list_head list;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    const char * label;
    void * data;
    struct list_head list;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    const char * label;
    void * data;
    struct list_head list;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    const char * label;
    void * data;
    struct list_head list;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    const char * label;
    void * data;
    struct list_head list;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    const char * label;
    void * data;
    struct list_head list;
    struct atomic_notifier_head notifier;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    const char * label;
    void * data;
    struct list_head list;
    struct blocking_notifier_head notifier;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    const char * label;
    void * data;
    struct list_head list;
    struct blocking_notifier_head notifier;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    const char * label;
    void * data;
    struct list_head list;
    struct blocking_notifier_head notifier;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    const char * label;
    void * data;
    struct list_head list;
    struct blocking_notifier_head notifier;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct gpio_device {
    struct device dev;
    struct cdev chrdev;
    int id;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    const char * label;
    void * data;
    struct list_head list;
    struct blocking_notifier_head notifier;
    struct rw_semaphore sem;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct gpio_device {
    struct device dev;
    struct cdev chrdev;
    int id;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    const char * label;
    void * data;
    struct list_head list;
    struct blocking_notifier_head notifier;
    struct rw_semaphore sem;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct gpio_device {
    struct device dev;
    struct cdev chrdev;
    int id;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    const char * label;
    void * data;
    struct list_head list;
    struct blocking_notifier_head line_state_notifier;
    struct blocking_notifier_head device_notifier;
    struct rw_semaphore sem;
    struct list_head pin_ranges;
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
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    const char * label;
    void * data;
    struct list_head list;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    const char * label;
    void * data;
    struct list_head list;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    const char * label;
    void * data;
    struct list_head list;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    const char * label;
    void * data;
    struct list_head list;
    struct list_head pin_ranges;
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
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    const char * label;
    void * data;
    struct list_head list;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    const char * label;
    void * data;
    struct list_head list;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    const char * label;
    void * data;
    struct list_head list;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    const char * label;
    void * data;
    struct list_head list;
    struct list_head pin_ranges;
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
struct gpio_device {
    int id;
    struct device dev;
    struct cdev chrdev;
    struct device * mockdev;
    struct module * owner;
    struct gpio_chip * chip;
    struct gpio_desc * descs;
    int base;
    u16 ngpio;
    char * label;
    void * data;
    struct list_head list;
    struct list_head pin_ranges;
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
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>char * label</code> ➡️ <code>const char * label</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct atomic_notifier_head notifier</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct atomic_notifier_head notifier</code> ➡️ <code>struct blocking_notifier_head notifier</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct rw_semaphore sem</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct blocking_notifier_head line_state_notifier</code>
</li>
<li>
<b>Field added. </b>
<code>struct blocking_notifier_head device_notifier</code>
</li>
<li>
<b>Field removed. </b>
<code>struct blocking_notifier_head notifier</code>
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
