# Function: <code>bpf_perf_event_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 r1, u64 index, u64 r3, u64 r4, u64 r5)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580315504,
      "name": "bpf_perf_event_read",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:189",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315504,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 r1, u64 flags, u64 r3, u64 r4, u64 r5)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580369264,
      "name": "bpf_perf_event_read",
      "external": false,
      "loc": "kernel/trace/bpf_trace.c:234",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580369264,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580416448,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:231",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580416448,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580428384,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:269",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580428384,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580483968,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:296",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580483968,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580569760,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:319",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580569760,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580627360,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:355",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580627360,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580688112,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:366",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580688112,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580735072,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:369",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580735072,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580848816,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:758",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580848816,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580837520,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:841",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580837520,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580842288,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:518",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842288,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581042096,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:518",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581042096,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581296816,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:570",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296816,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581621424,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:573",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581621424,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581761920,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:571",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581761920,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581879312,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:571",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581879312,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492045176,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:369",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492045176,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225943992,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:369",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225943992,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285214864,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:369",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285214864,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580703872,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:369",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580703872,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580650080,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:369",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580650080,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580695120,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:369",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580695120,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_perf_event_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580750640,
      "name": "bpf_perf_event_read",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:369",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580750640,
      "name": "bpf_perf_event_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 index</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 map</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_1</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_2</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_3</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r3</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r4</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r5</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
u64 bpf_perf_event_read(u64 map, u64 flags, u64 __ur_1, u64 __ur_2, u64 __ur_3)
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
