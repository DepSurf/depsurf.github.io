# Function: <code>bpf_prog_array_copy</code>

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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580541328,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:1512",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541328,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580625136,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:1638",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580625136,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580685408,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:1890",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580685408,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580752816,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:1883",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752816,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580803408,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:1883",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580803408,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580920848,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:1961",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920848,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580917504,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:2018",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917504,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580921456,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:2114",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580921456,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, u64 bpf_cookie, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581123968,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:2127",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123968,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, u64 bpf_cookie, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581393424,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:2413",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581393424,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, u64 bpf_cookie, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581743200,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:2407",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581743200,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, u64 bpf_cookie, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902512,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:2424",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902512,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, u64 bpf_cookie, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582026176,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:2600",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582026176,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492118808,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:1883",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492118808,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226019644,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:1883",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226019644,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285326384,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:1883",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285326384,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272290488,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:1883",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272290488,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
    }
  ]
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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580772208,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:1883",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772208,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580718384,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:1883",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580718384,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580763456,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:1883",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580763456,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, struct bpf_prog_array * * new_array)
```

```json
{
  "name": "bpf_prog_array_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580821600,
      "name": "bpf_prog_array_copy",
      "external": true,
      "loc": "kernel/bpf/core.c:1883",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_detach_bpf_prog",
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580821600,
      "name": "bpf_prog_array_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
int bpf_prog_array_copy(struct bpf_prog_array * old_array, struct bpf_prog * exclude_prog, struct bpf_prog * include_prog, struct bpf_prog_array * * new_array)
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
<li>
<b>Param reordered. </b>
<code>old_array, exclude_prog, include_prog, new_array</code> ➡️ <code>old_array, exclude_prog, include_prog, bpf_cookie, new_array</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
