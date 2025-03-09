# Function: <code>pinctrl_find_cells_size</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pinctrl_find_cells_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496515800,
      "name": "pinctrl_find_cells_size",
      "external": false,
      "loc": "drivers/pinctrl/devicetree.c:290",
      "file": "drivers/pinctrl/devicetree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/devicetree.c:pinctrl_parse_index_with_args",
        "drivers/pinctrl/devicetree.c:pinctrl_count_index_with_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496515800,
      "name": "pinctrl_find_cells_size.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
int pinctrl_find_cells_size(const struct device_node * np)
```

```json
{
  "name": "pinctrl_find_cells_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229820660,
      "name": "pinctrl_find_cells_size",
      "external": false,
      "loc": "drivers/pinctrl/devicetree.c:290",
      "file": "drivers/pinctrl/devicetree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/devicetree.c:pinctrl_parse_index_with_args",
        "drivers/pinctrl/devicetree.c:pinctrl_count_index_with_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229820660,
      "name": "pinctrl_find_cells_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pinctrl_find_cells_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290734080,
      "name": "pinctrl_find_cells_size",
      "external": false,
      "loc": "drivers/pinctrl/devicetree.c:290",
      "file": "drivers/pinctrl/devicetree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/devicetree.c:pinctrl_parse_index_with_args",
        "drivers/pinctrl/devicetree.c:pinctrl_count_index_with_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290734080,
      "name": "pinctrl_find_cells_size.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pinctrl_find_cells_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275432638,
      "name": "pinctrl_find_cells_size",
      "external": false,
      "loc": "drivers/pinctrl/devicetree.c:290",
      "file": "drivers/pinctrl/devicetree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/devicetree.c:pinctrl_parse_index_with_args",
        "drivers/pinctrl/devicetree.c:pinctrl_count_index_with_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275432638,
      "name": "pinctrl_find_cells_size.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int pinctrl_find_cells_size(const struct device_node * np)
```
</details>
</li>
</ul>
