# Struct: <code>rockchip_pin_bank</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct rockchip_pin_bank {
    void * reg_base;
    struct regmap * regmap_pull;
    struct clk * clk;
    int irq;
    u32 saved_masks;
    u32 pin_base;
    u8 nr_pins;
    char * name;
    u8 bank_num;
    struct rockchip_iomux[4] iomux;
    struct rockchip_drv[4] drv;
    enum rockchip_pin_pull_type[4] pull_type;
    bool valid;
    struct device_node * of_node;
    struct rockchip_pinctrl * drvdata;
    struct irq_domain * domain;
    struct gpio_chip gpio_chip;
    struct pinctrl_gpio_range grange;
    raw_spinlock_t slock;
    u32 toggle_edge_mode;
    u32 recalced_mask;
    u32 route_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rockchip_pin_bank {
    void * reg_base;
    struct regmap * regmap_pull;
    struct clk * clk;
    int irq;
    u32 saved_masks;
    u32 pin_base;
    u8 nr_pins;
    char * name;
    u8 bank_num;
    struct rockchip_iomux[4] iomux;
    struct rockchip_drv[4] drv;
    enum rockchip_pin_pull_type[4] pull_type;
    bool valid;
    struct device_node * of_node;
    struct rockchip_pinctrl * drvdata;
    struct irq_domain * domain;
    struct gpio_chip gpio_chip;
    struct pinctrl_gpio_range grange;
    raw_spinlock_t slock;
    u32 toggle_edge_mode;
    u32 recalced_mask;
    u32 route_mask;
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct rockchip_pin_bank {
    void * reg_base;
    struct regmap * regmap_pull;
    struct clk * clk;
    int irq;
    u32 saved_masks;
    u32 pin_base;
    u8 nr_pins;
    char * name;
    u8 bank_num;
    struct rockchip_iomux[4] iomux;
    struct rockchip_drv[4] drv;
    enum rockchip_pin_pull_type[4] pull_type;
    bool valid;
    struct device_node * of_node;
    struct rockchip_pinctrl * drvdata;
    struct irq_domain * domain;
    struct gpio_chip gpio_chip;
    struct pinctrl_gpio_range grange;
    raw_spinlock_t slock;
    u32 toggle_edge_mode;
    u32 recalced_mask;
    u32 route_mask;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct rockchip_pin_bank {
    void * reg_base;
    struct regmap * regmap_pull;
    struct clk * clk;
    int irq;
    u32 saved_masks;
    u32 pin_base;
    u8 nr_pins;
    char * name;
    u8 bank_num;
    struct rockchip_iomux[4] iomux;
    struct rockchip_drv[4] drv;
    enum rockchip_pin_pull_type[4] pull_type;
    bool valid;
    struct device_node * of_node;
    struct rockchip_pinctrl * drvdata;
    struct irq_domain * domain;
    struct gpio_chip gpio_chip;
    struct pinctrl_gpio_range grange;
    raw_spinlock_t slock;
    u32 toggle_edge_mode;
    u32 recalced_mask;
    u32 route_mask;
}
```
</details>
</li>
</ul>
