# Function: <code>__btf_resolve_size</code>

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
const struct btf_type * __btf_resolve_size(const struct btf * btf, const struct btf_type * type, u32 * type_size, const struct btf_type * * elem_type, u32 * elem_id, u32 * total_nelems, u32 * type_id)
```

```json
{
  "name": "__btf_resolve_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581096640,
      "name": "__btf_resolve_size",
      "external": false,
      "loc": "kernel/bpf/btf.c:1692",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_show_obj_safe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096640,
      "name": "__btf_resolve_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
const struct btf_type * __btf_resolve_size(const struct btf * btf, const struct btf_type * type, u32 * type_size, const struct btf_type * * elem_type, u32 * elem_id, u32 * total_nelems, u32 * type_id)
```

```json
{
  "name": "__btf_resolve_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581115824,
      "name": "__btf_resolve_size",
      "external": false,
      "loc": "kernel/bpf/btf.c:1693",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_struct_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581115824,
      "name": "__btf_resolve_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
const struct btf_type * __btf_resolve_size(const struct btf * btf, const struct btf_type * type, u32 * type_size, const struct btf_type * * elem_type, u32 * elem_id, u32 * total_nelems, u32 * type_id)
```

```json
{
  "name": "__btf_resolve_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581347120,
      "name": "__btf_resolve_size",
      "external": false,
      "loc": "kernel/bpf/btf.c:1693",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_struct_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581347120,
      "name": "__btf_resolve_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
const struct btf_type * __btf_resolve_size(const struct btf * btf, const struct btf_type * type, u32 * type_size, const struct btf_type * * elem_type, u32 * elem_id, u32 * total_nelems, u32 * type_id)
```

```json
{
  "name": "__btf_resolve_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581657200,
      "name": "__btf_resolve_size",
      "external": false,
      "loc": "kernel/bpf/btf.c:1821",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_struct_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581657200,
      "name": "__btf_resolve_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
const struct btf_type * __btf_resolve_size(const struct btf * btf, const struct btf_type * type, u32 * type_size, const struct btf_type * * elem_type, u32 * elem_id, u32 * total_nelems, u32 * type_id)
```

```json
{
  "name": "__btf_resolve_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582047088,
      "name": "__btf_resolve_size",
      "external": false,
      "loc": "kernel/bpf/btf.c:1844",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_struct_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582047088,
      "name": "__btf_resolve_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
const struct btf_type * __btf_resolve_size(const struct btf * btf, const struct btf_type * type, u32 * type_size, const struct btf_type * * elem_type, u32 * elem_id, u32 * total_nelems, u32 * type_id)
```

```json
{
  "name": "__btf_resolve_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582241760,
      "name": "__btf_resolve_size",
      "external": false,
      "loc": "kernel/bpf/btf.c:1874",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_struct_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582241760,
      "name": "__btf_resolve_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
const struct btf_type * __btf_resolve_size(const struct btf * btf, const struct btf_type * type, u32 * type_size, const struct btf_type * * elem_type, u32 * elem_id, u32 * total_nelems, u32 * type_id)
```

```json
{
  "name": "__btf_resolve_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582397424,
      "name": "__btf_resolve_size",
      "external": false,
      "loc": "kernel/bpf/btf.c:1875",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_struct_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582397424,
      "name": "__btf_resolve_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
const struct btf_type * __btf_resolve_size(const struct btf * btf, const struct btf_type * type, u32 * type_size, const struct btf_type * * elem_type, u32 * elem_id, u32 * total_nelems, u32 * type_id)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
