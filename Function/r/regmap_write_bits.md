# Function: <code>regmap_write_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int regmap_write_bits(struct regmap * map, unsigned int reg, unsigned int mask, unsigned int val)
```

```json
{
  "name": "regmap_write_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584507840,
      "name": "regmap_write_bits",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2581",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_fields_force_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584507840,
      "name": "regmap_write_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regmap_write_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585319827,
      "name": "regmap_write_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1137",
      "file": "drivers/pinctrl/pinctrl-sx150x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "regmap_write_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1137",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regmap_write_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585204358,
      "name": "regmap_write_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1137",
      "file": "drivers/pinctrl/pinctrl-sx150x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "regmap_write_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1137",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regmap_write_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585659239,
      "name": "regmap_write_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1177",
      "file": "drivers/pinctrl/pinctrl-sx150x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple",
        "drivers/pinctrl/pinctrl-sx150x.c:__sx150x_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "regmap_write_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1177",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regmap_write_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586821814,
      "name": "regmap_write_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1202",
      "file": "drivers/pinctrl/pinctrl-sx150x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple",
        "drivers/pinctrl/pinctrl-sx150x.c:__sx150x_gpio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "regmap_write_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1202",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regmap_write_bits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587962646,
      "name": "regmap_write_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1250",
      "file": "drivers/pinctrl/pinctrl-sx150x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple",
        "drivers/pinctrl/pinctrl-sx150x.c:__sx150x_gpio_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regmap_write_bits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588237202,
      "name": "regmap_write_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1267",
      "file": "drivers/pinctrl/pinctrl-sx150x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple",
        "drivers/pinctrl/pinctrl-sx150x.c:__sx150x_gpio_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "regmap_write_bits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588530082,
      "name": "regmap_write_bits",
      "external": false,
      "loc": "include/linux/regmap.h:1267",
      "file": "drivers/pinctrl/pinctrl-sx150x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_output",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_direction_input",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_gpio_set_multiple",
        "drivers/pinctrl/pinctrl-sx150x.c:__sx150x_gpio_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int regmap_write_bits(struct regmap * map, unsigned int reg, unsigned int mask, unsigned int val)
```
</details>
</li>
</ul>
