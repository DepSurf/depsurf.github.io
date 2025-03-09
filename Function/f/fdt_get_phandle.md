# Function: <code>fdt_get_phandle</code>

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
uint32_t fdt_get_phandle(const void * fdt, int nodeoffset)
```

```json
{
  "name": "fdt_get_phandle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510858904,
      "name": "fdt_get_phandle",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt_ro.c:486",
      "file": "lib/fdt_ro.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/fdt_ro.c:fdt_node_offset_by_phandle",
        "lib/fdt_ro.c:fdt_find_max_phandle",
        "drivers/of/fdt.c:of_get_flat_dt_phandle",
        "lib/fdt_ro.c:fdt_node_offset_by_phandle",
        "lib/fdt_ro.c:fdt_find_max_phandle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503812200,
      "name": "fdt_get_phandle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
uint32_t fdt_get_phandle(const void * fdt, int nodeoffset)
```

```json
{
  "name": "fdt_get_phandle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236434032,
      "name": "fdt_get_phandle",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt_ro.c:486",
      "file": "lib/fdt_ro.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:of_get_flat_dt_phandle",
        "lib/fdt_ro.c:fdt_node_offset_by_phandle",
        "lib/fdt_ro.c:fdt_find_max_phandle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236434032,
      "name": "fdt_get_phandle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
uint32_t fdt_get_phandle(const void * fdt, int nodeoffset)
```

```json
{
  "name": "fdt_get_phandle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297652608,
      "name": "fdt_get_phandle",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt_ro.c:486",
      "file": "lib/fdt_ro.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:of_get_flat_dt_phandle",
        "lib/fdt_ro.c:fdt_node_offset_by_phandle",
        "lib/fdt_ro.c:fdt_find_max_phandle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297652608,
      "name": "fdt_get_phandle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
uint32_t fdt_get_phandle(const void * fdt, int nodeoffset)
```

```json
{
  "name": "fdt_get_phandle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279708188,
      "name": "fdt_get_phandle",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt_ro.c:486",
      "file": "lib/fdt_ro.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:of_get_flat_dt_phandle",
        "lib/fdt_ro.c:fdt_node_offset_by_phandle",
        "lib/fdt_ro.c:fdt_find_max_phandle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279708188,
      "name": "fdt_get_phandle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
uint32_t fdt_get_phandle(const void * fdt, int nodeoffset)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
uint32_t fdt_get_phandle(const void * fdt, int nodeoffset)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
uint32_t fdt_get_phandle(const void * fdt, int nodeoffset)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
uint32_t fdt_get_phandle(const void * fdt, int nodeoffset)
```
</details>
</li>
</ul>
