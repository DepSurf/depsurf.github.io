# Function: <code>tc3589x_set_bits</code>

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
int tc3589x_set_bits(struct tc3589x * tc3589x, u8 reg, u8 mask, u8 val)
```

```json
{
  "name": "tc3589x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499268104,
      "name": "tc3589x_set_bits",
      "external": true,
      "loc": "drivers/mfd/tc3589x.c:123",
      "file": "drivers/mfd/tc3589x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_input",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499268104,
      "name": "tc3589x_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int tc3589x_set_bits(struct tc3589x * tc3589x, u8 reg, u8 mask, u8 val)
```

```json
{
  "name": "tc3589x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231784264,
      "name": "tc3589x_set_bits",
      "external": true,
      "loc": "drivers/mfd/tc3589x.c:123",
      "file": "drivers/mfd/tc3589x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_input",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231784264,
      "name": "tc3589x_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int tc3589x_set_bits(struct tc3589x * tc3589x, u8 reg, u8 mask, u8 val)
```

```json
{
  "name": "tc3589x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292455552,
      "name": "tc3589x_set_bits",
      "external": true,
      "loc": "drivers/mfd/tc3589x.c:123",
      "file": "drivers/mfd/tc3589x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_input",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292455552,
      "name": "tc3589x_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int tc3589x_set_bits(struct tc3589x * tc3589x, u8 reg, u8 mask, u8 val)
```

```json
{
  "name": "tc3589x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276524844,
      "name": "tc3589x_set_bits",
      "external": true,
      "loc": "drivers/mfd/tc3589x.c:123",
      "file": "drivers/mfd/tc3589x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_set_config",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_input",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_direction_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276524844,
      "name": "tc3589x_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
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
int tc3589x_set_bits(struct tc3589x * tc3589x, u8 reg, u8 mask, u8 val)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int tc3589x_set_bits(struct tc3589x * tc3589x, u8 reg, u8 mask, u8 val)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int tc3589x_set_bits(struct tc3589x * tc3589x, u8 reg, u8 mask, u8 val)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int tc3589x_set_bits(struct tc3589x * tc3589x, u8 reg, u8 mask, u8 val)
```
</details>
</li>
</ul>
