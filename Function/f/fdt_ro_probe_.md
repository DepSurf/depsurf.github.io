# Function: <code>fdt_ro_probe_</code>

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
int fdt_ro_probe_(const void * fdt)
```

```json
{
  "name": "fdt_ro_probe_",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510854920,
      "name": "fdt_ro_probe_",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt.c:18",
      "file": "lib/fdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/fdt.c:fdt_move",
        "lib/fdt_ro.c:fdt_node_offset_by_compatible",
        "lib/fdt_ro.c:fdt_node_offset_by_phandle",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_supernode_atdepth_offset",
        "lib/fdt_ro.c:fdt_get_path",
        "lib/fdt_ro.c:fdt_get_name",
        "lib/fdt_ro.c:fdt_path_offset_namelen",
        "lib/fdt_ro.c:fdt_subnode_offset_namelen",
        "lib/fdt_ro.c:fdt_get_mem_rsv",
        "lib/fdt_ro.c:fdt_get_string",
        "lib/fdt_rw.c:fdt_open_into",
        "lib/fdt_rw.c:fdt_rw_probe_",
        "lib/fdt.c:fdt_move",
        "lib/fdt_ro.c:fdt_node_offset_by_compatible",
        "lib/fdt_ro.c:fdt_node_offset_by_phandle",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_supernode_atdepth_offset",
        "lib/fdt_ro.c:fdt_get_path",
        "lib/fdt_ro.c:fdt_get_name",
        "lib/fdt_ro.c:fdt_path_offset_namelen",
        "lib/fdt_ro.c:fdt_subnode_offset_namelen",
        "lib/fdt_ro.c:fdt_get_mem_rsv",
        "lib/fdt_ro.c:fdt_get_string",
        "lib/fdt_rw.c:fdt_open_into",
        "lib/fdt_rw.c:fdt_rw_probe_"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503808096,
      "name": "fdt_ro_probe_",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int fdt_ro_probe_(const void * fdt)
```

```json
{
  "name": "fdt_ro_probe_",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236429932,
      "name": "fdt_ro_probe_",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt.c:18",
      "file": "lib/fdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/fdt.c:fdt_move",
        "lib/fdt_ro.c:fdt_node_offset_by_compatible",
        "lib/fdt_ro.c:fdt_node_offset_by_phandle",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_supernode_atdepth_offset",
        "lib/fdt_ro.c:fdt_get_path",
        "lib/fdt_ro.c:fdt_get_name",
        "lib/fdt_ro.c:fdt_path_offset_namelen",
        "lib/fdt_ro.c:fdt_subnode_offset_namelen",
        "lib/fdt_ro.c:fdt_get_mem_rsv",
        "lib/fdt_ro.c:fdt_get_string",
        "lib/fdt_rw.c:fdt_open_into",
        "lib/fdt_rw.c:fdt_rw_probe_"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236429932,
      "name": "fdt_ro_probe_",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int fdt_ro_probe_(const void * fdt)
```

```json
{
  "name": "fdt_ro_probe_",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297646784,
      "name": "fdt_ro_probe_",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt.c:18",
      "file": "lib/fdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/fdt.c:fdt_move",
        "lib/fdt_ro.c:fdt_node_offset_by_compatible",
        "lib/fdt_ro.c:fdt_node_offset_by_phandle",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_supernode_atdepth_offset",
        "lib/fdt_ro.c:fdt_get_path",
        "lib/fdt_ro.c:fdt_get_name",
        "lib/fdt_ro.c:fdt_path_offset_namelen",
        "lib/fdt_ro.c:fdt_subnode_offset_namelen",
        "lib/fdt_ro.c:fdt_get_mem_rsv",
        "lib/fdt_ro.c:fdt_get_string",
        "lib/fdt_rw.c:fdt_open_into",
        "lib/fdt_rw.c:fdt_rw_probe_"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297646784,
      "name": "fdt_ro_probe_",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int fdt_ro_probe_(const void * fdt)
```

```json
{
  "name": "fdt_ro_probe_",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279703526,
      "name": "fdt_ro_probe_",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt.c:18",
      "file": "lib/fdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/fdt.c:fdt_move",
        "lib/fdt_ro.c:fdt_node_offset_by_compatible",
        "lib/fdt_ro.c:fdt_node_offset_by_phandle",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_supernode_atdepth_offset",
        "lib/fdt_ro.c:fdt_get_path",
        "lib/fdt_ro.c:fdt_get_name",
        "lib/fdt_ro.c:fdt_path_offset_namelen",
        "lib/fdt_ro.c:fdt_subnode_offset_namelen",
        "lib/fdt_ro.c:fdt_get_mem_rsv",
        "lib/fdt_ro.c:fdt_get_string",
        "lib/fdt_rw.c:fdt_open_into",
        "lib/fdt_rw.c:fdt_rw_probe_"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279703526,
      "name": "fdt_ro_probe_",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int fdt_ro_probe_(const void * fdt)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int fdt_ro_probe_(const void * fdt)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int fdt_ro_probe_(const void * fdt)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int fdt_ro_probe_(const void * fdt)
```
</details>
</li>
</ul>
