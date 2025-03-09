# Function: <code>fdt_splice_struct_</code>

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
int fdt_splice_struct_(void * fdt, void * p, int oldlen, int newlen)
```

```json
{
  "name": "fdt_splice_struct_",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510863264,
      "name": "fdt_splice_struct_",
      "external": false,
      "loc": "scripts/dtc/libfdt/fdt_rw.c:80",
      "file": "lib/fdt_rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/fdt_rw.c:fdt_del_node",
        "lib/fdt_rw.c:fdt_delprop",
        "lib/fdt_rw.c:fdt_appendprop",
        "lib/fdt_rw.c:fdt_set_name",
        "lib/fdt_rw.c:fdt_add_property_",
        "lib/fdt_rw.c:fdt_del_node",
        "lib/fdt_rw.c:fdt_delprop",
        "lib/fdt_rw.c:fdt_appendprop",
        "lib/fdt_rw.c:fdt_set_name",
        "lib/fdt_rw.c:fdt_add_property_"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503816408,
      "name": "fdt_splice_struct_",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int fdt_splice_struct_(void * fdt, void * p, int oldlen, int newlen)
```

```json
{
  "name": "fdt_splice_struct_",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236438028,
      "name": "fdt_splice_struct_",
      "external": false,
      "loc": "scripts/dtc/libfdt/fdt_rw.c:80",
      "file": "lib/fdt_rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/fdt_rw.c:fdt_del_node",
        "lib/fdt_rw.c:fdt_delprop",
        "lib/fdt_rw.c:fdt_appendprop",
        "lib/fdt_rw.c:fdt_set_name",
        "lib/fdt_rw.c:fdt_add_property_"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236438028,
      "name": "fdt_splice_struct_",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int fdt_splice_struct_(void * fdt, void * p, int oldlen, int newlen)
```

```json
{
  "name": "fdt_splice_struct_",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297658496,
      "name": "fdt_splice_struct_",
      "external": false,
      "loc": "scripts/dtc/libfdt/fdt_rw.c:80",
      "file": "lib/fdt_rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/fdt_rw.c:fdt_del_node",
        "lib/fdt_rw.c:fdt_delprop",
        "lib/fdt_rw.c:fdt_appendprop",
        "lib/fdt_rw.c:fdt_set_name",
        "lib/fdt_rw.c:fdt_add_property_"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297658496,
      "name": "fdt_splice_struct_",
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
int fdt_splice_struct_(void * fdt, void * p, int oldlen, int newlen)
```

```json
{
  "name": "fdt_splice_struct_",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279712212,
      "name": "fdt_splice_struct_",
      "external": false,
      "loc": "scripts/dtc/libfdt/fdt_rw.c:80",
      "file": "lib/fdt_rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/fdt_rw.c:fdt_del_node",
        "lib/fdt_rw.c:fdt_delprop",
        "lib/fdt_rw.c:fdt_appendprop",
        "lib/fdt_rw.c:fdt_set_name",
        "lib/fdt_rw.c:fdt_add_property_"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279712212,
      "name": "fdt_splice_struct_",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int fdt_splice_struct_(void * fdt, void * p, int oldlen, int newlen)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int fdt_splice_struct_(void * fdt, void * p, int oldlen, int newlen)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int fdt_splice_struct_(void * fdt, void * p, int oldlen, int newlen)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int fdt_splice_struct_(void * fdt, void * p, int oldlen, int newlen)
```
</details>
</li>
</ul>
