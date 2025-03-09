# Struct: <code>wm831x_pdata</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
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
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
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
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct wm831x_pdata {
    int wm831x_num;
    int (*)(struct wm831x *) pre_init;
    int (*)(struct wm831x *) post_init;
    bool irq_cmos;
    bool disable_touch;
    bool soft_shutdown;
    int irq_base;
    int gpio_base;
    int[16] gpio_defaults;
    struct wm831x_backlight_pdata * backlight;
    struct wm831x_backup_pdata * backup;
    struct wm831x_battery_pdata * battery;
    struct wm831x_touch_pdata * touch;
    struct wm831x_watchdog_pdata * watchdog;
    struct wm831x_status_pdata *[2] status;
    struct regulator_init_data *[4] dcdc;
    struct regulator_init_data *[2] epe;
    struct regulator_init_data *[11] ldo;
    struct regulator_init_data *[2] isink;
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
