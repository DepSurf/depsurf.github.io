# Struct: <code>intel_soc_pmic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_level2;
    struct device * dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_level2;
    struct device * dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_level2;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct device * dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_pwrbtn;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_pwrbtn;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_pwrbtn;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_pwrbtn;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
    struct intel_scu_ipc_dev * scu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_pwrbtn;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
    struct intel_scu_ipc_dev * scu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_pwrbtn;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
    struct intel_scu_ipc_dev * scu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_pwrbtn;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
    struct intel_scu_ipc_dev * scu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_pwrbtn;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
    struct intel_scu_ipc_dev * scu;
    enum intel_cht_wc_models cht_wc_model;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_pwrbtn;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
    struct intel_scu_ipc_dev * scu;
    enum intel_cht_wc_models cht_wc_model;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_pwrbtn;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
    struct intel_scu_ipc_dev * scu;
    enum intel_cht_wc_models cht_wc_model;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_pwrbtn;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
    struct intel_scu_ipc_dev * scu;
    enum intel_cht_wc_models cht_wc_model;
}
```
</details>
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_pwrbtn;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_pwrbtn;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct regmap_irq_chip_data * irq_chip_data_tmu</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct regmap_irq_chip_data * irq_chip_data_bcu</code>
</li>
<li>
<b>Field added. </b>
<code>struct regmap_irq_chip_data * irq_chip_data_adc</code>
</li>
<li>
<b>Field added. </b>
<code>struct regmap_irq_chip_data * irq_chip_data_chgr</code>
</li>
<li>
<b>Field added. </b>
<code>struct regmap_irq_chip_data * irq_chip_data_crit</code>
</li>
<li>
<b>Field removed. </b>
<code>struct regmap_irq_chip_data * irq_chip_data_level2</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>struct regmap_irq_chip_data * irq_chip_data_pwrbtn</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct intel_scu_ipc_dev * scu</code>
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
<code>enum intel_cht_wc_models cht_wc_model</code>
</li>
</ul>
</details>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_pwrbtn;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_pwrbtn;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_pwrbtn;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_pwrbtn;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_pwrbtn;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct intel_soc_pmic {
    int irq;
    struct regmap * regmap;
    struct regmap_irq_chip_data * irq_chip_data;
    struct regmap_irq_chip_data * irq_chip_data_pwrbtn;
    struct regmap_irq_chip_data * irq_chip_data_tmu;
    struct regmap_irq_chip_data * irq_chip_data_bcu;
    struct regmap_irq_chip_data * irq_chip_data_adc;
    struct regmap_irq_chip_data * irq_chip_data_chgr;
    struct regmap_irq_chip_data * irq_chip_data_crit;
    struct device * dev;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
