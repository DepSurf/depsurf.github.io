# Function: <code>destroy_local_trace_kprobe</code>

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
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
```

```json
{
  "name": "destroy_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580584944,
      "name": "destroy_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1505",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580584944,
      "name": "destroy_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
```

```json
{
  "name": "destroy_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580643248,
      "name": "destroy_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1421",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580643248,
      "name": "destroy_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
```

```json
{
  "name": "destroy_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "destroy_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1431",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705149,
      "name": "destroy_local_trace_kprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071580704816,
      "name": "destroy_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
```

```json
{
  "name": "destroy_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580753280,
      "name": "destroy_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1630",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580753280,
      "name": "destroy_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
```

```json
{
  "name": "destroy_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580870512,
      "name": "destroy_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1823",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580870512,
      "name": "destroy_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
```

```json
{
  "name": "destroy_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580862912,
      "name": "destroy_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1844",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580862912,
      "name": "destroy_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
```

```json
{
  "name": "destroy_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580866336,
      "name": "destroy_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1847",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580866336,
      "name": "destroy_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
```

```json
{
  "name": "destroy_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581067152,
      "name": "destroy_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1845",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581067152,
      "name": "destroy_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
```

```json
{
  "name": "destroy_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581326832,
      "name": "destroy_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1839",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581326832,
      "name": "destroy_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
```

```json
{
  "name": "destroy_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581657264,
      "name": "destroy_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1791",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581657264,
      "name": "destroy_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
```

```json
{
  "name": "destroy_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581797824,
      "name": "destroy_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1748",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581797824,
      "name": "destroy_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
```

```json
{
  "name": "destroy_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581919424,
      "name": "destroy_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1831",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581919424,
      "name": "destroy_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
```

```json
{
  "name": "destroy_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492064584,
      "name": "destroy_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1630",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492064584,
      "name": "destroy_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
```

```json
{
  "name": "destroy_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225964088,
      "name": "destroy_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1630",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225964088,
      "name": "destroy_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
```

```json
{
  "name": "destroy_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285244960,
      "name": "destroy_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1630",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285244960,
      "name": "destroy_local_trace_kprobe",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
```

```json
{
  "name": "destroy_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580722080,
      "name": "destroy_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1630",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580722080,
      "name": "destroy_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
```

```json
{
  "name": "destroy_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580668272,
      "name": "destroy_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1630",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580668272,
      "name": "destroy_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
```

```json
{
  "name": "destroy_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580713328,
      "name": "destroy_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1630",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580713328,
      "name": "destroy_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
```

```json
{
  "name": "destroy_local_trace_kprobe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580771280,
      "name": "destroy_local_trace_kprobe",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1630",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580771280,
      "name": "destroy_local_trace_kprobe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
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
void destroy_local_trace_kprobe(struct trace_event_call * event_call)
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
