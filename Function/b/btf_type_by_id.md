# Function: <code>btf_type_by_id</code>

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
  "name": "btf_type_by_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580717192,
      "name": "btf_type_by_id",
      "external": false,
      "loc": "kernel/bpf/btf.c:439",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_type_seq_show",
        "kernel/bpf/btf.c:btf_struct_seq_show",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_modifier_seq_show",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct btf_type * btf_type_by_id(const struct btf * btf, u32 type_id)
```

```json
{
  "name": "btf_type_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580796421,
      "name": "btf_type_by_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:518",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_type_seq_show",
        "kernel/bpf/btf.c:btf_parse_type_sec",
        "kernel/bpf/btf.c:btf_parse_type_sec",
        "kernel/bpf/btf.c:btf_parse_type_sec",
        "kernel/bpf/btf.c:btf_parse_type_sec",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_struct_seq_show",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_modifier_seq_show",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580791008,
      "name": "btf_type_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct btf_type * btf_type_by_id(const struct btf * btf, u32 type_id)
```

```json
{
  "name": "btf_type_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580884325,
      "name": "btf_type_by_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:592",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_type_seq_show",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_seq_show",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_seq_show",
        "kernel/bpf/btf.c:btf_find_spin_lock",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_var_seq_show",
        "kernel/bpf/btf.c:btf_modifier_seq_show",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/verifier.c:check_btf_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878496,
      "name": "btf_type_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct btf_type * btf_type_by_id(const struct btf * btf, u32 type_id)
```

```json
{
  "name": "btf_type_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580935285,
      "name": "btf_type_by_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:592",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_type_seq_show",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_seq_show",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_seq_show",
        "kernel/bpf/btf.c:btf_find_spin_lock",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_var_seq_show",
        "kernel/bpf/btf.c:btf_modifier_seq_show",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/verifier.c:check_btf_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580929456,
      "name": "btf_type_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
const struct btf_type * btf_type_by_id(const struct btf * btf, u32 type_id)
```

```json
{
  "name": "btf_type_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581097317,
      "name": "btf_type_by_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:607",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_type_seq_show",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:__btf_resolve_helper_id",
        "kernel/bpf/btf.c:__btf_resolve_helper_id",
        "kernel/bpf/btf.c:__btf_resolve_helper_id",
        "kernel/bpf/btf.c:__btf_resolve_helper_id",
        "kernel/bpf/btf.c:__btf_resolve_helper_id",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_func_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_seq_show",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_seq_show",
        "kernel/bpf/btf.c:btf_find_spin_lock",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_var_seq_show",
        "kernel/bpf/btf.c:btf_modifier_seq_show",
        "kernel/bpf/btf.c:btf_modifier_seq_show",
        "kernel/bpf/btf.c:btf_modifier_seq_show",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_resolve_size",
        "kernel/bpf/btf.c:btf_resolve_size",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_ksym_set_name",
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581085584,
      "name": "btf_type_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
const struct btf_type * btf_type_by_id(const struct btf * btf, u32 type_id)
```

```json
{
  "name": "btf_type_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581094053,
      "name": "btf_type_by_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:707",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_type_show",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve_valid",
        "kernel/bpf/btf.c:btf_func_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_find_spin_lock",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_var_show",
        "kernel/bpf/btf.c:btf_modifier_show",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:__btf_resolve_size",
        "kernel/bpf/btf.c:__btf_resolve_size",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr",
        "kernel/bpf/btf.c:btf_find_by_name_kind"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_snprintf_btf",
        "kernel/trace/bpf_trace.c:bpf_seq_printf_btf",
        "kernel/bpf/core.c:bpf_prog_ksym_set_name",
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581110832,
      "name": "btf_type_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
const struct btf_type * btf_type_by_id(const struct btf * btf, u32 type_id)
```

```json
{
  "name": "btf_type_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581113125,
      "name": "btf_type_by_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:709",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_type_show",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve_valid",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_find_spin_lock",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_var_show",
        "kernel/bpf/btf.c:btf_modifier_show",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:__btf_resolve_size",
        "kernel/bpf/btf.c:__btf_resolve_size",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr",
        "kernel/bpf/btf.c:btf_find_by_name_kind"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_snprintf_btf",
        "kernel/trace/bpf_trace.c:bpf_seq_printf_btf",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581129424,
      "name": "btf_type_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
const struct btf_type * btf_type_by_id(const struct btf * btf, u32 type_id)
```

```json
{
  "name": "btf_type_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581343525,
      "name": "btf_type_by_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:709",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_type_show",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve_valid",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_find_field",
        "kernel/bpf/btf.c:btf_find_field",
        "kernel/bpf/btf.c:btf_find_field",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_var_show",
        "kernel/bpf/btf.c:btf_modifier_show",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:__btf_resolve_size",
        "kernel/bpf/btf.c:__btf_resolve_size",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr",
        "kernel/bpf/btf.c:btf_type_resolve_func_ptr",
        "kernel/bpf/btf.c:btf_find_by_name_kind"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_snprintf_btf",
        "kernel/trace/bpf_trace.c:bpf_seq_printf_btf",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361408,
      "name": "btf_type_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
const struct btf_type * btf_type_by_id(const struct btf * btf, u32 type_id)
```

```json
{
  "name": "btf_type_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581699986,
      "name": "btf_type_by_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:804",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:bpf_core_add_cands",
        "kernel/bpf/btf.c:__bpf_core_types_are_compat",
        "kernel/bpf/btf.c:__bpf_core_types_are_compat",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:btf_type_show",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_check_type_tags",
        "kernel/bpf/btf.c:btf_check_type_tags",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_decl_tag_resolve",
        "kernel/bpf/btf.c:btf_decl_tag_resolve",
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_func_resolve",
        "kernel/bpf/btf.c:btf_parse_kptrs",
        "kernel/bpf/btf.c:btf_parse_kptrs",
        "kernel/bpf/btf.c:btf_find_field",
        "kernel/bpf/btf.c:btf_find_field",
        "kernel/bpf/btf.c:btf_find_field",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_var_show",
        "kernel/bpf/btf.c:btf_modifier_show",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:__btf_resolve_size",
        "kernel/bpf/btf.c:__btf_resolve_size",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_type_skip_modifiers",
        "kernel/bpf/btf.c:btf_type_skip_modifiers",
        "kernel/bpf/btf.c:btf_find_by_name_kind"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_snprintf_btf",
        "kernel/trace/bpf_trace.c:bpf_seq_printf_btf",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_format_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_match_member",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581675616,
      "name": "btf_type_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
const struct btf_type * btf_type_by_id(const struct btf * btf, u32 type_id)
```

```json
{
  "name": "btf_type_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582101410,
      "name": "btf_type_by_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:805",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:bpf_core_add_cands",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:btf_type_snprintf_show",
        "kernel/bpf/btf.c:btf_type_seq_show_flags",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/btf.c:get_kern_ctx_btf_id",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_check_type_tags",
        "kernel/bpf/btf.c:btf_check_type_tags",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_decl_tag_resolve",
        "kernel/bpf/btf.c:btf_decl_tag_resolve",
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_func_resolve",
        "kernel/bpf/btf.c:btf_parse_fields",
        "kernel/bpf/btf.c:btf_parse_fields",
        "kernel/bpf/btf.c:btf_parse_fields",
        "kernel/bpf/btf.c:btf_parse_fields",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_var_show",
        "kernel/bpf/btf.c:btf_modifier_show",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:__btf_resolve_size",
        "kernel/bpf/btf.c:__btf_resolve_size",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_find_by_name_kind"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_snprintf_btf",
        "kernel/trace/bpf_trace.c:bpf_seq_printf_btf",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:process_kf_arg_ptr_to_list_node",
        "kernel/bpf/verifier.c:process_kf_arg_ptr_to_list_node",
        "kernel/bpf/verifier.c:get_kfunc_ptr_arg_type",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_match",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_match",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_format_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_type_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_match_member",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582031232,
      "name": "btf_type_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
const struct btf_type * btf_type_by_id(const struct btf * btf, u32 type_id)
```

```json
{
  "name": "btf_type_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582298149,
      "name": "btf_type_by_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:824",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_type_ids_nocast_alias",
        "kernel/bpf/btf.c:btf_type_ids_nocast_alias",
        "kernel/bpf/btf.c:btf_nested_type_is_trusted",
        "kernel/bpf/btf.c:btf_nested_type_is_trusted",
        "kernel/bpf/btf.c:btf_nested_type_is_trusted",
        "kernel/bpf/btf.c:bpf_core_add_cands",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:__register_btf_kfunc_id_set",
        "kernel/bpf/btf.c:__register_btf_kfunc_id_set",
        "kernel/bpf/btf.c:btf_check_iter_kfuncs",
        "kernel/bpf/btf.c:btf_type_show",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/btf.c:get_kern_ctx_btf_id",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_check_type_tags",
        "kernel/bpf/btf.c:btf_check_type_tags",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_decl_tag_resolve",
        "kernel/bpf/btf.c:btf_decl_tag_resolve",
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_func_resolve",
        "kernel/bpf/btf.c:btf_parse_kptr",
        "kernel/bpf/btf.c:btf_parse_kptr",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_var_show",
        "kernel/bpf/btf.c:btf_modifier_show",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:__btf_resolve_size",
        "kernel/bpf/btf.c:__btf_resolve_size",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_find_by_name_kind"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_snprintf_btf",
        "kernel/trace/bpf_trace.c:bpf_seq_printf_btf",
        "kernel/trace/trace_probe.c:find_btf_func_proto",
        "kernel/trace/trace_probe.c:find_btf_func_proto",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:fetch_kfunc_meta",
        "kernel/bpf/verifier.c:fetch_kfunc_meta",
        "kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node",
        "kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node",
        "kernel/bpf/verifier.c:process_iter_arg",
        "kernel/bpf/verifier.c:process_iter_arg",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_format_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_type_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_match_member",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582223296,
      "name": "btf_type_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
const struct btf_type * btf_type_by_id(const struct btf * btf, u32 type_id)
```

```json
{
  "name": "btf_type_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582455813,
      "name": "btf_type_by_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:825",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_type_ids_nocast_alias",
        "kernel/bpf/btf.c:btf_type_ids_nocast_alias",
        "kernel/bpf/btf.c:btf_nested_type_is_trusted",
        "kernel/bpf/btf.c:btf_nested_type_is_trusted",
        "kernel/bpf/btf.c:btf_nested_type_is_trusted",
        "kernel/bpf/btf.c:bpf_core_add_cands",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:__register_btf_kfunc_id_set",
        "kernel/bpf/btf.c:__register_btf_kfunc_id_set",
        "kernel/bpf/btf.c:btf_check_iter_kfuncs",
        "kernel/bpf/btf.c:btf_type_show",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_check_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_ids_match",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_struct_walk",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/btf.c:get_kern_ctx_btf_id",
        "kernel/bpf/btf.c:btf_validate_prog_ctx_type",
        "kernel/bpf/btf.c:btf_validate_prog_ctx_type",
        "kernel/bpf/btf.c:btf_validate_prog_ctx_type",
        "kernel/bpf/btf.c:btf_validate_prog_ctx_type",
        "kernel/bpf/btf.c:btf_validate_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_check_type_tags",
        "kernel/bpf/btf.c:btf_check_type_tags",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_decl_tag_resolve",
        "kernel/bpf/btf.c:btf_decl_tag_resolve",
        "kernel/bpf/btf.c:btf_datasec_show",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_func_resolve",
        "kernel/bpf/btf.c:btf_parse_kptr",
        "kernel/bpf/btf.c:btf_parse_kptr",
        "kernel/bpf/btf.c:btf_find_decl_tag_value",
        "kernel/bpf/btf.c:btf_find_decl_tag_value",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_var_show",
        "kernel/bpf/btf.c:btf_modifier_show",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:__btf_resolve_size",
        "kernel/bpf/btf.c:__btf_resolve_size",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_show_name",
        "kernel/bpf/btf.c:btf_find_by_name_kind"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_snprintf_btf",
        "kernel/trace/bpf_trace.c:bpf_seq_printf_btf",
        "kernel/trace/trace_btf.c:btf_find_struct_member",
        "kernel/trace/trace_btf.c:btf_find_func_proto",
        "kernel/trace/trace_btf.c:btf_find_func_proto",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:do_check_subprogs",
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:fetch_kfunc_meta",
        "kernel/bpf/verifier.c:fetch_kfunc_meta",
        "kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node",
        "kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node",
        "kernel/bpf/verifier.c:check_ptr_to_map_access",
        "kernel/bpf/verifier.c:check_ptr_to_btf_access",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:bpf_find_exception_callback_insn_off",
        "kernel/bpf/verifier.c:bpf_find_exception_callback_insn_off",
        "kernel/bpf/log.c:print_verifier_state",
        "kernel/bpf/log.c:print_reg_state",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_format_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_type_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_spec_match",
        "tools/lib/bpf/relo_core.c:bpf_core_match_member",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582379248,
      "name": "btf_type_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
const struct btf_type * btf_type_by_id(const struct btf * btf, u32 type_id)
```

```json
{
  "name": "btf_type_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492274848,
      "name": "btf_type_by_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:592",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_type_seq_show",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_seq_show",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_seq_show",
        "kernel/bpf/btf.c:btf_find_spin_lock",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_modifier_seq_show",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/verifier.c:check_btf_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492268064,
      "name": "btf_type_by_id",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
const struct btf_type * btf_type_by_id(const struct btf * btf, u32 type_id)
```

```json
{
  "name": "btf_type_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226163860,
      "name": "btf_type_by_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:592",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_type_seq_show",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_seq_show",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_seq_show",
        "kernel/bpf/btf.c:btf_find_spin_lock",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_modifier_seq_show",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/verifier.c:check_btf_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226157520,
      "name": "btf_type_by_id",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
const struct btf_type * btf_type_by_id(const struct btf * btf, u32 type_id)
```

```json
{
  "name": "btf_type_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285506572,
      "name": "btf_type_by_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:592",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_type_seq_show",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_seq_show",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_seq_show",
        "kernel/bpf/btf.c:btf_find_spin_lock",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_var_seq_show",
        "kernel/bpf/btf.c:btf_modifier_seq_show",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/verifier.c:check_btf_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285498080,
      "name": "btf_type_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
const struct btf_type * btf_type_by_id(const struct btf * btf, u32 type_id)
```

```json
{
  "name": "btf_type_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272410810,
      "name": "btf_type_by_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:592",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_type_seq_show",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_seq_show",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_seq_show",
        "kernel/bpf/btf.c:btf_find_spin_lock",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_modifier_seq_show",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/verifier.c:check_btf_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272405606,
      "name": "btf_type_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
const struct btf_type * btf_type_by_id(const struct btf * btf, u32 type_id)
```

```json
{
  "name": "btf_type_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580904085,
      "name": "btf_type_by_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:592",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_type_seq_show",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_seq_show",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_seq_show",
        "kernel/bpf/btf.c:btf_find_spin_lock",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_var_seq_show",
        "kernel/bpf/btf.c:btf_modifier_seq_show",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/verifier.c:check_btf_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580898256,
      "name": "btf_type_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
const struct btf_type * btf_type_by_id(const struct btf * btf, u32 type_id)
```

```json
{
  "name": "btf_type_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580850149,
      "name": "btf_type_by_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:592",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_type_seq_show",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_seq_show",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_seq_show",
        "kernel/bpf/btf.c:btf_find_spin_lock",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_var_seq_show",
        "kernel/bpf/btf.c:btf_modifier_seq_show",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/verifier.c:check_btf_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844320,
      "name": "btf_type_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
const struct btf_type * btf_type_by_id(const struct btf * btf, u32 type_id)
```

```json
{
  "name": "btf_type_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580895333,
      "name": "btf_type_by_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:592",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_type_seq_show",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_seq_show",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_seq_show",
        "kernel/bpf/btf.c:btf_find_spin_lock",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_var_seq_show",
        "kernel/bpf/btf.c:btf_modifier_seq_show",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/verifier.c:check_btf_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889504,
      "name": "btf_type_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
const struct btf_type * btf_type_by_id(const struct btf * btf, u32 type_id)
```

```json
{
  "name": "btf_type_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580953973,
      "name": "btf_type_by_id",
      "external": true,
      "loc": "kernel/bpf/btf.c:592",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_type_seq_show",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_seq_show",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_struct_seq_show",
        "kernel/bpf/btf.c:btf_find_spin_lock",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_struct_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_var_seq_show",
        "kernel/bpf/btf.c:btf_modifier_seq_show",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_type_id_size",
        "kernel/bpf/btf.c:btf_type_id_size"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/verifier.c:check_btf_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580948144,
      "name": "btf_type_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
const struct btf_type * btf_type_by_id(const struct btf * btf, u32 type_id)
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
