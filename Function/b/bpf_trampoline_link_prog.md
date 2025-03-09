# Function: <code>bpf_trampoline_link_prog</code>

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
int bpf_trampoline_link_prog(struct bpf_prog * prog)
```

```json
{
  "name": "bpf_trampoline_link_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581070368,
      "name": "bpf_trampoline_link_prog",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:259",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581070368,
      "name": "bpf_trampoline_link_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int bpf_trampoline_link_prog(struct bpf_prog * prog, struct bpf_trampoline * tr)
```

```json
{
  "name": "bpf_trampoline_link_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581085152,
      "name": "bpf_trampoline_link_prog",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:377",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581085152,
      "name": "bpf_trampoline_link_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
int bpf_trampoline_link_prog(struct bpf_prog * prog, struct bpf_trampoline * tr)
```

```json
{
  "name": "bpf_trampoline_link_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581104256,
      "name": "bpf_trampoline_link_prog",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:407",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581104256,
      "name": "bpf_trampoline_link_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int bpf_trampoline_link_prog(struct bpf_prog * prog, struct bpf_trampoline * tr)
```

```json
{
  "name": "bpf_trampoline_link_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581334192,
      "name": "bpf_trampoline_link_prog",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:413",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581334192,
      "name": "bpf_trampoline_link_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
int bpf_trampoline_link_prog(struct bpf_tramp_link * link, struct bpf_trampoline * tr)
```

```json
{
  "name": "bpf_trampoline_link_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581639200,
      "name": "bpf_trampoline_link_prog",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:413",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581639200,
      "name": "bpf_trampoline_link_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 717
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
int bpf_trampoline_link_prog(struct bpf_tramp_link * link, struct bpf_trampoline * tr)
```

```json
{
  "name": "bpf_trampoline_link_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582029712,
      "name": "bpf_trampoline_link_prog",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:582",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582029712,
      "name": "bpf_trampoline_link_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int bpf_trampoline_link_prog(struct bpf_tramp_link * link, struct bpf_trampoline * tr)
```

```json
{
  "name": "bpf_trampoline_link_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582221760,
      "name": "bpf_trampoline_link_prog",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:560",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582221760,
      "name": "bpf_trampoline_link_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int bpf_trampoline_link_prog(struct bpf_tramp_link * link, struct bpf_trampoline * tr)
```

```json
{
  "name": "bpf_trampoline_link_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582377664,
      "name": "bpf_trampoline_link_prog",
      "external": true,
      "loc": "kernel/bpf/trampoline.c:571",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582377664,
      "name": "bpf_trampoline_link_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int bpf_trampoline_link_prog(struct bpf_prog * prog)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_trampoline * tr</code>
</li>
</ul>
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
<code>struct bpf_tramp_link * link</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_prog * prog</code>
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
