# Function: <code>fdt_next_tag</code>

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
uint32_t fdt_next_tag(const void * fdt, int startoffset, int * nextoffset)
```

```json
{
  "name": "fdt_next_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510855496,
      "name": "fdt_next_tag",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt.c:126",
      "file": "lib/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/fdt.c:fdt_next_node",
        "lib/fdt.c:fdt_next_node",
        "lib/fdt.c:fdt_check_prop_offset_",
        "lib/fdt.c:fdt_check_node_offset_",
        "lib/fdt_ro.c:fdt_check_full",
        "lib/fdt_ro.c:nextprop_",
        "lib/fdt_rw.c:fdt_open_into",
        "lib/fdt_sw.c:fdt_finish",
        "lib/fdt_sw.c:fdt_finish",
        "lib/fdt.c:fdt_next_node",
        "lib/fdt.c:fdt_next_node",
        "lib/fdt.c:fdt_check_prop_offset_",
        "lib/fdt.c:fdt_check_node_offset_",
        "lib/fdt_ro.c:fdt_check_full",
        "lib/fdt_ro.c:nextprop_",
        "lib/fdt_rw.c:fdt_open_into"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503808672,
      "name": "fdt_next_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
uint32_t fdt_next_tag(const void * fdt, int startoffset, int * nextoffset)
```

```json
{
  "name": "fdt_next_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236430532,
      "name": "fdt_next_tag",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt.c:126",
      "file": "lib/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/fdt.c:fdt_next_node",
        "lib/fdt.c:fdt_check_prop_offset_",
        "lib/fdt.c:fdt_check_node_offset_",
        "lib/fdt_ro.c:fdt_check_full",
        "lib/fdt_ro.c:nextprop_",
        "lib/fdt_rw.c:fdt_open_into"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236430532,
      "name": "fdt_next_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
uint32_t fdt_next_tag(const void * fdt, int startoffset, int * nextoffset)
```

```json
{
  "name": "fdt_next_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297647504,
      "name": "fdt_next_tag",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt.c:126",
      "file": "lib/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/fdt.c:fdt_next_node",
        "lib/fdt.c:fdt_next_node",
        "lib/fdt.c:fdt_check_prop_offset_",
        "lib/fdt.c:fdt_check_node_offset_",
        "lib/fdt_ro.c:fdt_check_full",
        "lib/fdt_ro.c:nextprop_",
        "lib/fdt_rw.c:fdt_open_into"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297647504,
      "name": "fdt_next_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
uint32_t fdt_next_tag(const void * fdt, int startoffset, int * nextoffset)
```

```json
{
  "name": "fdt_next_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279704546,
      "name": "fdt_next_tag",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt.c:126",
      "file": "lib/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/fdt.c:fdt_next_node",
        "lib/fdt.c:fdt_next_node",
        "lib/fdt.c:fdt_check_prop_offset_",
        "lib/fdt.c:fdt_check_node_offset_",
        "lib/fdt_ro.c:fdt_check_full",
        "lib/fdt_ro.c:nextprop_",
        "lib/fdt_rw.c:fdt_open_into"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279704546,
      "name": "fdt_next_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
uint32_t fdt_next_tag(const void * fdt, int startoffset, int * nextoffset)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
uint32_t fdt_next_tag(const void * fdt, int startoffset, int * nextoffset)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
uint32_t fdt_next_tag(const void * fdt, int startoffset, int * nextoffset)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
uint32_t fdt_next_tag(const void * fdt, int startoffset, int * nextoffset)
```
</details>
</li>
</ul>
