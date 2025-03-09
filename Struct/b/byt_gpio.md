# Struct: <code>byt_gpio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct byt_gpio {
    struct gpio_chip chip;
    struct platform_device * pdev;
    raw_spinlock_t lock;
    void * reg_base;
    struct pinctrl_gpio_range * range;
    struct byt_gpio_pin_context * saved_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct byt_gpio {
    struct gpio_chip chip;
    struct platform_device * pdev;
    struct pinctrl_dev * pctl_dev;
    struct pinctrl_desc pctl_desc;
    raw_spinlock_t lock;
    const struct byt_pinctrl_soc_data * soc_data;
    struct byt_community * communities_copy;
    struct byt_gpio_pin_context * saved_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct byt_gpio {
    struct gpio_chip chip;
    struct platform_device * pdev;
    struct pinctrl_dev * pctl_dev;
    struct pinctrl_desc pctl_desc;
    raw_spinlock_t lock;
    const struct byt_pinctrl_soc_data * soc_data;
    struct byt_community * communities_copy;
    struct byt_gpio_pin_context * saved_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct byt_gpio {
    struct gpio_chip chip;
    struct platform_device * pdev;
    struct pinctrl_dev * pctl_dev;
    struct pinctrl_desc pctl_desc;
    raw_spinlock_t lock;
    const struct byt_pinctrl_soc_data * soc_data;
    struct byt_community * communities_copy;
    struct byt_gpio_pin_context * saved_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct byt_gpio {
    struct gpio_chip chip;
    struct platform_device * pdev;
    struct pinctrl_dev * pctl_dev;
    struct pinctrl_desc pctl_desc;
    raw_spinlock_t lock;
    const struct byt_pinctrl_soc_data * soc_data;
    struct byt_community * communities_copy;
    struct byt_gpio_pin_context * saved_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct byt_gpio {
    struct gpio_chip chip;
    struct platform_device * pdev;
    struct pinctrl_dev * pctl_dev;
    struct pinctrl_desc pctl_desc;
    raw_spinlock_t lock;
    const struct byt_pinctrl_soc_data * soc_data;
    struct byt_community * communities_copy;
    struct byt_gpio_pin_context * saved_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct byt_gpio {
    struct gpio_chip chip;
    struct platform_device * pdev;
    struct pinctrl_dev * pctl_dev;
    struct pinctrl_desc pctl_desc;
    raw_spinlock_t lock;
    const struct byt_pinctrl_soc_data * soc_data;
    struct byt_community * communities_copy;
    struct byt_gpio_pin_context * saved_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct byt_gpio {
    struct gpio_chip chip;
    struct platform_device * pdev;
    struct pinctrl_dev * pctl_dev;
    struct pinctrl_desc pctl_desc;
    raw_spinlock_t lock;
    const struct byt_pinctrl_soc_data * soc_data;
    struct byt_community * communities_copy;
    struct byt_gpio_pin_context * saved_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct byt_gpio {
    struct gpio_chip chip;
    struct platform_device * pdev;
    struct pinctrl_dev * pctl_dev;
    struct pinctrl_desc pctl_desc;
    const struct intel_pinctrl_soc_data * soc_data;
    struct intel_community * communities_copy;
    struct byt_gpio_pin_context * saved_context;
}
```
</details>
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct byt_gpio {
    struct gpio_chip chip;
    struct platform_device * pdev;
    struct pinctrl_dev * pctl_dev;
    struct pinctrl_desc pctl_desc;
    const struct intel_pinctrl_soc_data * soc_data;
    struct intel_community * communities_copy;
    struct byt_gpio_pin_context * saved_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct byt_gpio {
    struct gpio_chip chip;
    struct platform_device * pdev;
    struct pinctrl_dev * pctl_dev;
    struct pinctrl_desc pctl_desc;
    const struct intel_pinctrl_soc_data * soc_data;
    struct intel_community * communities_copy;
    struct byt_gpio_pin_context * saved_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct byt_gpio {
    struct gpio_chip chip;
    struct platform_device * pdev;
    struct pinctrl_dev * pctl_dev;
    struct pinctrl_desc pctl_desc;
    const struct intel_pinctrl_soc_data * soc_data;
    struct intel_community * communities_copy;
    struct byt_gpio_pin_context * saved_context;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct byt_gpio {
    struct gpio_chip chip;
    struct platform_device * pdev;
    struct pinctrl_dev * pctl_dev;
    struct pinctrl_desc pctl_desc;
    const struct intel_pinctrl_soc_data * soc_data;
    struct intel_community * communities_copy;
    struct byt_gpio_pin_context * saved_context;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct pinctrl_dev * pctl_dev</code>
</li>
<li>
<b>Field added. </b>
<code>struct pinctrl_desc pctl_desc</code>
</li>
<li>
<b>Field added. </b>
<code>const struct byt_pinctrl_soc_data * soc_data</code>
</li>
<li>
<b>Field added. </b>
<code>struct byt_community * communities_copy</code>
</li>
<li>
<b>Field removed. </b>
<code>void * reg_base</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pinctrl_gpio_range * range</code>
</li>
</ul>
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
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>raw_spinlock_t lock</code>
</li>
<li>
<b>Field type changed. </b>
<code>const struct byt_pinctrl_soc_data * soc_data</code> ➡️ <code>const struct intel_pinctrl_soc_data * soc_data</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct byt_community * communities_copy</code> ➡️ <code>struct intel_community * communities_copy</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct byt_gpio {
    struct gpio_chip chip;
    struct platform_device * pdev;
    struct pinctrl_dev * pctl_dev;
    struct pinctrl_desc pctl_desc;
    const struct intel_pinctrl_soc_data * soc_data;
    struct intel_community * communities_copy;
    struct byt_gpio_pin_context * saved_context;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct byt_gpio {
    struct gpio_chip chip;
    struct platform_device * pdev;
    struct pinctrl_dev * pctl_dev;
    struct pinctrl_desc pctl_desc;
    const struct intel_pinctrl_soc_data * soc_data;
    struct intel_community * communities_copy;
    struct byt_gpio_pin_context * saved_context;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct byt_gpio {
    struct gpio_chip chip;
    struct platform_device * pdev;
    struct pinctrl_dev * pctl_dev;
    struct pinctrl_desc pctl_desc;
    const struct intel_pinctrl_soc_data * soc_data;
    struct intel_community * communities_copy;
    struct byt_gpio_pin_context * saved_context;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct byt_gpio {
    struct gpio_chip chip;
    struct platform_device * pdev;
    struct pinctrl_dev * pctl_dev;
    struct pinctrl_desc pctl_desc;
    const struct intel_pinctrl_soc_data * soc_data;
    struct intel_community * communities_copy;
    struct byt_gpio_pin_context * saved_context;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct byt_gpio {
    struct gpio_chip chip;
    struct platform_device * pdev;
    struct pinctrl_dev * pctl_dev;
    struct pinctrl_desc pctl_desc;
    const struct intel_pinctrl_soc_data * soc_data;
    struct intel_community * communities_copy;
    struct byt_gpio_pin_context * saved_context;
}
```
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
