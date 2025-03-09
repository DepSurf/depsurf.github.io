# Function: <code>btf_type_skip_modifiers</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct btf_type * btf_type_skip_modifiers(const struct btf * btf, u32 id, u32 * res_id)
```

```json
{
  "name": "btf_type_skip_modifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581084021,
      "name": "btf_type_skip_modifiers",
      "external": true,
      "loc": "kernel/bpf/btf.c:404",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_modifier_seq_show",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr"
      ],
      "caller_func": [
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581085216,
      "name": "btf_type_skip_modifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
const struct btf_type * btf_type_skip_modifiers(const struct btf * btf, u32 id, u32 * res_id)
```

```json
{
  "name": "btf_type_skip_modifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581108588,
      "name": "btf_type_skip_modifiers",
      "external": true,
      "loc": "kernel/bpf/btf.c:493",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:__btf_array_show",
        "kernel/bpf/btf.c:btf_modifier_show",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581106240,
      "name": "btf_type_skip_modifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
const struct btf_type * btf_type_skip_modifiers(const struct btf * btf, u32 id, u32 * res_id)
```

```json
{
  "name": "btf_type_skip_modifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581140946,
      "name": "btf_type_skip_modifiers",
      "external": true,
      "loc": "kernel/bpf/btf.c:494",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:__btf_array_show",
        "kernel/bpf/btf.c:btf_modifier_show",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125440,
      "name": "btf_type_skip_modifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
const struct btf_type * btf_type_skip_modifiers(const struct btf * btf, u32 id, u32 * res_id)
```

```json
{
  "name": "btf_type_skip_modifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581373773,
      "name": "btf_type_skip_modifiers",
      "external": true,
      "loc": "kernel/bpf/btf.c:494",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:__btf_array_show",
        "kernel/bpf/btf.c:btf_modifier_show",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581357216,
      "name": "btf_type_skip_modifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
const struct btf_type * btf_type_skip_modifiers(const struct btf * btf, u32 id, u32 * res_id)
```

```json
{
  "name": "btf_type_skip_modifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581668656,
      "name": "btf_type_skip_modifiers",
      "external": true,
      "loc": "kernel/bpf/btf.c:581",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/btf.c:__bpf_core_types_are_compat",
        "kernel/bpf/btf.c:__bpf_core_types_are_compat",
        "kernel/bpf/btf.c:__bpf_core_types_are_compat",
        "kernel/bpf/btf.c:__bpf_core_types_are_compat",
        "kernel/bpf/btf.c:__bpf_core_types_are_compat",
        "kernel/bpf/btf.c:__bpf_core_types_are_compat",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:__btf_type_is_scalar_struct",
        "kernel/bpf/btf.c:__btf_type_is_scalar_struct",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:__btf_array_show",
        "kernel/bpf/btf.c:btf_modifier_show",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr",
        "tools/lib/bpf/relo_core.c:bpf_core_format_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_match_member",
        "tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat",
        "tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668656,
      "name": "btf_type_skip_modifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
const struct btf_type * btf_type_skip_modifiers(const struct btf * btf, u32 id, u32 * res_id)
```

```json
{
  "name": "btf_type_skip_modifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582082503,
      "name": "btf_type_skip_modifiers",
      "external": true,
      "loc": "kernel/bpf/btf.c:576",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_type_match"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:get_kfunc_ptr_arg_type",
        "kernel/bpf/verifier.c:__btf_type_is_scalar_struct",
        "kernel/bpf/verifier.c:__btf_type_is_scalar_struct",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:__btf_array_show",
        "kernel/bpf/btf.c:btf_modifier_show",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_match",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_match",
        "tools/lib/bpf/relo_core.c:bpf_core_format_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_match_member",
        "tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat",
        "tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582062992,
      "name": "btf_type_skip_modifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
const struct btf_type * btf_type_skip_modifiers(const struct btf * btf, u32 id, u32 * res_id)
```

```json
{
  "name": "btf_type_skip_modifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582278808,
      "name": "btf_type_skip_modifiers",
      "external": true,
      "loc": "kernel/bpf/btf.c:599",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_type_match"
      ],
      "caller_func": [
        "kernel/trace/trace_probe.c:type_from_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:process_kf_arg_ptr_to_btf_id",
        "kernel/bpf/verifier.c:get_kfunc_ptr_arg_type",
        "kernel/bpf/verifier.c:__btf_type_is_scalar_struct",
        "kernel/bpf/verifier.c:__btf_type_is_scalar_struct",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:process_iter_arg",
        "kernel/bpf/verifier.c:process_iter_arg",
        "kernel/bpf/btf.c:btf_nested_type_is_trusted",
        "kernel/bpf/btf.c:btf_check_iter_kfuncs",
        "kernel/bpf/btf.c:btf_check_iter_kfuncs",
        "kernel/bpf/btf.c:btf_check_iter_kfuncs",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:__btf_array_show",
        "kernel/bpf/btf.c:btf_modifier_show",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_match",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_match",
        "tools/lib/bpf/relo_core.c:bpf_core_format_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_match_member",
        "tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat",
        "tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582257696,
      "name": "btf_type_skip_modifiers",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct btf_type * btf_type_skip_modifiers(const struct btf * btf, u32 id, u32 * res_id)
```

```json
{
  "name": "btf_type_skip_modifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582417443,
      "name": "btf_type_skip_modifiers",
      "external": true,
      "loc": "kernel/bpf/btf.c:600",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_check_func_type_match"
      ],
      "caller_func": [
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:parse_btf_arg",
        "kernel/trace/trace_btf.c:btf_find_struct_member",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:process_kf_arg_ptr_to_btf_id",
        "kernel/bpf/verifier.c:get_kfunc_ptr_arg_type",
        "kernel/bpf/verifier.c:__btf_type_is_scalar_struct",
        "kernel/bpf/verifier.c:__btf_type_is_scalar_struct",
        "kernel/bpf/verifier.c:process_iter_arg",
        "kernel/bpf/verifier.c:process_iter_arg",
        "kernel/bpf/btf.c:btf_nested_type_is_trusted",
        "kernel/bpf/btf.c:btf_check_iter_kfuncs",
        "kernel/bpf/btf.c:btf_check_iter_kfuncs",
        "kernel/bpf/btf.c:btf_check_iter_kfuncs",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:__btf_array_show",
        "kernel/bpf/btf.c:btf_modifier_show",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_match",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_match",
        "tools/lib/bpf/relo_core.c:bpf_core_format_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_match_member",
        "tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat",
        "tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582414656,
      "name": "btf_type_skip_modifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
const struct btf_type * btf_type_skip_modifiers(const struct btf * btf, u32 id, u32 * res_id)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
