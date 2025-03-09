# Function: <code>bpf_probe_register</code>

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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580573360,
      "name": "bpf_probe_register",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1160",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580573360,
      "name": "bpf_probe_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580631712,
      "name": "bpf_probe_register",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1205",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580631712,
      "name": "bpf_probe_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580693168,
      "name": "bpf_probe_register",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1377",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580693168,
      "name": "bpf_probe_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580740192,
      "name": "bpf_probe_register",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1401",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580740192,
      "name": "bpf_probe_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580856192,
      "name": "bpf_probe_register",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1895",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856192,
      "name": "bpf_probe_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580848416,
      "name": "bpf_probe_register",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2151",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580848416,
      "name": "bpf_probe_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580852240,
      "name": "bpf_probe_register",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1848",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580852240,
      "name": "bpf_probe_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581052480,
      "name": "bpf_probe_register",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1932",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581052480,
      "name": "bpf_probe_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581309808,
      "name": "bpf_probe_register",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2113",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581309808,
      "name": "bpf_probe_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581638128,
      "name": "bpf_probe_register",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2336",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581638128,
      "name": "bpf_probe_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581779552,
      "name": "bpf_probe_register",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2345",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581779552,
      "name": "bpf_probe_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581899488,
      "name": "bpf_probe_register",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2450",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581899488,
      "name": "bpf_probe_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492051744,
      "name": "bpf_probe_register",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1401",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492051744,
      "name": "bpf_probe_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225951348,
      "name": "bpf_probe_register",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1401",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225951348,
      "name": "bpf_probe_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285224224,
      "name": "bpf_probe_register",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1401",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285224224,
      "name": "bpf_probe_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
  "name": "bpf_probe_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_probe_register",
      "external": false,
      "loc": "include/linux/trace_events.h:507",
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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580708992,
      "name": "bpf_probe_register",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1401",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580708992,
      "name": "bpf_probe_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580655200,
      "name": "bpf_probe_register",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1401",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580655200,
      "name": "bpf_probe_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580700240,
      "name": "bpf_probe_register",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1401",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580700240,
      "name": "bpf_probe_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_probe_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580758192,
      "name": "bpf_probe_register",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1401",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580758192,
      "name": "bpf_probe_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
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
int bpf_probe_register(struct bpf_raw_event_map * btp, struct bpf_prog * prog)
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
