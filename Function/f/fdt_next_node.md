# Function: <code>fdt_next_node</code>

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
int fdt_next_node(const void * fdt, int offset, int * depth)
```

```json
{
  "name": "fdt_next_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510855912,
      "name": "fdt_next_node",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt.c:197",
      "file": "lib/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/fdt.c:fdt_next_subnode",
        "lib/fdt.c:fdt_first_subnode",
        "lib/fdt_ro.c:fdt_node_offset_by_compatible",
        "lib/fdt_ro.c:fdt_node_offset_by_phandle",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_get_path",
        "lib/fdt_ro.c:fdt_find_max_phandle",
        "lib/fdt_wip.c:fdt_node_end_offset_",
        "drivers/of/fdt.c:of_scan_flat_dt",
        "drivers/of/fdt.c:of_scan_flat_dt",
        "drivers/of/fdt.c:unflatten_dt_nodes",
        "lib/fdt.c:fdt_next_subnode",
        "lib/fdt.c:fdt_first_subnode",
        "lib/fdt_ro.c:fdt_node_offset_by_compatible",
        "lib/fdt_ro.c:fdt_node_offset_by_phandle",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_get_path",
        "lib/fdt_ro.c:fdt_find_max_phandle",
        "lib/fdt_wip.c:fdt_node_end_offset_"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503809088,
      "name": "fdt_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int fdt_next_node(const void * fdt, int offset, int * depth)
```

```json
{
  "name": "fdt_next_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236430984,
      "name": "fdt_next_node",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt.c:197",
      "file": "lib/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:of_scan_flat_dt",
        "drivers/of/fdt.c:of_scan_flat_dt",
        "drivers/of/fdt.c:unflatten_dt_nodes",
        "lib/fdt.c:fdt_next_subnode",
        "lib/fdt.c:fdt_first_subnode",
        "lib/fdt_ro.c:fdt_node_offset_by_compatible",
        "lib/fdt_ro.c:fdt_node_offset_by_phandle",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_get_path",
        "lib/fdt_ro.c:fdt_find_max_phandle",
        "lib/fdt_wip.c:fdt_node_end_offset_"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236430984,
      "name": "fdt_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int fdt_next_node(const void * fdt, int offset, int * depth)
```

```json
{
  "name": "fdt_next_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297648224,
      "name": "fdt_next_node",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt.c:197",
      "file": "lib/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:of_scan_flat_dt",
        "drivers/of/fdt.c:of_scan_flat_dt",
        "drivers/of/fdt.c:unflatten_dt_nodes",
        "drivers/of/fdt.c:unflatten_dt_nodes",
        "lib/fdt.c:fdt_next_subnode",
        "lib/fdt.c:fdt_first_subnode",
        "lib/fdt_ro.c:fdt_node_offset_by_compatible",
        "lib/fdt_ro.c:fdt_node_offset_by_compatible",
        "lib/fdt_ro.c:fdt_node_offset_by_phandle",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_get_path",
        "lib/fdt_ro.c:fdt_find_max_phandle",
        "lib/fdt_ro.c:fdt_find_max_phandle",
        "lib/fdt_wip.c:fdt_nop_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297648224,
      "name": "fdt_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int fdt_next_node(const void * fdt, int offset, int * depth)
```

```json
{
  "name": "fdt_next_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279704990,
      "name": "fdt_next_node",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt.c:197",
      "file": "lib/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:of_scan_flat_dt",
        "drivers/of/fdt.c:of_scan_flat_dt",
        "drivers/of/fdt.c:unflatten_dt_nodes",
        "lib/fdt.c:fdt_next_subnode",
        "lib/fdt.c:fdt_first_subnode",
        "lib/fdt_ro.c:fdt_node_offset_by_compatible",
        "lib/fdt_ro.c:fdt_node_offset_by_compatible",
        "lib/fdt_ro.c:fdt_node_offset_by_phandle",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_get_path",
        "lib/fdt_ro.c:fdt_find_max_phandle",
        "lib/fdt_wip.c:fdt_nop_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279704990,
      "name": "fdt_next_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int fdt_next_node(const void * fdt, int offset, int * depth)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int fdt_next_node(const void * fdt, int offset, int * depth)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int fdt_next_node(const void * fdt, int offset, int * depth)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int fdt_next_node(const void * fdt, int offset, int * depth)
```
</details>
</li>
</ul>
