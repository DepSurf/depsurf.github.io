# Function: <code>bpf_prog_has_trampoline</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool bpf_prog_has_trampoline(const struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_has_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581636000,
      "name": "bpf_prog_has_trampoline",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:30",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581636000,
      "name": "bpf_prog_has_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
bool bpf_prog_has_trampoline(const struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_has_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582025760,
      "name": "bpf_prog_has_trampoline",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:108",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582025760,
      "name": "bpf_prog_has_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
bool bpf_prog_has_trampoline(const struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_has_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582218048,
      "name": "bpf_prog_has_trampoline",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:107",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218048,
      "name": "bpf_prog_has_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
bool bpf_prog_has_trampoline(const struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_has_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582373248,
      "name": "bpf_prog_has_trampoline",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:107",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/trace/bpf_trace.c:tracing_prog_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582373248,
      "name": "bpf_prog_has_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool bpf_prog_has_trampoline(const struct bpf_prog * prog)
```
</details>
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
