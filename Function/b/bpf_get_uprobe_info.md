# Function: <code>bpf_get_uprobe_info</code>

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
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_uprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580613936,
      "name": "bpf_get_uprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1165",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580613936,
      "name": "bpf_get_uprobe_info",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_uprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580672928,
      "name": "bpf_get_uprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1167",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580672928,
      "name": "bpf_get_uprobe_info",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_uprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580737440,
      "name": "bpf_get_uprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1189",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580737440,
      "name": "bpf_get_uprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_uprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580788224,
      "name": "bpf_get_uprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1397",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580788224,
      "name": "bpf_get_uprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_uprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580905616,
      "name": "bpf_get_uprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1404",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580905616,
      "name": "bpf_get_uprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_uprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580900416,
      "name": "bpf_get_uprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1417",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580900416,
      "name": "bpf_get_uprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_uprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580904240,
      "name": "bpf_get_uprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1422",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580904240,
      "name": "bpf_get_uprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_uprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581106432,
      "name": "bpf_get_uprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1423",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581106432,
      "name": "bpf_get_uprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_uprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581368800,
      "name": "bpf_get_uprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1413",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581368800,
      "name": "bpf_get_uprobe_info",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_uprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581705120,
      "name": "bpf_get_uprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1419",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581705120,
      "name": "bpf_get_uprobe_info",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_uprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581850000,
      "name": "bpf_get_uprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1419",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581850000,
      "name": "bpf_get_uprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, u64 * probe_addr, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_uprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581973120,
      "name": "bpf_get_uprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1415",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581973120,
      "name": "bpf_get_uprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_uprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492100840,
      "name": "bpf_get_uprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1397",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492100840,
      "name": "bpf_get_uprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_uprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226000860,
      "name": "bpf_get_uprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1397",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226000860,
      "name": "bpf_get_uprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_uprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285303328,
      "name": "bpf_get_uprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1397",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285303328,
      "name": "bpf_get_uprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_uprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580757024,
      "name": "bpf_get_uprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1397",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757024,
      "name": "bpf_get_uprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_uprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580703216,
      "name": "bpf_get_uprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1397",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580703216,
      "name": "bpf_get_uprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_uprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580748272,
      "name": "bpf_get_uprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1397",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580748272,
      "name": "bpf_get_uprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, bool perf_type_tracepoint)
```

```json
{
  "name": "bpf_get_uprobe_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580806320,
      "name": "bpf_get_uprobe_info",
      "external": true,
      "loc": "kernel/trace/trace_uprobe.c:1397",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_get_perf_event_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580806320,
      "name": "bpf_get_uprobe_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, bool perf_type_tracepoint)
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 * probe_addr</code>
</li>
<li>
<b>Param reordered. </b>
<code>event, fd_type, filename, probe_offset, perf_type_tracepoint</code> ➡️ <code>event, fd_type, filename, probe_offset, probe_addr, perf_type_tracepoint</code>
</li>
</ul>
</details>
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
int bpf_get_uprobe_info(const struct perf_event * event, u32 * fd_type, const char * * filename, u64 * probe_offset, bool perf_type_tracepoint)
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
