# Function: <code>btf_show_obj_safe</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void * btf_show_obj_safe(struct btf_show * show, const struct btf_type * t, void * data)
```

```json
{
  "name": "btf_show_obj_safe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581096992,
      "name": "btf_show_obj_safe",
      "external": false,
      "loc": "kernel/bpf/btf.c:1091",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_ptr_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_show_start_aggr_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096992,
      "name": "btf_show_obj_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_show_obj_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581116208,
      "name": "btf_show_obj_safe",
      "external": false,
      "loc": "kernel/bpf/btf.c:1092",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_ptr_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_show_start_aggr_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581116208,
      "name": "btf_show_obj_safe.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_show_obj_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581347504,
      "name": "btf_show_obj_safe",
      "external": false,
      "loc": "kernel/bpf/btf.c:1092",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_ptr_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_show_start_aggr_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581347504,
      "name": "btf_show_obj_safe.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_show_obj_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581657648,
      "name": "btf_show_obj_safe",
      "external": false,
      "loc": "kernel/bpf/btf.c:1187",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_ptr_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_show_start_aggr_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581657648,
      "name": "btf_show_obj_safe.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_show_obj_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582047536,
      "name": "btf_show_obj_safe",
      "external": false,
      "loc": "kernel/bpf/btf.c:1191",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_enum64_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_ptr_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_show_start_aggr_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582047536,
      "name": "btf_show_obj_safe.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_show_obj_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582242224,
      "name": "btf_show_obj_safe",
      "external": false,
      "loc": "kernel/bpf/btf.c:1210",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_enum64_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_ptr_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_show_start_aggr_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582242224,
      "name": "btf_show_obj_safe.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_show_obj_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582397888,
      "name": "btf_show_obj_safe",
      "external": false,
      "loc": "kernel/bpf/btf.c:1211",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_enum64_show",
        "kernel/bpf/btf.c:btf_enum_show",
        "kernel/bpf/btf.c:btf_ptr_show",
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_show_start_aggr_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582397888,
      "name": "btf_show_obj_safe.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void * btf_show_obj_safe(struct btf_show * show, const struct btf_type * t, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void * btf_show_obj_safe(struct btf_show * show, const struct btf_type * t, void * data)
```
</details>
</li>
</ul>
