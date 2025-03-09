# Struct: <code>lp8788_platform_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_ldo_enable_pin *[6] ldo_pin;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_ldo_enable_pin *[6] ldo_pin;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_ldo_enable_pin *[6] ldo_pin;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_ldo_enable_pin *[6] ldo_pin;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_ldo_enable_pin *[6] ldo_pin;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
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
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
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
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct lp8788_ldo_enable_pin *[6] ldo_pin</code>
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
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct lp8788_platform_data {
    int (*)(struct lp8788 *) init_func;
    struct regulator_init_data *[4] buck_data;
    struct regulator_init_data *[12] dldo_data;
    struct regulator_init_data *[10] aldo_data;
    struct lp8788_buck1_dvs * buck1_dvs;
    struct lp8788_buck2_dvs * buck2_dvs;
    struct lp8788_charger_platform_data * chg_pdata;
    enum lp8788_alarm_sel alarm_sel;
    struct lp8788_backlight_platform_data * bl_pdata;
    struct lp8788_led_platform_data * led_pdata;
    struct lp8788_vib_platform_data * vib_pdata;
    struct iio_map * adc_pdata;
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
