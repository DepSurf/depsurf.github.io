# Function: <code>fdt_getprop_namelen</code>

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
const void * fdt_getprop_namelen(const void * fdt, int nodeoffset, const char * name, int namelen, int * lenp)
```

```json
{
  "name": "fdt_getprop_namelen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510858536,
      "name": "fdt_getprop_namelen",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt_ro.c:434",
      "file": "lib/fdt_ro.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/fdt_ro.c:fdt_node_check_compatible",
        "lib/fdt_ro.c:fdt_stringlist_get",
        "lib/fdt_ro.c:fdt_stringlist_search",
        "lib/fdt_ro.c:fdt_stringlist_count",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_get_alias_namelen",
        "lib/fdt_ro.c:fdt_get_phandle",
        "lib/fdt_ro.c:fdt_get_phandle",
        "lib/fdt_wip.c:fdt_setprop_inplace_namelen_partial",
        "lib/fdt_ro.c:fdt_get_alias_namelen",
        "lib/fdt_ro.c:fdt_getprop",
        "lib/fdt_wip.c:fdt_setprop_inplace_namelen_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503811752,
      "name": "fdt_getprop_namelen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
const void * fdt_getprop_namelen(const void * fdt, int nodeoffset, const char * name, int namelen, int * lenp)
```

```json
{
  "name": "fdt_getprop_namelen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236433572,
      "name": "fdt_getprop_namelen",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt_ro.c:434",
      "file": "lib/fdt_ro.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/fdt_ro.c:fdt_get_alias_namelen",
        "lib/fdt_ro.c:fdt_getprop",
        "lib/fdt_wip.c:fdt_setprop_inplace_namelen_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236433572,
      "name": "fdt_getprop_namelen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
const void * fdt_getprop_namelen(const void * fdt, int nodeoffset, const char * name, int namelen, int * lenp)
```

```json
{
  "name": "fdt_getprop_namelen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297652048,
      "name": "fdt_getprop_namelen",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt_ro.c:434",
      "file": "lib/fdt_ro.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/fdt_ro.c:fdt_get_alias_namelen",
        "lib/fdt_ro.c:fdt_getprop",
        "lib/fdt_wip.c:fdt_setprop_inplace_namelen_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297652048,
      "name": "fdt_getprop_namelen",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
const void * fdt_getprop_namelen(const void * fdt, int nodeoffset, const char * name, int namelen, int * lenp)
```

```json
{
  "name": "fdt_getprop_namelen",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279707746,
      "name": "fdt_getprop_namelen",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt_ro.c:434",
      "file": "lib/fdt_ro.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/fdt_ro.c:fdt_node_check_compatible",
        "lib/fdt_ro.c:fdt_stringlist_get",
        "lib/fdt_ro.c:fdt_stringlist_search",
        "lib/fdt_ro.c:fdt_stringlist_count",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_get_alias_namelen",
        "lib/fdt_ro.c:fdt_get_phandle",
        "lib/fdt_ro.c:fdt_get_phandle",
        "lib/fdt_wip.c:fdt_setprop_inplace_namelen_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279707746,
      "name": "fdt_getprop_namelen",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
const void * fdt_getprop_namelen(const void * fdt, int nodeoffset, const char * name, int namelen, int * lenp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
const void * fdt_getprop_namelen(const void * fdt, int nodeoffset, const char * name, int namelen, int * lenp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
const void * fdt_getprop_namelen(const void * fdt, int nodeoffset, const char * name, int namelen, int * lenp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
const void * fdt_getprop_namelen(const void * fdt, int nodeoffset, const char * name, int namelen, int * lenp)
```
</details>
</li>
</ul>
