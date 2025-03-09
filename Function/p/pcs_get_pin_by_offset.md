# Function: <code>pcs_get_pin_by_offset</code>

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
int pcs_get_pin_by_offset(struct pcs_device * pcs, unsigned int offset)
```

```json
{
  "name": "pcs_get_pin_by_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496560736,
      "name": "pcs_get_pin_by_offset",
      "external": false,
      "loc": "drivers/pinctrl/pinctrl-single.c:797",
      "file": "drivers/pinctrl/pinctrl-single.c",
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
      "addr": 18446603336496560736,
      "name": "pcs_get_pin_by_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int pcs_get_pin_by_offset(struct pcs_device * pcs, unsigned int offset)
```

```json
{
  "name": "pcs_get_pin_by_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229869852,
      "name": "pcs_get_pin_by_offset",
      "external": false,
      "loc": "drivers/pinctrl/pinctrl-single.c:797",
      "file": "drivers/pinctrl/pinctrl-single.c",
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
      "addr": 3229869852,
      "name": "pcs_get_pin_by_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int pcs_get_pin_by_offset(struct pcs_device * pcs, unsigned int offset)
```

```json
{
  "name": "pcs_get_pin_by_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290760032,
      "name": "pcs_get_pin_by_offset",
      "external": false,
      "loc": "drivers/pinctrl/pinctrl-single.c:797",
      "file": "drivers/pinctrl/pinctrl-single.c",
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
      "addr": 13835058055290760032,
      "name": "pcs_get_pin_by_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int pcs_get_pin_by_offset(struct pcs_device * pcs, unsigned int offset)
```

```json
{
  "name": "pcs_get_pin_by_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275448002,
      "name": "pcs_get_pin_by_offset",
      "external": false,
      "loc": "drivers/pinctrl/pinctrl-single.c:797",
      "file": "drivers/pinctrl/pinctrl-single.c",
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
      "addr": 18446743936275448002,
      "name": "pcs_get_pin_by_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int pcs_get_pin_by_offset(struct pcs_device * pcs, unsigned int offset)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int pcs_get_pin_by_offset(struct pcs_device * pcs, unsigned int offset)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int pcs_get_pin_by_offset(struct pcs_device * pcs, unsigned int offset)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int pcs_get_pin_by_offset(struct pcs_device * pcs, unsigned int offset)
```
</details>
</li>
</ul>
