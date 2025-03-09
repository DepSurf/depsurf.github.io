# Struct: <code>arizona</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    struct clk *[2] mclk;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    struct clk *[2] mclk;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    struct clk *[2] mclk;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    struct clk *[2] mclk;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    struct clk *[2] mclk;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    struct clk *[2] mclk;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    struct clk *[2] mclk;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    struct clk *[2] mclk;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    struct clk *[2] mclk;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    struct clk *[2] mclk;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
    struct blocking_notifier_head notifier;
}
```
</details>
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
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    struct clk *[2] mclk;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    struct clk *[2] mclk;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    struct clk *[2] mclk;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    struct clk *[2] mclk;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
    struct blocking_notifier_head notifier;
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
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    struct clk *[2] mclk;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    struct clk *[2] mclk;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    struct clk *[2] mclk;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    struct clk *[2] mclk;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
    struct blocking_notifier_head notifier;
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
<code>struct blocking_notifier_head notifier</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct clk *[2] mclk</code>
</li>
</ul>
</details>
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
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
struct arizona {
    struct regmap * regmap;
    struct device * dev;
    enum arizona_type type;
    unsigned int rev;
    int num_core_supplies;
    struct regulator_bulk_data[2] core_supplies;
    struct regulator * dcvdd;
    bool has_fully_powered_off;
    struct arizona_pdata pdata;
    unsigned int external_dcvdd;
    int irq;
    struct irq_domain * virq;
    struct regmap_irq_chip_data * aod_irq_chip;
    struct regmap_irq_chip_data * irq_chip;
    bool hpdet_clamp;
    unsigned int hp_ena;
    struct mutex clk_lock;
    int clk32k_ref;
    struct clk *[2] mclk;
    bool ctrlif_error;
    struct snd_soc_dapm_context * dapm;
    int[3] tdm_width;
    int[3] tdm_slots;
    uint16_t dac_comp_coeff;
    uint8_t dac_comp_enabled;
    struct mutex dac_comp_lock;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct snd_soc_dapm_context * dapm</code> ➡️ <code>struct snd_soc_dapm_context * dapm</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct clk *[2] mclk</code> ➡️ <code>struct clk *[2] mclk</code>
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
