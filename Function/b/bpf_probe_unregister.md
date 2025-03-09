# Function: <code>bpf_probe_unregister</code>

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
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580573456,
      "name": "bpf_probe_unregister",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1170",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580573456,
      "name": "bpf_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580631776,
      "name": "bpf_probe_unregister",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1210",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580631776,
      "name": "bpf_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580693232,
      "name": "bpf_probe_unregister",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1382",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580693232,
      "name": "bpf_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580740256,
      "name": "bpf_probe_unregister",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1406",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580740256,
      "name": "bpf_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580856256,
      "name": "bpf_probe_unregister",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1900",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tp_link_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856256,
      "name": "bpf_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580848480,
      "name": "bpf_probe_unregister",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2156",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tp_link_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580848480,
      "name": "bpf_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580852304,
      "name": "bpf_probe_unregister",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1853",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tp_link_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580852304,
      "name": "bpf_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581052544,
      "name": "bpf_probe_unregister",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1937",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tp_link_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581052544,
      "name": "bpf_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581309904,
      "name": "bpf_probe_unregister",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2118",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tp_link_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581309904,
      "name": "bpf_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581638240,
      "name": "bpf_probe_unregister",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2341",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tp_link_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581638240,
      "name": "bpf_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581779664,
      "name": "bpf_probe_unregister",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2350",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tp_link_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581779664,
      "name": "bpf_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581899600,
      "name": "bpf_probe_unregister",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2455",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tp_link_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581899600,
      "name": "bpf_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492051824,
      "name": "bpf_probe_unregister",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1406",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492051824,
      "name": "bpf_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225951428,
      "name": "bpf_probe_unregister",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1406",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225951428,
      "name": "bpf_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285224352,
      "name": "bpf_probe_unregister",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1406",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285224352,
      "name": "bpf_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_probe_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_probe_unregister",
      "external": false,
      "loc": "include/linux/trace_events.h:511",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580709056,
      "name": "bpf_probe_unregister",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1406",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580709056,
      "name": "bpf_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580655264,
      "name": "bpf_probe_unregister",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1406",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580655264,
      "name": "bpf_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580700304,
      "name": "bpf_probe_unregister",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1406",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580700304,
      "name": "bpf_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580758256,
      "name": "bpf_probe_unregister",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1406",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580758256,
      "name": "bpf_probe_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int bpf_probe_unregister(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```
</details>
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
