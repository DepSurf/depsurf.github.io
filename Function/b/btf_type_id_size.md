# Function: <code>btf_type_id_size</code>

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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
```

```json
{
  "name": "btf_type_id_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580712560,
      "name": "btf_type_id_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:821",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:array_map_check_btf",
        "kernel/bpf/arraymap.c:array_map_check_btf",
        "kernel/bpf/btf.c:btf_new_fd",
        "kernel/bpf/btf.c:btf_array_seq_show",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_member",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_check_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580712560,
      "name": "btf_type_id_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
```

```json
{
  "name": "btf_type_id_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580791184,
      "name": "btf_type_id_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:953",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/btf.c:btf_parse_type_sec",
        "kernel/bpf/btf.c:btf_parse_type_sec",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_array_seq_show",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_member",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_check_kflag_member",
        "kernel/bpf/btf.c:btf_modifier_check_member",
        "kernel/bpf/btf.c:btf_member_is_reg_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580791184,
      "name": "btf_type_id_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
```

```json
{
  "name": "btf_type_id_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580878672,
      "name": "btf_type_id_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1054",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_array_seq_show",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_member",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_check_kflag_member",
        "kernel/bpf/btf.c:btf_modifier_check_member",
        "kernel/bpf/btf.c:btf_member_is_reg_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878672,
      "name": "btf_type_id_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
```

```json
{
  "name": "btf_type_id_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580929632,
      "name": "btf_type_id_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1054",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_array_seq_show",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_member",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_check_kflag_member",
        "kernel/bpf/btf.c:btf_modifier_check_member",
        "kernel/bpf/btf.c:btf_member_is_reg_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580929632,
      "name": "btf_type_id_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
```

```json
{
  "name": "btf_type_id_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581086000,
      "name": "btf_type_id_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1160",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_array_seq_show",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_member",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_check_kflag_member",
        "kernel/bpf/btf.c:btf_modifier_check_member",
        "kernel/bpf/btf.c:btf_member_is_reg_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581086000,
      "name": "btf_type_id_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
```

```json
{
  "name": "btf_type_id_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581111776,
      "name": "btf_type_id_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1789",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/btf.c:btf_resolve_valid",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_member",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_check_kflag_member",
        "kernel/bpf/btf.c:btf_modifier_check_member",
        "kernel/bpf/btf.c:btf_member_is_reg_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581111776,
      "name": "btf_type_id_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
```

```json
{
  "name": "btf_type_id_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581130368,
      "name": "btf_type_id_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1791",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/btf.c:btf_resolve_valid",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_member",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_check_kflag_member",
        "kernel/bpf/btf.c:btf_modifier_check_member",
        "kernel/bpf/btf.c:btf_member_is_reg_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581130368,
      "name": "btf_type_id_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
```

```json
{
  "name": "btf_type_id_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581362816,
      "name": "btf_type_id_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1791",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/btf.c:btf_resolve_valid",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_member",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_check_kflag_member",
        "kernel/bpf/btf.c:btf_modifier_check_member",
        "kernel/bpf/btf.c:btf_member_is_reg_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581362816,
      "name": "btf_type_id_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
```

```json
{
  "name": "btf_type_id_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581678656,
      "name": "btf_type_id_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1920",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/btf.c:btf_resolve_valid",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_member",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_check_kflag_member",
        "kernel/bpf/btf.c:btf_modifier_check_member",
        "kernel/bpf/btf.c:btf_member_is_reg_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581678656,
      "name": "btf_type_id_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 506
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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
```

```json
{
  "name": "btf_type_id_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582073152,
      "name": "btf_type_id_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1944",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/btf.c:btf_resolve_valid",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_member",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_check_kflag_member",
        "kernel/bpf/btf.c:btf_modifier_check_member",
        "kernel/bpf/btf.c:btf_member_is_reg_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582073152,
      "name": "btf_type_id_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 506
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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
```

```json
{
  "name": "btf_type_id_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582269360,
      "name": "btf_type_id_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1974",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/btf.c:btf_resolve_valid",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_member",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_check_kflag_member",
        "kernel/bpf/btf.c:btf_modifier_check_member",
        "kernel/bpf/btf.c:btf_member_is_reg_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269360,
      "name": "btf_type_id_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
```

```json
{
  "name": "btf_type_id_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582424896,
      "name": "btf_type_id_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1975",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/syscall.c:map_check_btf",
        "kernel/bpf/btf.c:btf_resolve_valid",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_func_proto_check",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_member",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_check_kflag_member",
        "kernel/bpf/btf.c:btf_modifier_check_member",
        "kernel/bpf/btf.c:btf_member_is_reg_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582424896,
      "name": "btf_type_id_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
```

```json
{
  "name": "btf_type_id_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492268432,
      "name": "btf_type_id_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1054",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_array_seq_show",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_member",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_check_kflag_member",
        "kernel/bpf/btf.c:btf_modifier_check_member",
        "kernel/bpf/btf.c:btf_member_is_reg_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492268432,
      "name": "btf_type_id_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
```

```json
{
  "name": "btf_type_id_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226157708,
      "name": "btf_type_id_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1054",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_array_seq_show",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_member",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_check_kflag_member",
        "kernel/bpf/btf.c:btf_modifier_check_member",
        "kernel/bpf/btf.c:btf_member_is_reg_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226157708,
      "name": "btf_type_id_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
```

```json
{
  "name": "btf_type_id_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285498432,
      "name": "btf_type_id_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1054",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_array_seq_show",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_member",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_check_kflag_member",
        "kernel/bpf/btf.c:btf_modifier_check_member",
        "kernel/bpf/btf.c:btf_member_is_reg_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285498432,
      "name": "btf_type_id_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
```

```json
{
  "name": "btf_type_id_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272405750,
      "name": "btf_type_id_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1054",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_array_seq_show",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_member",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_check_kflag_member",
        "kernel/bpf/btf.c:btf_modifier_check_member",
        "kernel/bpf/btf.c:btf_member_is_reg_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272405750,
      "name": "btf_type_id_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
```

```json
{
  "name": "btf_type_id_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580898432,
      "name": "btf_type_id_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1054",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_array_seq_show",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_member",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_check_kflag_member",
        "kernel/bpf/btf.c:btf_modifier_check_member",
        "kernel/bpf/btf.c:btf_member_is_reg_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580898432,
      "name": "btf_type_id_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
```

```json
{
  "name": "btf_type_id_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580844496,
      "name": "btf_type_id_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1054",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_array_seq_show",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_member",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_check_kflag_member",
        "kernel/bpf/btf.c:btf_modifier_check_member",
        "kernel/bpf/btf.c:btf_member_is_reg_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844496,
      "name": "btf_type_id_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
```

```json
{
  "name": "btf_type_id_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580889680,
      "name": "btf_type_id_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1054",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_array_seq_show",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_member",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_check_kflag_member",
        "kernel/bpf/btf.c:btf_modifier_check_member",
        "kernel/bpf/btf.c:btf_member_is_reg_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889680,
      "name": "btf_type_id_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
```

```json
{
  "name": "btf_type_id_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580948320,
      "name": "btf_type_id_size",
      "external": true,
      "loc": "kernel/bpf/btf.c:1054",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_check_all_types",
        "kernel/bpf/btf.c:btf_resolve",
        "kernel/bpf/btf.c:btf_datasec_resolve",
        "kernel/bpf/btf.c:btf_array_seq_show",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_resolve",
        "kernel/bpf/btf.c:btf_array_check_member",
        "kernel/bpf/btf.c:btf_ptr_resolve",
        "kernel/bpf/btf.c:btf_var_resolve",
        "kernel/bpf/btf.c:btf_modifier_resolve",
        "kernel/bpf/btf.c:btf_modifier_check_kflag_member",
        "kernel/bpf/btf.c:btf_modifier_check_member",
        "kernel/bpf/btf.c:btf_member_is_reg_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580948320,
      "name": "btf_type_id_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
const struct btf_type * btf_type_id_size(const struct btf * btf, u32 * type_id, u32 * ret_size)
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
