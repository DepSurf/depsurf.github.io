# Function: <code>register_ftrace_direct</code>

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
int register_ftrace_direct(long unsigned int ip, long unsigned int addr)
```

```json
{
  "name": "register_ftrace_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580627808,
      "name": "register_ftrace_direct",
      "external": true,
      "loc": "kernel/trace/ftrace.c:4988",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580627808,
      "name": "register_ftrace_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1038
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
int register_ftrace_direct(long unsigned int ip, long unsigned int addr)
```

```json
{
  "name": "register_ftrace_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580618608,
      "name": "register_ftrace_direct",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5079",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580618608,
      "name": "register_ftrace_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 970
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
int register_ftrace_direct(long unsigned int ip, long unsigned int addr)
```

```json
{
  "name": "register_ftrace_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580621488,
      "name": "register_ftrace_direct",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5079",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580621488,
      "name": "register_ftrace_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 966
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
int register_ftrace_direct(long unsigned int ip, long unsigned int addr)
```

```json
{
  "name": "register_ftrace_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_ftrace_direct",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5079",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592167412,
      "name": "register_ftrace_direct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071580793232,
      "name": "register_ftrace_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1042
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
int register_ftrace_direct(long unsigned int ip, long unsigned int addr)
```

```json
{
  "name": "register_ftrace_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581014592,
      "name": "register_ftrace_direct",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5245",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014592,
      "name": "register_ftrace_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
int register_ftrace_direct(long unsigned int ip, long unsigned int addr)
```

```json
{
  "name": "register_ftrace_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581315440,
      "name": "register_ftrace_direct",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5268",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581315440,
      "name": "register_ftrace_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
int register_ftrace_direct(struct ftrace_ops * ops, long unsigned int addr)
```

```json
{
  "name": "register_ftrace_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_ftrace_direct",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5411",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596521828,
      "name": "register_ftrace_direct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071581412656,
      "name": "register_ftrace_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
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
int register_ftrace_direct(struct ftrace_ops * ops, long unsigned int addr)
```

```json
{
  "name": "register_ftrace_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_ftrace_direct",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5388",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597422235,
      "name": "register_ftrace_direct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071581518592,
      "name": "register_ftrace_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 840
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
int register_ftrace_direct(long unsigned int ip, long unsigned int addr)
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ftrace_ops * ops</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int ip</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
