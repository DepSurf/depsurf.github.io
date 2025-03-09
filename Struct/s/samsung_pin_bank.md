# Struct: <code>samsung_pin_bank</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct samsung_pin_bank {
    const struct samsung_pin_bank_type * type;
    void * pctl_base;
    u32 pctl_offset;
    u8 nr_pins;
    void * eint_base;
    u8 eint_func;
    enum eint_type eint_type;
    u32 eint_mask;
    u32 eint_offset;
    const char * name;
    u32 pin_base;
    void * soc_priv;
    struct device_node * of_node;
    struct samsung_pinctrl_drv_data * drvdata;
    struct irq_domain * irq_domain;
    struct gpio_chip gpio_chip;
    struct pinctrl_gpio_range grange;
    struct exynos_irq_chip * irq_chip;
    spinlock_t slock;
    u32[7] pm_save;
}
```
</details>
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct samsung_pin_bank {
    const struct samsung_pin_bank_type * type;
    void * pctl_base;
    u32 pctl_offset;
    u8 nr_pins;
    void * eint_base;
    u8 eint_func;
    enum eint_type eint_type;
    u32 eint_mask;
    u32 eint_offset;
    const char * name;
    u32 pin_base;
    void * soc_priv;
    struct device_node * of_node;
    struct samsung_pinctrl_drv_data * drvdata;
    struct irq_domain * irq_domain;
    struct gpio_chip gpio_chip;
    struct pinctrl_gpio_range grange;
    struct exynos_irq_chip * irq_chip;
    spinlock_t slock;
    u32[7] pm_save;
}
```
</details>
</li>
</ul>
