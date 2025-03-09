# Function: <code>btf_find_by_name_kind</code>

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
s32 btf_find_by_name_kind(const struct btf * btf, const char * name, u8 kind)
```

```json
{
  "name": "btf_find_by_name_kind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581085072,
      "name": "btf_find_by_name_kind",
      "external": true,
      "loc": "kernel/bpf/btf.c:385",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581085072,
      "name": "btf_find_by_name_kind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
s32 btf_find_by_name_kind(const struct btf * btf, const char * name, u8 kind)
```

```json
{
  "name": "btf_find_by_name_kind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581106000,
      "name": "btf_find_by_name_kind",
      "external": true,
      "loc": "kernel/bpf/btf.c:473",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_pseudo_btf_id",
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581106000,
      "name": "btf_find_by_name_kind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
s32 btf_find_by_name_kind(const struct btf * btf, const char * name, u8 kind)
```

```json
{
  "name": "btf_find_by_name_kind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581125216,
      "name": "btf_find_by_name_kind",
      "external": true,
      "loc": "kernel/bpf/btf.c:474",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125216,
      "name": "btf_find_by_name_kind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
s32 btf_find_by_name_kind(const struct btf * btf, const char * name, u8 kind)
```

```json
{
  "name": "btf_find_by_name_kind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581356992,
      "name": "btf_find_by_name_kind",
      "external": true,
      "loc": "kernel/bpf/btf.c:474",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:bpf_btf_find_by_name_kind",
        "kernel/bpf/btf.c:bpf_btf_find_by_name_kind",
        "kernel/bpf/btf.c:btf_parse_vmlinux",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581356992,
      "name": "btf_find_by_name_kind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
s32 btf_find_by_name_kind(const struct btf * btf, const char * name, u8 kind)
```

```json
{
  "name": "btf_find_by_name_kind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581668368,
      "name": "btf_find_by_name_kind",
      "external": true,
      "loc": "kernel/bpf/btf.c:517",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:bpf_find_btf_id",
        "kernel/bpf/btf.c:bpf_find_btf_id",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668368,
      "name": "btf_find_by_name_kind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
s32 btf_find_by_name_kind(const struct btf * btf, const char * name, u8 kind)
```

```json
{
  "name": "btf_find_by_name_kind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582062112,
      "name": "btf_find_by_name_kind",
      "external": true,
      "loc": "kernel/bpf/btf.c:512",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/btf.c:bpf_find_btf_id",
        "kernel/bpf/btf.c:bpf_find_btf_id",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582062112,
      "name": "btf_find_by_name_kind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
s32 btf_find_by_name_kind(const struct btf * btf, const char * name, u8 kind)
```

```json
{
  "name": "btf_find_by_name_kind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582257152,
      "name": "btf_find_by_name_kind",
      "external": true,
      "loc": "kernel/bpf/btf.c:535",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_probe.c:find_btf_func_proto",
        "kernel/bpf/btf.c:btf_nested_type_is_trusted",
        "kernel/bpf/btf.c:bpf_find_btf_id",
        "kernel/bpf/btf.c:bpf_find_btf_id",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582257152,
      "name": "btf_find_by_name_kind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
s32 btf_find_by_name_kind(const struct btf * btf, const char * name, u8 kind)
```

```json
{
  "name": "btf_find_by_name_kind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582414352,
      "name": "btf_find_by_name_kind",
      "external": true,
      "loc": "kernel/bpf/btf.c:536",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_find_exception_callback_insn_off",
        "kernel/bpf/btf.c:btf_nested_type_is_trusted",
        "kernel/bpf/btf.c:bpf_find_btf_id",
        "kernel/bpf/btf.c:bpf_find_btf_id",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582414352,
      "name": "btf_find_by_name_kind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
s32 btf_find_by_name_kind(const struct btf * btf, const char * name, u8 kind)
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
