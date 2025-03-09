# Function: <code>__btf_verifier_log_type</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580707824,
      "name": "__btf_verifier_log_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:493",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_df_resolve",
        "kernel/bpf/btf.c:btf_df_check_member",
        "kernel/bpf/btf.c:btf_verifier_log_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580707824,
      "name": "__btf_verifier_log_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580785056,
      "name": "__btf_verifier_log_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:613",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_type_sec",
        "kernel/bpf/btf.c:btf_parse_type_sec",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_df_resolve",
        "kernel/bpf/btf.c:btf_df_check_kflag_member",
        "kernel/bpf/btf.c:btf_df_check_member",
        "kernel/bpf/btf.c:btf_verifier_log_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580785056,
      "name": "__btf_verifier_log_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
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
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580870432,
      "name": "__btf_verifier_log_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:688",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_df_resolve",
        "kernel/bpf/btf.c:btf_df_check_kflag_member",
        "kernel/bpf/btf.c:btf_df_check_member",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580870432,
      "name": "__btf_verifier_log_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
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
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580921440,
      "name": "__btf_verifier_log_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:688",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_df_resolve",
        "kernel/bpf/btf.c:btf_df_check_kflag_member",
        "kernel/bpf/btf.c:btf_df_check_member",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580921440,
      "name": "__btf_verifier_log_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581077632,
      "name": "__btf_verifier_log_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:703",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_func_check",
        "kernel/bpf/btf.c:btf_func_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_df_resolve",
        "kernel/bpf/btf.c:btf_df_check_kflag_member",
        "kernel/bpf/btf.c:btf_df_check_member",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077632,
      "name": "__btf_verifier_log_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090544,
      "name": "__btf_verifier_log_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:1288",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_func_check",
        "kernel/bpf/btf.c:btf_func_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_df_resolve",
        "kernel/bpf/btf.c:btf_df_check_kflag_member",
        "kernel/bpf/btf.c:btf_df_check_member",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090544,
      "name": "__btf_verifier_log_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581109664,
      "name": "__btf_verifier_log_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:1289",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_df_resolve",
        "kernel/bpf/btf.c:btf_df_check_kflag_member",
        "kernel/bpf/btf.c:btf_df_check_member",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581109664,
      "name": "__btf_verifier_log_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581339872,
      "name": "__btf_verifier_log_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:1289",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_df_resolve",
        "kernel/bpf/btf.c:btf_df_check_kflag_member",
        "kernel/bpf/btf.c:btf_df_check_member",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581339872,
      "name": "__btf_verifier_log_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 718
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
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581649280,
      "name": "__btf_verifier_log_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:1384",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_decl_tag_resolve",
        "kernel/bpf/btf.c:btf_decl_tag_resolve",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_func_resolve",
        "kernel/bpf/btf.c:btf_func_resolve",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_df_resolve",
        "kernel/bpf/btf.c:btf_df_check_kflag_member",
        "kernel/bpf/btf.c:btf_df_check_member",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581649280,
      "name": "__btf_verifier_log_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 769
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
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582041376,
      "name": "__btf_verifier_log_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:1388",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_decl_tag_resolve",
        "kernel/bpf/btf.c:btf_decl_tag_resolve",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_func_resolve",
        "kernel/bpf/btf.c:btf_func_resolve",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_enum64_check_meta",
        "kernel/bpf/btf.c:btf_enum64_check_meta",
        "kernel/bpf/btf.c:btf_enum64_check_meta",
        "kernel/bpf/btf.c:btf_enum64_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_df_resolve",
        "kernel/bpf/btf.c:btf_df_check_kflag_member",
        "kernel/bpf/btf.c:btf_df_check_member",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041376,
      "name": "__btf_verifier_log_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 755
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
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582235696,
      "name": "__btf_verifier_log_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:1407",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_decl_tag_resolve",
        "kernel/bpf/btf.c:btf_decl_tag_resolve",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_func_resolve",
        "kernel/bpf/btf.c:btf_func_resolve",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_enum64_check_meta",
        "kernel/bpf/btf.c:btf_enum64_check_meta",
        "kernel/bpf/btf.c:btf_enum64_check_meta",
        "kernel/bpf/btf.c:btf_enum64_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_df_resolve",
        "kernel/bpf/btf.c:btf_df_check_kflag_member",
        "kernel/bpf/btf.c:btf_df_check_member",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582235696,
      "name": "__btf_verifier_log_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 698
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
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582391792,
      "name": "__btf_verifier_log_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:1408",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_decl_tag_resolve",
        "kernel/bpf/btf.c:btf_decl_tag_resolve",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_decl_tag_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_float_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_func_resolve",
        "kernel/bpf/btf.c:btf_func_resolve",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_func_proto_check_meta",
        "kernel/bpf/btf.c:btf_enum64_check_meta",
        "kernel/bpf/btf.c:btf_enum64_check_meta",
        "kernel/bpf/btf.c:btf_enum64_check_meta",
        "kernel/bpf/btf.c:btf_enum64_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_fwd_check_meta",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_df_resolve",
        "kernel/bpf/btf.c:btf_df_check_kflag_member",
        "kernel/bpf/btf.c:btf_df_check_member",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582391792,
      "name": "__btf_verifier_log_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 698
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
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492257352,
      "name": "__btf_verifier_log_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:688",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_df_resolve",
        "kernel/bpf/btf.c:btf_df_check_kflag_member",
        "kernel/bpf/btf.c:btf_df_check_member",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492257352,
      "name": "__btf_verifier_log_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226150072,
      "name": "__btf_verifier_log_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:688",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_df_resolve",
        "kernel/bpf/btf.c:btf_df_check_kflag_member",
        "kernel/bpf/btf.c:btf_df_check_member",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226150072,
      "name": "__btf_verifier_log_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285486832,
      "name": "__btf_verifier_log_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:688",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_df_resolve",
        "kernel/bpf/btf.c:btf_df_check_kflag_member",
        "kernel/bpf/btf.c:btf_df_check_member",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285486832,
      "name": "__btf_verifier_log_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272397852,
      "name": "__btf_verifier_log_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:688",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_df_resolve",
        "kernel/bpf/btf.c:btf_df_check_kflag_member",
        "kernel/bpf/btf.c:btf_df_check_member",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272397852,
      "name": "__btf_verifier_log_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580890240,
      "name": "__btf_verifier_log_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:688",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_df_resolve",
        "kernel/bpf/btf.c:btf_df_check_kflag_member",
        "kernel/bpf/btf.c:btf_df_check_member",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580890240,
      "name": "__btf_verifier_log_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
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
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580836304,
      "name": "__btf_verifier_log_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:688",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_df_resolve",
        "kernel/bpf/btf.c:btf_df_check_kflag_member",
        "kernel/bpf/btf.c:btf_df_check_member",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580836304,
      "name": "__btf_verifier_log_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
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
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580881488,
      "name": "__btf_verifier_log_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:688",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_df_resolve",
        "kernel/bpf/btf.c:btf_df_check_kflag_member",
        "kernel/bpf/btf.c:btf_df_check_member",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881488,
      "name": "__btf_verifier_log_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
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
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```

```json
{
  "name": "__btf_verifier_log_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580940128,
      "name": "__btf_verifier_log_type",
      "external": false,
      "loc": "kernel/bpf/btf.c:688",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_datasec_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_var_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_enum_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_struct_check_meta",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_array_check_meta",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_ref_type_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_int_check_meta",
        "kernel/bpf/btf.c:btf_df_resolve",
        "kernel/bpf/btf.c:btf_df_check_kflag_member",
        "kernel/bpf/btf.c:btf_df_check_member",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580940128,
      "name": "__btf_verifier_log_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env * env, const struct btf_type * t, bool log_details, const char * fmt, void (anon))
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
