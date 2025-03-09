# Function: <code>btf_name_by_offset</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_name_by_offset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580710525,
      "name": "btf_name_by_offset",
      "external": false,
      "loc": "kernel/bpf/btf.c:429",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_enum_seq_show",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
const char * btf_name_by_offset(const struct btf * btf, u32 offset)
```

```json
{
  "name": "btf_name_by_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580790976,
      "name": "btf_name_by_offset",
      "external": true,
      "loc": "kernel/bpf/btf.c:510",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:verbose_linfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580790976,
      "name": "btf_name_by_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
const char * btf_name_by_offset(const struct btf * btf, u32 offset)
```

```json
{
  "name": "btf_name_by_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580878464,
      "name": "btf_name_by_offset",
      "external": true,
      "loc": "kernel/bpf/btf.c:584",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:verbose_linfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878464,
      "name": "btf_name_by_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
const char * btf_name_by_offset(const struct btf * btf, u32 offset)
```

```json
{
  "name": "btf_name_by_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580929424,
      "name": "btf_name_by_offset",
      "external": true,
      "loc": "kernel/bpf/btf.c:584",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:verbose_linfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580929424,
      "name": "btf_name_by_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * btf_name_by_offset(const struct btf * btf, u32 offset)
```

```json
{
  "name": "btf_name_by_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581096503,
      "name": "btf_name_by_offset",
      "external": true,
      "loc": "kernel/bpf/btf.c:599",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_find_by_name_kind"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_ksym_set_name",
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/verifier.c:check_struct_ops_btf_id",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581085552,
      "name": "btf_name_by_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
const char * btf_name_by_offset(const struct btf * btf, u32 offset)
```

```json
{
  "name": "btf_name_by_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581123413,
      "name": "btf_name_by_offset",
      "external": true,
      "loc": "kernel/bpf/btf.c:702",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_find_by_name_kind"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_ksym_set_name",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:check_struct_ops_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581110784,
      "name": "btf_name_by_offset",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * btf_name_by_offset(const struct btf * btf, u32 offset)
```

```json
{
  "name": "btf_name_by_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581143987,
      "name": "btf_name_by_offset",
      "external": true,
      "loc": "kernel/bpf/btf.c:704",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_find_by_name_kind"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:check_struct_ops_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581129376,
      "name": "btf_name_by_offset",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * btf_name_by_offset(const struct btf * btf, u32 offset)
```

```json
{
  "name": "btf_name_by_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581377283,
      "name": "btf_name_by_offset",
      "external": true,
      "loc": "kernel/bpf/btf.c:704",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_find_by_name_kind"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:check_struct_ops_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361360,
      "name": "btf_name_by_offset",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * btf_name_by_offset(const struct btf * btf, u32 offset)
```

```json
{
  "name": "btf_name_by_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581700093,
      "name": "btf_name_by_offset",
      "external": true,
      "loc": "kernel/bpf/btf.c:799",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:bpf_core_add_cands",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_find_by_name_kind"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:check_struct_ops_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_format_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_format_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_match_member",
        "tools/lib/bpf/relo_core.c:bpf_core_match_member",
        "tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat",
        "tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581675552,
      "name": "btf_name_by_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
const char * btf_name_by_offset(const struct btf * btf, u32 offset)
```

```json
{
  "name": "btf_name_by_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582101517,
      "name": "btf_name_by_offset",
      "external": true,
      "loc": "kernel/bpf/btf.c:800",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:bpf_core_add_cands",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_find_by_name_kind"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:check_struct_ops_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:process_kf_arg_ptr_to_list_node",
        "kernel/bpf/verifier.c:process_kf_arg_ptr_to_list_node",
        "kernel/bpf/verifier.c:process_kf_arg_ptr_to_list_node",
        "kernel/bpf/verifier.c:get_kfunc_ptr_arg_type",
        "kernel/bpf/verifier.c:is_kfunc_arg_scalar_with_name",
        "kernel/bpf/verifier.c:__kfunc_param_match_suffix",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "tools/lib/bpf/relo_core.c:bpf_core_names_match",
        "tools/lib/bpf/relo_core.c:bpf_core_names_match",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_format_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_format_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_format_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_match_member",
        "tools/lib/bpf/relo_core.c:bpf_core_match_member",
        "tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat",
        "tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582069888,
      "name": "btf_name_by_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
const char * btf_name_by_offset(const struct btf * btf, u32 offset)
```

```json
{
  "name": "btf_name_by_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582298284,
      "name": "btf_name_by_offset",
      "external": true,
      "loc": "kernel/bpf/btf.c:819",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_type_ids_nocast_alias",
        "kernel/bpf/btf.c:btf_type_ids_nocast_alias",
        "kernel/bpf/btf.c:btf_nested_type_is_trusted",
        "kernel/bpf/btf.c:bpf_core_add_cands",
        "kernel/bpf/btf.c:__register_btf_kfunc_id_set",
        "kernel/bpf/btf.c:btf_check_iter_kfuncs",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_find_by_name_kind"
      ],
      "caller_func": [
        "kernel/trace/trace_probe.c:sprint_nth_btf_arg",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:check_struct_ops_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:fetch_kfunc_meta",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node",
        "kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node",
        "kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node",
        "kernel/bpf/verifier.c:process_kf_arg_ptr_to_btf_id",
        "kernel/bpf/verifier.c:is_kfunc_arg_scalar_with_name",
        "kernel/bpf/verifier.c:__kfunc_param_match_suffix",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:process_iter_arg",
        "kernel/bpf/verifier.c:process_iter_arg",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "tools/lib/bpf/relo_core.c:bpf_core_names_match",
        "tools/lib/bpf/relo_core.c:bpf_core_names_match",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_format_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_format_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_format_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_match_member",
        "tools/lib/bpf/relo_core.c:bpf_core_match_member",
        "tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat",
        "tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582265680,
      "name": "btf_name_by_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
const char * btf_name_by_offset(const struct btf * btf, u32 offset)
```

```json
{
  "name": "btf_name_by_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582455948,
      "name": "btf_name_by_offset",
      "external": true,
      "loc": "kernel/bpf/btf.c:820",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_type_ids_nocast_alias",
        "kernel/bpf/btf.c:btf_type_ids_nocast_alias",
        "kernel/bpf/btf.c:btf_nested_type_is_trusted",
        "kernel/bpf/btf.c:bpf_core_add_cands",
        "kernel/bpf/btf.c:__register_btf_kfunc_id_set",
        "kernel/bpf/btf.c:btf_check_iter_kfuncs",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_validate_prog_ctx_type",
        "kernel/bpf/btf.c:btf_validate_prog_ctx_type",
        "kernel/bpf/btf.c:btf_validate_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_find_by_name_kind"
      ],
      "caller_func": [
        "kernel/trace/trace_probe.c:sprint_nth_btf_arg",
        "kernel/trace/trace_probe.c:parse_btf_arg",
        "kernel/trace/trace_btf.c:btf_find_struct_member",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:check_struct_ops_btf_id",
        "kernel/bpf/verifier.c:do_check_subprogs",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:fetch_kfunc_meta",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node",
        "kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node",
        "kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node",
        "kernel/bpf/verifier.c:process_kf_arg_ptr_to_btf_id",
        "kernel/bpf/verifier.c:is_kfunc_arg_scalar_with_name",
        "kernel/bpf/verifier.c:__kfunc_param_match_suffix",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/log.c:print_verifier_state",
        "kernel/bpf/log.c:print_reg_state",
        "kernel/bpf/log.c:verbose_linfo",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "tools/lib/bpf/relo_core.c:bpf_core_names_match",
        "tools/lib/bpf/relo_core.c:bpf_core_names_match",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_format_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_format_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_format_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_match_member",
        "tools/lib/bpf/relo_core.c:bpf_core_match_member",
        "tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat",
        "tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582421120,
      "name": "btf_name_by_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
const char * btf_name_by_offset(const struct btf * btf, u32 offset)
```

```json
{
  "name": "btf_name_by_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492267984,
      "name": "btf_name_by_offset",
      "external": true,
      "loc": "kernel/bpf/btf.c:584",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:verbose_linfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492267984,
      "name": "btf_name_by_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
const char * btf_name_by_offset(const struct btf * btf, u32 offset)
```

```json
{
  "name": "btf_name_by_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226157476,
      "name": "btf_name_by_offset",
      "external": true,
      "loc": "kernel/bpf/btf.c:584",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:verbose_linfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226157476,
      "name": "btf_name_by_offset",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
const char * btf_name_by_offset(const struct btf * btf, u32 offset)
```

```json
{
  "name": "btf_name_by_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285498032,
      "name": "btf_name_by_offset",
      "external": true,
      "loc": "kernel/bpf/btf.c:584",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:verbose_linfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285498032,
      "name": "btf_name_by_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
const char * btf_name_by_offset(const struct btf * btf, u32 offset)
```

```json
{
  "name": "btf_name_by_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272405548,
      "name": "btf_name_by_offset",
      "external": true,
      "loc": "kernel/bpf/btf.c:584",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:verbose_linfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272405548,
      "name": "btf_name_by_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
const char * btf_name_by_offset(const struct btf * btf, u32 offset)
```

```json
{
  "name": "btf_name_by_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580898224,
      "name": "btf_name_by_offset",
      "external": true,
      "loc": "kernel/bpf/btf.c:584",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:verbose_linfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580898224,
      "name": "btf_name_by_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
const char * btf_name_by_offset(const struct btf * btf, u32 offset)
```

```json
{
  "name": "btf_name_by_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580844288,
      "name": "btf_name_by_offset",
      "external": true,
      "loc": "kernel/bpf/btf.c:584",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:verbose_linfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844288,
      "name": "btf_name_by_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
const char * btf_name_by_offset(const struct btf * btf, u32 offset)
```

```json
{
  "name": "btf_name_by_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580889472,
      "name": "btf_name_by_offset",
      "external": true,
      "loc": "kernel/bpf/btf.c:584",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:verbose_linfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889472,
      "name": "btf_name_by_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
const char * btf_name_by_offset(const struct btf * btf, u32 offset)
```

```json
{
  "name": "btf_name_by_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580948112,
      "name": "btf_name_by_offset",
      "external": true,
      "loc": "kernel/bpf/btf.c:584",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:check_btf_info",
        "kernel/bpf/verifier.c:verbose_linfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580948112,
      "name": "btf_name_by_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
const char * btf_name_by_offset(const struct btf * btf, u32 offset)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
