# Struct: <code>palmas_pctrl_chip_info</code>

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
struct palmas_pctrl_chip_info {
    struct device * dev;
    struct pinctrl_dev * pctl;
    struct palmas * palmas;
    int[26] pins_current_opt;
    const struct palmas_pin_function * functions;
    unsigned int num_functions;
    const struct palmas_pingroup * pin_groups;
    int num_pin_groups;
    const struct pinctrl_pin_desc * pins;
    unsigned int num_pins;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct palmas_pctrl_chip_info {
    struct device * dev;
    struct pinctrl_dev * pctl;
    struct palmas * palmas;
    int[26] pins_current_opt;
    const struct palmas_pin_function * functions;
    unsigned int num_functions;
    const struct palmas_pingroup * pin_groups;
    int num_pin_groups;
    const struct pinctrl_pin_desc * pins;
    unsigned int num_pins;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct palmas_pctrl_chip_info {
    struct device * dev;
    struct pinctrl_dev * pctl;
    struct palmas * palmas;
    int[26] pins_current_opt;
    const struct palmas_pin_function * functions;
    unsigned int num_functions;
    const struct palmas_pingroup * pin_groups;
    int num_pin_groups;
    const struct pinctrl_pin_desc * pins;
    unsigned int num_pins;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct palmas_pctrl_chip_info {
    struct device * dev;
    struct pinctrl_dev * pctl;
    struct palmas * palmas;
    int[26] pins_current_opt;
    const struct palmas_pin_function * functions;
    unsigned int num_functions;
    const struct palmas_pingroup * pin_groups;
    int num_pin_groups;
    const struct pinctrl_pin_desc * pins;
    unsigned int num_pins;
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
struct palmas_pctrl_chip_info {
    struct device * dev;
    struct pinctrl_dev * pctl;
    struct palmas * palmas;
    int[26] pins_current_opt;
    const struct palmas_pin_function * functions;
    unsigned int num_functions;
    const struct palmas_pingroup * pin_groups;
    int num_pin_groups;
    const struct pinctrl_pin_desc * pins;
    unsigned int num_pins;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct palmas_pctrl_chip_info {
    struct device * dev;
    struct pinctrl_dev * pctl;
    struct palmas * palmas;
    int[26] pins_current_opt;
    const struct palmas_pin_function * functions;
    unsigned int num_functions;
    const struct palmas_pingroup * pin_groups;
    int num_pin_groups;
    const struct pinctrl_pin_desc * pins;
    unsigned int num_pins;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct palmas_pctrl_chip_info {
    struct device * dev;
    struct pinctrl_dev * pctl;
    struct palmas * palmas;
    int[26] pins_current_opt;
    const struct palmas_pin_function * functions;
    unsigned int num_functions;
    const struct palmas_pingroup * pin_groups;
    int num_pin_groups;
    const struct pinctrl_pin_desc * pins;
    unsigned int num_pins;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct palmas_pctrl_chip_info {
    struct device * dev;
    struct pinctrl_dev * pctl;
    struct palmas * palmas;
    int[26] pins_current_opt;
    const struct palmas_pin_function * functions;
    unsigned int num_functions;
    const struct palmas_pingroup * pin_groups;
    int num_pin_groups;
    const struct pinctrl_pin_desc * pins;
    unsigned int num_pins;
}
```
</details>
</li>
</ul>
