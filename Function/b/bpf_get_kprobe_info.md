# Function: <code>bpf_get_kprobe_info</code>

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
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_kprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580584432,
      "name": "bpf_get_kprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1302",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580584432,
      "name": "bpf_get_kprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_kprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580642736,
      "name": "bpf_get_kprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1218",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580642736,
      "name": "bpf_get_kprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_kprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580704352,
      "name": "bpf_get_kprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1253",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580704352,
      "name": "bpf_get_kprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_kprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580752832,
      "name": "bpf_get_kprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1454",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752832,
      "name": "bpf_get_kprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_kprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580869936,
      "name": "bpf_get_kprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1635",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580869936,
      "name": "bpf_get_kprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_kprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580862336,
      "name": "bpf_get_kprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1655",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580862336,
      "name": "bpf_get_kprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_kprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580865808,
      "name": "bpf_get_kprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1658",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865808,
      "name": "bpf_get_kprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_kprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581066624,
      "name": "bpf_get_kprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1653",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581066624,
      "name": "bpf_get_kprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_kprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581326224,
      "name": "bpf_get_kprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1638",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581326224,
      "name": "bpf_get_kprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_kprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581656576,
      "name": "bpf_get_kprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1590",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581656576,
      "name": "bpf_get_kprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_kprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581797104,
      "name": "bpf_get_kprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1547",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581797104,
      "name": "bpf_get_kprobe_info",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, long unsigned int * missed, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_kprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581918544,
      "name": "bpf_get_kprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1613",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581918544,
      "name": "bpf_get_kprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_kprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492064072,
      "name": "bpf_get_kprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1454",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492064072,
      "name": "bpf_get_kprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_kprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225963592,
      "name": "bpf_get_kprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1454",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225963592,
      "name": "bpf_get_kprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_kprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285244304,
      "name": "bpf_get_kprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1454",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285244304,
      "name": "bpf_get_kprobe_info",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_kprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580721632,
      "name": "bpf_get_kprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1454",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580721632,
      "name": "bpf_get_kprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_kprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580667824,
      "name": "bpf_get_kprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1454",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580667824,
      "name": "bpf_get_kprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_kprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580712880,
      "name": "bpf_get_kprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1454",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580712880,
      "name": "bpf_get_kprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_kprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580770832,
      "name": "bpf_get_kprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_kprobe.c:1454",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580770832,
      "name": "bpf_get_kprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int * missed</code>
</li>
<li>
<b>Param reordered. </b>
<code>event, fd_type, symbol, probe_offset, probe_addr, perf_type_tracepoint</code> ➡️ <code>event, fd_type, symbol, probe_offset, probe_addr, missed, perf_type_tracepoint</code>
</li>
</ul>
</details>
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
int bpf_get_kprobe_info(const struct perf_event * event, u32 * fd_type, const char * * symbol, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
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
