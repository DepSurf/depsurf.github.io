# Function: <code>pinctrl_parse_index_with_args</code>

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
int pinctrl_parse_index_with_args(const struct device_node * np, const char * list_name, int index, struct of_phandle_args * out_args)
```

```json
{
  "name": "pinctrl_parse_index_with_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496515968,
      "name": "pinctrl_parse_index_with_args",
      "external": true,
      "loc": "drivers/pinctrl/devicetree.c:409",
      "file": "drivers/pinctrl/devicetree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-single.c:pcs_parse_bits_in_pinctrl_entry",
        "drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496515968,
      "name": "pinctrl_parse_index_with_args",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int pinctrl_parse_index_with_args(const struct device_node * np, const char * list_name, int index, struct of_phandle_args * out_args)
```

```json
{
  "name": "pinctrl_parse_index_with_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229820836,
      "name": "pinctrl_parse_index_with_args",
      "external": true,
      "loc": "drivers/pinctrl/devicetree.c:409",
      "file": "drivers/pinctrl/devicetree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map",
        "drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_dt_node_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229820836,
      "name": "pinctrl_parse_index_with_args",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int pinctrl_parse_index_with_args(const struct device_node * np, const char * list_name, int index, struct of_phandle_args * out_args)
```

```json
{
  "name": "pinctrl_parse_index_with_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290734288,
      "name": "pinctrl_parse_index_with_args",
      "external": true,
      "loc": "drivers/pinctrl/devicetree.c:409",
      "file": "drivers/pinctrl/devicetree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290734288,
      "name": "pinctrl_parse_index_with_args",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
int pinctrl_parse_index_with_args(const struct device_node * np, const char * list_name, int index, struct of_phandle_args * out_args)
```

```json
{
  "name": "pinctrl_parse_index_with_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275432740,
      "name": "pinctrl_parse_index_with_args",
      "external": true,
      "loc": "drivers/pinctrl/devicetree.c:409",
      "file": "drivers/pinctrl/devicetree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275432740,
      "name": "pinctrl_parse_index_with_args",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int pinctrl_parse_index_with_args(const struct device_node * np, const char * list_name, int index, struct of_phandle_args * out_args)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int pinctrl_parse_index_with_args(const struct device_node * np, const char * list_name, int index, struct of_phandle_args * out_args)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int pinctrl_parse_index_with_args(const struct device_node * np, const char * list_name, int index, struct of_phandle_args * out_args)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int pinctrl_parse_index_with_args(const struct device_node * np, const char * list_name, int index, struct of_phandle_args * out_args)
```
</details>
</li>
</ul>
