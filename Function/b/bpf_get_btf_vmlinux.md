# Function: <code>bpf_get_btf_vmlinux</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct btf * bpf_get_btf_vmlinux()
```

```json
{
  "name": "bpf_get_btf_vmlinux",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581026411,
      "name": "bpf_get_btf_vmlinux",
      "external": true,
      "loc": "kernel/bpf/verifier.c:11947",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_snprintf_btf",
        "kernel/trace/bpf_trace.c:bpf_seq_printf_btf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/btf.c:btf_parse_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581026128,
      "name": "bpf_get_btf_vmlinux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct btf * bpf_get_btf_vmlinux()
```

```json
{
  "name": "bpf_get_btf_vmlinux",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581036742,
      "name": "bpf_get_btf_vmlinux",
      "external": true,
      "loc": "kernel/bpf/verifier.c:13272",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_snprintf_btf",
        "kernel/trace/bpf_trace.c:bpf_seq_printf_btf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/btf.c:btf_parse_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581036448,
      "name": "bpf_get_btf_vmlinux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct btf * bpf_get_btf_vmlinux()
```

```json
{
  "name": "bpf_get_btf_vmlinux",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581259946,
      "name": "bpf_get_btf_vmlinux",
      "external": true,
      "loc": "kernel/bpf/verifier.c:13716",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_snprintf_btf",
        "kernel/trace/bpf_trace.c:bpf_seq_printf_btf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/btf.c:bpf_btf_find_by_name_kind",
        "kernel/bpf/btf.c:btf_parse_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581259600,
      "name": "bpf_get_btf_vmlinux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct btf * bpf_get_btf_vmlinux()
```

```json
{
  "name": "bpf_get_btf_vmlinux",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581550620,
      "name": "bpf_get_btf_vmlinux",
      "external": true,
      "loc": "kernel/bpf/verifier.c:14880",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_snprintf_btf",
        "kernel/trace/bpf_trace.c:bpf_seq_printf_btf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/btf.c:btf_parse_module",
        "kernel/bpf/btf.c:bpf_find_btf_id",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581550256,
      "name": "bpf_get_btf_vmlinux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
struct btf * bpf_get_btf_vmlinux()
```

```json
{
  "name": "bpf_get_btf_vmlinux",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581922260,
      "name": "bpf_get_btf_vmlinux",
      "external": true,
      "loc": "kernel/bpf/verifier.c:17051",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_snprintf_btf",
        "kernel/trace/bpf_trace.c:bpf_seq_printf_btf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/btf.c:btf_parse_module",
        "kernel/bpf/btf.c:bpf_find_btf_id",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581921872,
      "name": "bpf_get_btf_vmlinux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
struct btf * bpf_get_btf_vmlinux()
```

```json
{
  "name": "bpf_get_btf_vmlinux",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582105021,
      "name": "bpf_get_btf_vmlinux",
      "external": true,
      "loc": "kernel/bpf/verifier.c:19382",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_snprintf_btf",
        "kernel/trace/bpf_trace.c:bpf_seq_printf_btf",
        "kernel/trace/trace_probe.c:sprint_nth_btf_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:find_btf_func_proto",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/btf.c:btf_parse_module",
        "kernel/bpf/btf.c:bpf_find_btf_id",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582104608,
      "name": "bpf_get_btf_vmlinux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
struct btf * bpf_get_btf_vmlinux()
```

```json
{
  "name": "bpf_get_btf_vmlinux",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582245208,
      "name": "bpf_get_btf_vmlinux",
      "external": true,
      "loc": "kernel/bpf/verifier.c:20729",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_snprintf_btf",
        "kernel/trace/bpf_trace.c:bpf_seq_printf_btf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/btf.c:btf_parse_module",
        "kernel/bpf/btf.c:bpf_find_btf_id",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582244800,
      "name": "bpf_get_btf_vmlinux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
struct btf * bpf_get_btf_vmlinux()
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
