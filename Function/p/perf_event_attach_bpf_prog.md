# Function: <code>perf_event_attach_bpf_prog</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog)
```

```json
{
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580486080,
      "name": "perf_event_attach_bpf_prog",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:781",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486080,
      "name": "perf_event_attach_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog)
```

```json
{
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580572432,
      "name": "perf_event_attach_bpf_prog",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:964",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580572432,
      "name": "perf_event_attach_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog)
```

```json
{
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580630560,
      "name": "perf_event_attach_bpf_prog",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1000",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580630560,
      "name": "perf_event_attach_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog)
```

```json
{
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580692016,
      "name": "perf_event_attach_bpf_prog",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1170",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580692016,
      "name": "perf_event_attach_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog)
```

```json
{
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580739040,
      "name": "perf_event_attach_bpf_prog",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1194",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580739040,
      "name": "perf_event_attach_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog)
```

```json
{
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580855024,
      "name": "perf_event_attach_bpf_prog",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1689",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_set_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580855024,
      "name": "perf_event_attach_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog)
```

```json
{
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580847248,
      "name": "perf_event_attach_bpf_prog",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1943",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_set_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580847248,
      "name": "perf_event_attach_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog)
```

```json
{
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580851072,
      "name": "perf_event_attach_bpf_prog",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1639",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_set_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580851072,
      "name": "perf_event_attach_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog, u64 bpf_cookie)
```

```json
{
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581051296,
      "name": "perf_event_attach_bpf_prog",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1721",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581051296,
      "name": "perf_event_attach_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog, u64 bpf_cookie)
```

```json
{
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581308496,
      "name": "perf_event_attach_bpf_prog",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1902",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581308496,
      "name": "perf_event_attach_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog, u64 bpf_cookie)
```

```json
{
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581636736,
      "name": "perf_event_attach_bpf_prog",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2119",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581636736,
      "name": "perf_event_attach_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog, u64 bpf_cookie)
```

```json
{
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581778160,
      "name": "perf_event_attach_bpf_prog",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2128",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581778160,
      "name": "perf_event_attach_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog, u64 bpf_cookie)
```

```json
{
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581898096,
      "name": "perf_event_attach_bpf_prog",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2233",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581898096,
      "name": "perf_event_attach_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog)
```

```json
{
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492050256,
      "name": "perf_event_attach_bpf_prog",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1194",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492050256,
      "name": "perf_event_attach_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog)
```

```json
{
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225950008,
      "name": "perf_event_attach_bpf_prog",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1194",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225950008,
      "name": "perf_event_attach_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog)
```

```json
{
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285221808,
      "name": "perf_event_attach_bpf_prog",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1194",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285221808,
      "name": "perf_event_attach_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_event_attach_bpf_prog",
      "external": false,
      "loc": "include/linux/trace_events.h:495",
      "file": "kernel/events/core.c",
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
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog)
```

```json
{
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580707840,
      "name": "perf_event_attach_bpf_prog",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1194",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580707840,
      "name": "perf_event_attach_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog)
```

```json
{
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580654048,
      "name": "perf_event_attach_bpf_prog",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1194",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580654048,
      "name": "perf_event_attach_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog)
```

```json
{
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580699088,
      "name": "perf_event_attach_bpf_prog",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1194",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580699088,
      "name": "perf_event_attach_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog)
```

```json
{
  "name": "perf_event_attach_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580757040,
      "name": "perf_event_attach_bpf_prog",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1194",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757040,
      "name": "perf_event_attach_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog)
```
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 bpf_cookie</code>
</li>
</ul>
</details>
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
int perf_event_attach_bpf_prog(struct perf_event * event, struct bpf_prog * prog)
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
