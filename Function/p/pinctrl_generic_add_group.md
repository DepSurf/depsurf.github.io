# Function: <code>pinctrl_generic_add_group</code>

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
int pinctrl_generic_add_group(struct pinctrl_dev * pctldev, const char * name, int * pins, int num_pins, void * data)
```

```json
{
  "name": "pinctrl_generic_add_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496499160,
      "name": "pinctrl_generic_add_group",
      "external": true,
      "loc": "drivers/pinctrl/core.c:625",
      "file": "drivers/pinctrl/core.c",
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
      "addr": 18446603336496499160,
      "name": "pinctrl_generic_add_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int pinctrl_generic_add_group(struct pinctrl_dev * pctldev, const char * name, int * pins, int num_pins, void * data)
```

```json
{
  "name": "pinctrl_generic_add_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229805244,
      "name": "pinctrl_generic_add_group",
      "external": true,
      "loc": "drivers/pinctrl/core.c:625",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-rza1.c:rza1_dt_node_to_map",
        "drivers/pinctrl/pinctrl-rza2.c:rza2_dt_node_to_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map",
        "drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_dt_node_to_map",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229805244,
      "name": "pinctrl_generic_add_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int pinctrl_generic_add_group(struct pinctrl_dev * pctldev, const char * name, int * pins, int num_pins, void * data)
```

```json
{
  "name": "pinctrl_generic_add_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290706528,
      "name": "pinctrl_generic_add_group",
      "external": true,
      "loc": "drivers/pinctrl/core.c:625",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290706528,
      "name": "pinctrl_generic_add_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
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
int pinctrl_generic_add_group(struct pinctrl_dev * pctldev, const char * name, int * pins, int num_pins, void * data)
```

```json
{
  "name": "pinctrl_generic_add_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275418244,
      "name": "pinctrl_generic_add_group",
      "external": true,
      "loc": "drivers/pinctrl/core.c:625",
      "file": "drivers/pinctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275418244,
      "name": "pinctrl_generic_add_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int pinctrl_generic_add_group(struct pinctrl_dev * pctldev, const char * name, int * pins, int num_pins, void * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int pinctrl_generic_add_group(struct pinctrl_dev * pctldev, const char * name, int * pins, int num_pins, void * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int pinctrl_generic_add_group(struct pinctrl_dev * pctldev, const char * name, int * pins, int num_pins, void * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int pinctrl_generic_add_group(struct pinctrl_dev * pctldev, const char * name, int * pins, int num_pins, void * data)
```
</details>
</li>
</ul>
