# Function: <code>btf_ctx_access</code>

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
bool btf_ctx_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "btf_ctx_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581092640,
      "name": "btf_ctx_access",
      "external": true,
      "loc": "kernel/bpf/btf.c:3686",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581092640,
      "name": "btf_ctx_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1070
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
bool btf_ctx_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "btf_ctx_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581119616,
      "name": "btf_ctx_access",
      "external": true,
      "loc": "kernel/bpf/btf.c:4582",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581119616,
      "name": "btf_ctx_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1379
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
bool btf_ctx_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "btf_ctx_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581138560,
      "name": "btf_ctx_access",
      "external": true,
      "loc": "kernel/bpf/btf.c:4653",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581138560,
      "name": "btf_ctx_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1380
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool btf_ctx_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "btf_ctx_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_ctx_access",
      "external": true,
      "loc": "kernel/bpf/btf.c:4701",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592187041,
      "name": "btf_ctx_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071581371184,
      "name": "btf_ctx_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1593
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool btf_ctx_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "btf_ctx_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_ctx_access",
      "external": true,
      "loc": "kernel/bpf/btf.c:5219",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:tracing_prog_is_valid_access",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593961559,
      "name": "btf_ctx_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071581687360,
      "name": "btf_ctx_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1941
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool btf_ctx_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "btf_ctx_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_ctx_access",
      "external": true,
      "loc": "kernel/bpf/btf.c:5851",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:tracing_prog_is_valid_access",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596022026,
      "name": "btf_ctx_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071582084272,
      "name": "btf_ctx_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool btf_ctx_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "btf_ctx_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_ctx_access",
      "external": true,
      "loc": "kernel/bpf/btf.c:5925",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:tracing_prog_is_valid_access",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596543936,
      "name": "btf_ctx_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071582280608,
      "name": "btf_ctx_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool btf_ctx_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "btf_ctx_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_ctx_access",
      "external": true,
      "loc": "kernel/bpf/btf.c:6095",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:tracing_prog_is_valid_access",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597447176,
      "name": "btf_ctx_access.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071582437264,
      "name": "btf_ctx_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2279
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
bool btf_ctx_access(int off, int size, enum bpf_access_type type, const struct bpf_prog * prog, struct bpf_insn_access_aux * info)
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
