# Function: <code>sh_pfc_read_raw_reg</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
u32 sh_pfc_read_raw_reg(void * mapped_reg, unsigned int reg_width)
```

```json
{
  "name": "sh_pfc_read_raw_reg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496643008,
      "name": "sh_pfc_read_raw_reg",
      "external": true,
      "loc": "drivers/pinctrl/sh-pfc/core.c:139",
      "file": "drivers/pinctrl/sh-pfc/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_config_mux",
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496643008,
      "name": "sh_pfc_read_raw_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
u32 sh_pfc_read_raw_reg(void * mapped_reg, unsigned int reg_width)
```

```json
{
  "name": "sh_pfc_read_raw_reg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229955376,
      "name": "sh_pfc_read_raw_reg",
      "external": true,
      "loc": "drivers/pinctrl/sh-pfc/core.c:139",
      "file": "drivers/pinctrl/sh-pfc/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_save_reg"
      ],
      "caller_func": [
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_config_mux",
        "drivers/pinctrl/sh-pfc/gpio.c:gpio_pin_setup",
        "drivers/pinctrl/sh-pfc/gpio.c:gpio_pin_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229955520,
      "name": "sh_pfc_read_raw_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
u32 sh_pfc_read_raw_reg(void * mapped_reg, unsigned int reg_width)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
u32 sh_pfc_read_raw_reg(void * mapped_reg, unsigned int reg_width)
```
</details>
</li>
</ul>
