# Struct: <code>gpio_bank</code>

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
struct gpio_bank {
    void * base;
    const struct omap_gpio_reg_offs * regs;
    int irq;
    u32 non_wakeup_gpios;
    u32 enabled_non_wakeup_gpios;
    struct gpio_regs context;
    u32 saved_datain;
    u32 level_mask;
    u32 toggle_mask;
    raw_spinlock_t lock;
    raw_spinlock_t wa_lock;
    struct gpio_chip chip;
    struct clk * dbck;
    struct notifier_block nb;
    unsigned int is_suspended;
    u32 mod_usage;
    u32 irq_usage;
    u32 dbck_enable_mask;
    bool dbck_enabled;
    bool is_mpuio;
    bool dbck_flag;
    bool loses_context;
    bool context_valid;
    int stride;
    u32 width;
    int context_loss_count;
    void (*)(struct gpio_bank *, unsigned int, int) set_dataout;
    int (*)(struct device *) get_context_loss_count;
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
struct gpio_bank {
    void * base;
    const struct omap_gpio_reg_offs * regs;
    int irq;
    u32 non_wakeup_gpios;
    u32 enabled_non_wakeup_gpios;
    struct gpio_regs context;
    u32 saved_datain;
    u32 level_mask;
    u32 toggle_mask;
    raw_spinlock_t lock;
    raw_spinlock_t wa_lock;
    struct gpio_chip chip;
    struct clk * dbck;
    struct notifier_block nb;
    unsigned int is_suspended;
    u32 mod_usage;
    u32 irq_usage;
    u32 dbck_enable_mask;
    bool dbck_enabled;
    bool is_mpuio;
    bool dbck_flag;
    bool loses_context;
    bool context_valid;
    int stride;
    u32 width;
    int context_loss_count;
    void (*)(struct gpio_bank *, unsigned int, int) set_dataout;
    int (*)(struct device *) get_context_loss_count;
}
```
</details>
</li>
</ul>
