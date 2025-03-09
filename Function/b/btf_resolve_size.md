# Function: <code>btf_resolve_size</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
const struct btf_type * btf_resolve_size(const struct btf * btf, const struct btf_type * type, u32 * type_size, const struct btf_type * * elem_type, u32 * total_nelems)
```

```json
{
  "name": "btf_resolve_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581085776,
      "name": "btf_resolve_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1091",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581085776,
      "name": "btf_resolve_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct btf_type * btf_resolve_size(const struct btf * btf, const struct btf_type * type, u32 * type_size)
```

```json
{
  "name": "btf_resolve_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581097069,
      "name": "btf_resolve_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1759",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_show_obj_safe"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581111744,
      "name": "btf_resolve_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct btf_type * btf_resolve_size(const struct btf * btf, const struct btf_type * type, u32 * type_size)
```

```json
{
  "name": "btf_resolve_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581143790,
      "name": "btf_resolve_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1761",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581130336,
      "name": "btf_resolve_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct btf_type * btf_resolve_size(const struct btf * btf, const struct btf_type * type, u32 * type_size)
```

```json
{
  "name": "btf_resolve_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581377074,
      "name": "btf_resolve_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1761",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581362784,
      "name": "btf_resolve_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct btf_type * btf_resolve_size(const struct btf * btf, const struct btf_type * type, u32 * type_size)
```

```json
{
  "name": "btf_resolve_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581691938,
      "name": "btf_resolve_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1890",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581678608,
      "name": "btf_resolve_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct btf_type * btf_resolve_size(const struct btf * btf, const struct btf_type * type, u32 * type_size)
```

```json
{
  "name": "btf_resolve_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582090623,
      "name": "btf_resolve_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1914",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_type_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582073088,
      "name": "btf_resolve_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct btf_type * btf_resolve_size(const struct btf * btf, const struct btf_type * type, u32 * type_size)
```

```json
{
  "name": "btf_resolve_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582287129,
      "name": "btf_resolve_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1944",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_type_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269296,
      "name": "btf_resolve_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct btf_type * btf_resolve_size(const struct btf * btf, const struct btf_type * type, u32 * type_size)
```

```json
{
  "name": "btf_resolve_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582444013,
      "name": "btf_resolve_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1945",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_prepare_func_args"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_type_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582424832,
      "name": "btf_resolve_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
const struct btf_type * btf_resolve_size(const struct btf * btf, const struct btf_type * type, u32 * type_size, const struct btf_type * * elem_type, u32 * total_nelems)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct btf_type * * elem_type</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 * total_nelems</code>
</li>
</ul>
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
