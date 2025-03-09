# Function: <code>pinmux_generic_add_function</code>

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
int pinmux_generic_add_function(struct pinctrl_dev * pctldev, const char * name, const char * * groups, const unsigned int num_groups, void * data)
```

```json
{
  "name": "pinmux_generic_add_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496509800,
      "name": "pinmux_generic_add_function",
      "external": true,
      "loc": "drivers/pinctrl/pinmux.c:771",
      "file": "drivers/pinctrl/pinmux.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-single.c:pcs_parse_bits_in_pinctrl_entry",
        "drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496509800,
      "name": "pinmux_generic_add_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int pinmux_generic_add_function(struct pinctrl_dev * pctldev, const char * name, const char * * groups, const unsigned int num_groups, void * data)
```

```json
{
  "name": "pinmux_generic_add_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229815292,
      "name": "pinmux_generic_add_function",
      "external": true,
      "loc": "drivers/pinctrl/pinmux.c:771",
      "file": "drivers/pinctrl/pinmux.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-rza1.c:rza1_dt_node_to_map",
        "drivers/pinctrl/pinctrl-rza2.c:rza2_dt_node_to_map",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229815292,
      "name": "pinmux_generic_add_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int pinmux_generic_add_function(struct pinctrl_dev * pctldev, const char * name, const char * * groups, const unsigned int num_groups, void * data)
```

```json
{
  "name": "pinmux_generic_add_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290726288,
      "name": "pinmux_generic_add_function",
      "external": true,
      "loc": "drivers/pinctrl/pinmux.c:771",
      "file": "drivers/pinctrl/pinmux.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290726288,
      "name": "pinmux_generic_add_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int pinmux_generic_add_function(struct pinctrl_dev * pctldev, const char * name, const char * * groups, const unsigned int num_groups, void * data)
```

```json
{
  "name": "pinmux_generic_add_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275427696,
      "name": "pinmux_generic_add_function",
      "external": true,
      "loc": "drivers/pinctrl/pinmux.c:771",
      "file": "drivers/pinctrl/pinmux.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275427696,
      "name": "pinmux_generic_add_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int pinmux_generic_add_function(struct pinctrl_dev * pctldev, const char * name, const char * * groups, const unsigned int num_groups, void * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int pinmux_generic_add_function(struct pinctrl_dev * pctldev, const char * name, const char * * groups, const unsigned int num_groups, void * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int pinmux_generic_add_function(struct pinctrl_dev * pctldev, const char * name, const char * * groups, const unsigned int num_groups, void * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int pinmux_generic_add_function(struct pinctrl_dev * pctldev, const char * name, const char * * groups, const unsigned int num_groups, void * data)
```
</details>
</li>
</ul>
