# Function: <code>bpf_get_perf_event_info</code>

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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr)
```

```json
{
  "name": "bpf_get_perf_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580573520,
      "name": "bpf_get_perf_event_info",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1180",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580573520,
      "name": "bpf_get_perf_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr)
```

```json
{
  "name": "bpf_get_perf_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580631808,
      "name": "bpf_get_perf_event_info",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1215",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580631808,
      "name": "bpf_get_perf_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr)
```

```json
{
  "name": "bpf_get_perf_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580693264,
      "name": "bpf_get_perf_event_info",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1387",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580693264,
      "name": "bpf_get_perf_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr)
```

```json
{
  "name": "bpf_get_perf_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580740288,
      "name": "bpf_get_perf_event_info",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1411",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580740288,
      "name": "bpf_get_perf_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr)
```

```json
{
  "name": "bpf_get_perf_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580856288,
      "name": "bpf_get_perf_event_info",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1905",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856288,
      "name": "bpf_get_perf_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr)
```

```json
{
  "name": "bpf_get_perf_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580848512,
      "name": "bpf_get_perf_event_info",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2161",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580848512,
      "name": "bpf_get_perf_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr)
```

```json
{
  "name": "bpf_get_perf_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580852336,
      "name": "bpf_get_perf_event_info",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1858",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580852336,
      "name": "bpf_get_perf_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr)
```

```json
{
  "name": "bpf_get_perf_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581052576,
      "name": "bpf_get_perf_event_info",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1942",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581052576,
      "name": "bpf_get_perf_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr)
```

```json
{
  "name": "bpf_get_perf_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581309936,
      "name": "bpf_get_perf_event_info",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2123",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581309936,
      "name": "bpf_get_perf_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr)
```

```json
{
  "name": "bpf_get_perf_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581638288,
      "name": "bpf_get_perf_event_info",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2346",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581638288,
      "name": "bpf_get_perf_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr)
```

```json
{
  "name": "bpf_get_perf_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581779712,
      "name": "bpf_get_perf_event_info",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2355",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581779712,
      "name": "bpf_get_perf_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr, long unsigned int * missed)
```

```json
{
  "name": "bpf_get_perf_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581899648,
      "name": "bpf_get_perf_event_info",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2460",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/syscall.c:bpf_perf_link_fill_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581899648,
      "name": "bpf_get_perf_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr)
```

```json
{
  "name": "bpf_get_perf_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492051856,
      "name": "bpf_get_perf_event_info",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1411",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492051856,
      "name": "bpf_get_perf_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr)
```

```json
{
  "name": "bpf_get_perf_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225951456,
      "name": "bpf_get_perf_event_info",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1411",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_task_fd_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225951456,
      "name": "bpf_get_perf_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr)
```

```json
{
  "name": "bpf_get_perf_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285224416,
      "name": "bpf_get_perf_event_info",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1411",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285224416,
      "name": "bpf_get_perf_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
  "name": "bpf_get_perf_event_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_get_perf_event_info",
      "external": false,
      "loc": "include/linux/trace_events.h:522",
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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr)
```

```json
{
  "name": "bpf_get_perf_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580709088,
      "name": "bpf_get_perf_event_info",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1411",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580709088,
      "name": "bpf_get_perf_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr)
```

```json
{
  "name": "bpf_get_perf_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580655296,
      "name": "bpf_get_perf_event_info",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1411",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580655296,
      "name": "bpf_get_perf_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr)
```

```json
{
  "name": "bpf_get_perf_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580700336,
      "name": "bpf_get_perf_event_info",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1411",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580700336,
      "name": "bpf_get_perf_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr)
```

```json
{
  "name": "bpf_get_perf_event_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580758288,
      "name": "bpf_get_perf_event_info",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1411",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580758288,
      "name": "bpf_get_perf_event_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr)
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
int bpf_get_perf_event_info(const struct perf_event * event, u32 * prog_id, u32 * fd_type, const char * * buf, u64 * probe_offset, u64 * probe_addr)
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
