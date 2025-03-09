# Function: <code>btf_type_resolve_func_ptr</code>

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
const struct btf_type * btf_type_resolve_func_ptr(const struct btf * btf, u32 id, u32 * res_id)
```

```json
{
  "name": "btf_type_resolve_func_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581085424,
      "name": "btf_type_resolve_func_ptr",
      "external": true,
      "loc": "kernel/bpf/btf.c:432",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_struct_ops_btf_id",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581085424,
      "name": "btf_type_resolve_func_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
const struct btf_type * btf_type_resolve_func_ptr(const struct btf * btf, u32 id, u32 * res_id)
```

```json
{
  "name": "btf_type_resolve_func_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581110592,
      "name": "btf_type_resolve_func_ptr",
      "external": true,
      "loc": "kernel/bpf/btf.c:521",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_struct_ops_btf_id",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581110592,
      "name": "btf_type_resolve_func_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
const struct btf_type * btf_type_resolve_func_ptr(const struct btf * btf, u32 id, u32 * res_id)
```

```json
{
  "name": "btf_type_resolve_func_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581129184,
      "name": "btf_type_resolve_func_ptr",
      "external": true,
      "loc": "kernel/bpf/btf.c:522",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_struct_ops_btf_id",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581129184,
      "name": "btf_type_resolve_func_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
const struct btf_type * btf_type_resolve_func_ptr(const struct btf * btf, u32 id, u32 * res_id)
```

```json
{
  "name": "btf_type_resolve_func_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581361168,
      "name": "btf_type_resolve_func_ptr",
      "external": true,
      "loc": "kernel/bpf/btf.c:522",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_struct_ops_btf_id",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361168,
      "name": "btf_type_resolve_func_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
const struct btf_type * btf_type_resolve_func_ptr(const struct btf * btf, u32 id, u32 * res_id)
```

```json
{
  "name": "btf_type_resolve_func_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581675456,
      "name": "btf_type_resolve_func_ptr",
      "external": true,
      "loc": "kernel/bpf/btf.c:609",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_struct_ops_btf_id",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581675456,
      "name": "btf_type_resolve_func_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
const struct btf_type * btf_type_resolve_func_ptr(const struct btf * btf, u32 id, u32 * res_id)
```

```json
{
  "name": "btf_type_resolve_func_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582069776,
      "name": "btf_type_resolve_func_ptr",
      "external": true,
      "loc": "kernel/bpf/btf.c:604",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_struct_ops_btf_id",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582069776,
      "name": "btf_type_resolve_func_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
const struct btf_type * btf_type_resolve_func_ptr(const struct btf * btf, u32 id, u32 * res_id)
```

```json
{
  "name": "btf_type_resolve_func_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582265568,
      "name": "btf_type_resolve_func_ptr",
      "external": true,
      "loc": "kernel/bpf/btf.c:627",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_struct_ops_btf_id",
        "kernel/bpf/verifier.c:get_kfunc_ptr_arg_type",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582265568,
      "name": "btf_type_resolve_func_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
const struct btf_type * btf_type_resolve_func_ptr(const struct btf * btf, u32 id, u32 * res_id)
```

```json
{
  "name": "btf_type_resolve_func_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582421008,
      "name": "btf_type_resolve_func_ptr",
      "external": true,
      "loc": "kernel/bpf/btf.c:628",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_struct_ops_btf_id",
        "kernel/bpf/verifier.c:get_kfunc_ptr_arg_type",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582421008,
      "name": "btf_type_resolve_func_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
const struct btf_type * btf_type_resolve_func_ptr(const struct btf * btf, u32 id, u32 * res_id)
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
