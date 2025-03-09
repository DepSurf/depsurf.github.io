# Function: <code>pinmux_generic_get_function</code>

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
struct function_desc * pinmux_generic_get_function(struct pinctrl_dev * pctldev, unsigned int selector)
```

```json
{
  "name": "pinmux_generic_get_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496507168,
      "name": "pinmux_generic_get_function",
      "external": true,
      "loc": "drivers/pinctrl/pinmux.c:749",
      "file": "drivers/pinctrl/pinmux.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-single.c:pcs_set_mux",
        "drivers/pinctrl/pinctrl-single.c:pcs_get_function",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinmux_set_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496507168,
      "name": "pinmux_generic_get_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct function_desc * pinmux_generic_get_function(struct pinctrl_dev * pctldev, unsigned int selector)
```

```json
{
  "name": "pinmux_generic_get_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229812760,
      "name": "pinmux_generic_get_function",
      "external": true,
      "loc": "drivers/pinctrl/pinmux.c:749",
      "file": "drivers/pinctrl/pinmux.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza2.c:rza2_set_mux",
        "drivers/pinctrl/pinctrl-single.c:pcs_set_mux",
        "drivers/pinctrl/pinctrl-single.c:pcs_get_function",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinmux_set_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229812760,
      "name": "pinmux_generic_get_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct function_desc * pinmux_generic_get_function(struct pinctrl_dev * pctldev, unsigned int selector)
```

```json
{
  "name": "pinmux_generic_get_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290721152,
      "name": "pinmux_generic_get_function",
      "external": true,
      "loc": "drivers/pinctrl/pinmux.c:749",
      "file": "drivers/pinctrl/pinmux.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-single.c:pcs_set_mux",
        "drivers/pinctrl/pinctrl-single.c:pcs_get_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290721152,
      "name": "pinmux_generic_get_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct function_desc * pinmux_generic_get_function(struct pinctrl_dev * pctldev, unsigned int selector)
```

```json
{
  "name": "pinmux_generic_get_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275425470,
      "name": "pinmux_generic_get_function",
      "external": true,
      "loc": "drivers/pinctrl/pinmux.c:749",
      "file": "drivers/pinctrl/pinmux.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-single.c:pcs_set_mux",
        "drivers/pinctrl/pinctrl-single.c:pcs_get_function"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275425470,
      "name": "pinmux_generic_get_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct function_desc * pinmux_generic_get_function(struct pinctrl_dev * pctldev, unsigned int selector)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct function_desc * pinmux_generic_get_function(struct pinctrl_dev * pctldev, unsigned int selector)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct function_desc * pinmux_generic_get_function(struct pinctrl_dev * pctldev, unsigned int selector)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct function_desc * pinmux_generic_get_function(struct pinctrl_dev * pctldev, unsigned int selector)
```
</details>
</li>
</ul>
