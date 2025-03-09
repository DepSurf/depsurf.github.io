# Function: <code>bpf_tracing_prog_attach</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_tracing_prog_attach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580946690,
      "name": "bpf_tracing_prog_attach",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2530",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int bpf_tracing_prog_attach(struct bpf_prog * prog, int tgt_prog_fd, u32 btf_id)
```

```json
{
  "name": "bpf_tracing_prog_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580943136,
      "name": "bpf_tracing_prog_attach",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2558",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580943136,
      "name": "bpf_tracing_prog_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1196
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
int bpf_tracing_prog_attach(struct bpf_prog * prog, int tgt_prog_fd, u32 btf_id)
```

```json
{
  "name": "bpf_tracing_prog_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580945616,
      "name": "bpf_tracing_prog_attach",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2569",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945616,
      "name": "bpf_tracing_prog_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1317
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
int bpf_tracing_prog_attach(struct bpf_prog * prog, int tgt_prog_fd, u32 btf_id)
```

```json
{
  "name": "bpf_tracing_prog_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581149760,
      "name": "bpf_tracing_prog_attach",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2679",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581149760,
      "name": "bpf_tracing_prog_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1317
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
int bpf_tracing_prog_attach(struct bpf_prog * prog, int tgt_prog_fd, u32 btf_id, u64 bpf_cookie)
```

```json
{
  "name": "bpf_tracing_prog_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581425232,
      "name": "bpf_tracing_prog_attach",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2922",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581425232,
      "name": "bpf_tracing_prog_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1305
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
int bpf_tracing_prog_attach(struct bpf_prog * prog, int tgt_prog_fd, u32 btf_id, u64 bpf_cookie)
```

```json
{
  "name": "bpf_tracing_prog_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581777792,
      "name": "bpf_tracing_prog_attach",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2956",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581777792,
      "name": "bpf_tracing_prog_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1360
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
int bpf_tracing_prog_attach(struct bpf_prog * prog, int tgt_prog_fd, u32 btf_id, u64 bpf_cookie)
```

```json
{
  "name": "bpf_tracing_prog_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581939952,
      "name": "bpf_tracing_prog_attach",
      "external": false,
      "loc": "kernel/bpf/syscall.c:3082",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939952,
      "name": "bpf_tracing_prog_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1407
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
int bpf_tracing_prog_attach(struct bpf_prog * prog, int tgt_prog_fd, u32 btf_id, u64 bpf_cookie)
```

```json
{
  "name": "bpf_tracing_prog_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582066560,
      "name": "bpf_tracing_prog_attach",
      "external": false,
      "loc": "kernel/bpf/syscall.c:3146",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582066560,
      "name": "bpf_tracing_prog_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1508
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
int bpf_tracing_prog_attach(struct bpf_prog * prog, int tgt_prog_fd, u32 btf_id)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 bpf_cookie</code>
</li>
</ul>
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
