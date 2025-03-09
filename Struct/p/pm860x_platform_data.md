# Struct: <code>pm860x_platform_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
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
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
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
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
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
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct pm860x_platform_data {
    struct pm860x_backlight_pdata * backlight;
    struct pm860x_led_pdata * led;
    struct pm860x_rtc_pdata * rtc;
    struct pm860x_touch_pdata * touch;
    struct pm860x_power_pdata * power;
    struct regulator_init_data * buck1;
    struct regulator_init_data * buck2;
    struct regulator_init_data * buck3;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldo8;
    struct regulator_init_data * ldo9;
    struct regulator_init_data * ldo10;
    struct regulator_init_data * ldo12;
    struct regulator_init_data * ldo_vibrator;
    struct regulator_init_data * ldo14;
    struct charger_desc * chg_desc;
    int companion_addr;
    int i2c_port;
    int irq_mode;
    int irq_base;
    int num_leds;
    int num_backlights;
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
