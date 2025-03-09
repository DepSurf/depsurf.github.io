# Struct: <code>i2c_bus_recovery_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    int scl_gpio;
    int sda_gpio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    int scl_gpio;
    int sda_gpio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    int scl_gpio;
    int sda_gpio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    int scl_gpio;
    int sda_gpio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    int scl_gpio;
    int sda_gpio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *, int) set_sda;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    struct gpio_desc * scl_gpiod;
    struct gpio_desc * sda_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *, int) set_sda;
    int (*)(struct i2c_adapter *) get_bus_free;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    struct gpio_desc * scl_gpiod;
    struct gpio_desc * sda_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *, int) set_sda;
    int (*)(struct i2c_adapter *) get_bus_free;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    struct gpio_desc * scl_gpiod;
    struct gpio_desc * sda_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *, int) set_sda;
    int (*)(struct i2c_adapter *) get_bus_free;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    struct gpio_desc * scl_gpiod;
    struct gpio_desc * sda_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *, int) set_sda;
    int (*)(struct i2c_adapter *) get_bus_free;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    struct gpio_desc * scl_gpiod;
    struct gpio_desc * sda_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *, int) set_sda;
    int (*)(struct i2c_adapter *) get_bus_free;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    struct gpio_desc * scl_gpiod;
    struct gpio_desc * sda_gpiod;
    struct pinctrl * pinctrl;
    struct pinctrl_state * pins_default;
    struct pinctrl_state * pins_gpio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *, int) set_sda;
    int (*)(struct i2c_adapter *) get_bus_free;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    struct gpio_desc * scl_gpiod;
    struct gpio_desc * sda_gpiod;
    struct pinctrl * pinctrl;
    struct pinctrl_state * pins_default;
    struct pinctrl_state * pins_gpio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *, int) set_sda;
    int (*)(struct i2c_adapter *) get_bus_free;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    struct gpio_desc * scl_gpiod;
    struct gpio_desc * sda_gpiod;
    struct pinctrl * pinctrl;
    struct pinctrl_state * pins_default;
    struct pinctrl_state * pins_gpio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *, int) set_sda;
    int (*)(struct i2c_adapter *) get_bus_free;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    struct gpio_desc * scl_gpiod;
    struct gpio_desc * sda_gpiod;
    struct pinctrl * pinctrl;
    struct pinctrl_state * pins_default;
    struct pinctrl_state * pins_gpio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *, int) set_sda;
    int (*)(struct i2c_adapter *) get_bus_free;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    struct gpio_desc * scl_gpiod;
    struct gpio_desc * sda_gpiod;
    struct pinctrl * pinctrl;
    struct pinctrl_state * pins_default;
    struct pinctrl_state * pins_gpio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *, int) set_sda;
    int (*)(struct i2c_adapter *) get_bus_free;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    struct gpio_desc * scl_gpiod;
    struct gpio_desc * sda_gpiod;
    struct pinctrl * pinctrl;
    struct pinctrl_state * pins_default;
    struct pinctrl_state * pins_gpio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *, int) set_sda;
    int (*)(struct i2c_adapter *) get_bus_free;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    struct gpio_desc * scl_gpiod;
    struct gpio_desc * sda_gpiod;
    struct pinctrl * pinctrl;
    struct pinctrl_state * pins_default;
    struct pinctrl_state * pins_gpio;
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
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *, int) set_sda;
    int (*)(struct i2c_adapter *) get_bus_free;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    struct gpio_desc * scl_gpiod;
    struct gpio_desc * sda_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *, int) set_sda;
    int (*)(struct i2c_adapter *) get_bus_free;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    struct gpio_desc * scl_gpiod;
    struct gpio_desc * sda_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *, int) set_sda;
    int (*)(struct i2c_adapter *) get_bus_free;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    struct gpio_desc * scl_gpiod;
    struct gpio_desc * sda_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *, int) set_sda;
    int (*)(struct i2c_adapter *) get_bus_free;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    struct gpio_desc * scl_gpiod;
    struct gpio_desc * sda_gpiod;
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
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *, int) set_sda;
    int (*)(struct i2c_adapter *) get_bus_free;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    struct gpio_desc * scl_gpiod;
    struct gpio_desc * sda_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *, int) set_sda;
    int (*)(struct i2c_adapter *) get_bus_free;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    struct gpio_desc * scl_gpiod;
    struct gpio_desc * sda_gpiod;
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
<b>Field added. </b>
<code>void (*)(struct i2c_adapter *, int) set_sda</code>
</li>
<li>
<b>Field added. </b>
<code>struct gpio_desc * scl_gpiod</code>
</li>
<li>
<b>Field added. </b>
<code>struct gpio_desc * sda_gpiod</code>
</li>
<li>
<b>Field removed. </b>
<code>int scl_gpio</code>
</li>
<li>
<b>Field removed. </b>
<code>int sda_gpio</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct i2c_adapter *) get_bus_free</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct pinctrl * pinctrl</code>
</li>
<li>
<b>Field added. </b>
<code>struct pinctrl_state * pins_default</code>
</li>
<li>
<b>Field added. </b>
<code>struct pinctrl_state * pins_gpio</code>
</li>
</ul>
</details>
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
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *, int) set_sda;
    int (*)(struct i2c_adapter *) get_bus_free;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    struct gpio_desc * scl_gpiod;
    struct gpio_desc * sda_gpiod;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct i2c_bus_recovery_info {
    int (*)(struct i2c_adapter *) recover_bus;
    int (*)(struct i2c_adapter *) get_scl;
    void (*)(struct i2c_adapter *, int) set_scl;
    int (*)(struct i2c_adapter *) get_sda;
    void (*)(struct i2c_adapter *, int) set_sda;
    int (*)(struct i2c_adapter *) get_bus_free;
    void (*)(struct i2c_adapter *) prepare_recovery;
    void (*)(struct i2c_adapter *) unprepare_recovery;
    struct gpio_desc * scl_gpiod;
    struct gpio_desc * sda_gpiod;
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
