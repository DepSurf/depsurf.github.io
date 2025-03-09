# Struct: <code>sec_platform_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
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
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
}
```
</details>
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
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
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
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct sec_platform_data {
    struct sec_regulator_data * regulators;
    struct sec_opmode_data * opmode;
    int device_type;
    int num_regulators;
    int irq_base;
    int (*)() cfg_pmic_irq;
    bool wakeup;
    bool buck_voltage_lock;
    int[3] buck_gpios;
    int[3] buck_ds;
    unsigned int[8] buck2_voltage;
    bool buck2_gpiodvs;
    unsigned int[8] buck3_voltage;
    bool buck3_gpiodvs;
    unsigned int[8] buck4_voltage;
    bool buck4_gpiodvs;
    int buck_set1;
    int buck_set2;
    int buck_set3;
    int buck2_enable;
    int buck3_enable;
    int buck4_enable;
    int buck_default_idx;
    int buck2_default_idx;
    int buck3_default_idx;
    int buck4_default_idx;
    int buck_ramp_delay;
    int buck2_ramp_delay;
    int buck34_ramp_delay;
    int buck5_ramp_delay;
    int buck16_ramp_delay;
    int buck7810_ramp_delay;
    int buck9_ramp_delay;
    int buck24_ramp_delay;
    int buck3_ramp_delay;
    int buck7_ramp_delay;
    int buck8910_ramp_delay;
    bool buck1_ramp_enable;
    bool buck2_ramp_enable;
    bool buck3_ramp_enable;
    bool buck4_ramp_enable;
    bool buck6_ramp_enable;
    int buck2_init;
    int buck3_init;
    int buck4_init;
    bool manual_poweroff;
    bool disable_wrstbi;
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
