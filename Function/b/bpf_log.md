# Function: <code>bpf_log</code>

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
void bpf_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "bpf_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581008128,
      "name": "bpf_log",
      "external": true,
      "loc": "kernel/bpf/verifier.c:334",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
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
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_resolve_helper_id",
        "kernel/bpf/btf.c:__btf_resolve_helper_id",
        "kernel/bpf/btf.c:__btf_resolve_helper_id",
        "kernel/bpf/btf.c:__btf_resolve_helper_id",
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
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581008128,
      "name": "bpf_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void bpf_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "bpf_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581011408,
      "name": "bpf_log",
      "external": true,
      "loc": "kernel/bpf/verifier.c:338",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
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
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_struct_walk",
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
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581011408,
      "name": "bpf_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void bpf_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "bpf_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581018496,
      "name": "bpf_log",
      "external": true,
      "loc": "kernel/bpf/verifier.c:357",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
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
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
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
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_struct_walk",
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
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581018496,
      "name": "bpf_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void bpf_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "bpf_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237888,
      "name": "bpf_log",
      "external": true,
      "loc": "kernel/bpf/verifier.c:358",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
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
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
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
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_struct_walk",
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
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237888,
      "name": "bpf_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void bpf_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "bpf_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581531952,
      "name": "bpf_log",
      "external": true,
      "loc": "kernel/bpf/verifier.c:361",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
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
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:btf_check_func_arg_match",
        "kernel/bpf/btf.c:__btf_type_is_scalar_struct",
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
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_struct_walk",
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
        "kernel/bpf/btf.c:btf_ctx_access",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581531952,
      "name": "bpf_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void bpf_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "bpf_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581810576,
      "name": "bpf_log",
      "external": true,
      "loc": "kernel/bpf/verifier.c:362",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
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
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_walk",
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
        "kernel/bpf/btf.c:get_kern_ctx_btf_id",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_match",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581810576,
      "name": "bpf_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void bpf_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "bpf_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582132224,
      "name": "bpf_log",
      "external": true,
      "loc": "kernel/bpf/log.c:315",
      "file": "kernel/bpf/log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
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
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_walk",
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
        "kernel/bpf/btf.c:get_kern_ctx_btf_id",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/offload.c:bpf_dev_bound_kfunc_check",
        "kernel/bpf/offload.c:bpf_dev_bound_kfunc_check",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_match",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582132224,
      "name": "bpf_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void bpf_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
```

```json
{
  "name": "bpf_log",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582274928,
      "name": "bpf_log",
      "external": true,
      "loc": "kernel/bpf/log.c:317",
      "file": "kernel/bpf/log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
        "kernel/bpf/btf.c:btf_prepare_func_args",
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
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_check_func_type_match",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_distill_func_proto",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_struct_walk",
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
        "kernel/bpf/btf.c:get_kern_ctx_btf_id",
        "kernel/bpf/btf.c:btf_validate_prog_ctx_type",
        "kernel/bpf/btf.c:btf_validate_prog_ctx_type",
        "kernel/bpf/btf.c:btf_validate_prog_ctx_type",
        "kernel/bpf/btf.c:btf_validate_prog_ctx_type",
        "kernel/bpf/btf.c:btf_validate_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/btf.c:btf_get_prog_ctx_type",
        "kernel/bpf/offload.c:bpf_dev_bound_kfunc_check",
        "kernel/bpf/offload.c:bpf_dev_bound_kfunc_check",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_match",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_patch_insn",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_parse_spec",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582274928,
      "name": "bpf_log",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void bpf_log(struct bpf_verifier_log * log, const char * fmt, void (anon))
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
