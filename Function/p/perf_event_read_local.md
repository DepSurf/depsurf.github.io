# Function: <code>perf_event_read_local</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u64 perf_event_read_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580416672,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:3297",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_event_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580416672,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
u64 perf_event_read_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580489728,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:3498",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_event_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580489728,
      "name": "perf_event_read_local",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
u64 perf_event_read_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580553136,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:3586",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_event_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580553136,
      "name": "perf_event_read_local",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event * event, u64 * value)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580584240,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:3675",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580584240,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580664000,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:3580",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_prog_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580664000,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580795520,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:3913",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_prog_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580795520,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580862032,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:3908",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_prog_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580862032,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580958800,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:3928",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_prog_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580958800,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581011008,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:4025",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_prog_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581011008,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581191072,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:4248",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_prog_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581191072,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581232592,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:4325",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_prog_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581232592,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
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
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581248624,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:4405",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_prog_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581248624,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581483648,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:4513",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_prog_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581483648,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581828704,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:4411",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_prog_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828704,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582256080,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:4531",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_prog_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582256080,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582456688,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:4531",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_prog_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582456688,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582625472,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:4566",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_prog_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582625472,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492364080,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:4025",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_prog_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492364080,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226248592,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:4025",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_prog_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226248592,
      "name": "perf_event_read_local",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285616144,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:4025",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_prog_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285616144,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272488316,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:4025",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272488316,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580979856,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:4025",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_prog_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580979856,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580926048,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:4025",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_prog_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580926048,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580971056,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:4025",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_prog_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580971056,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int perf_event_read_local(struct perf_event * event, u64 * value, u64 * enabled, u64 * running)
```

```json
{
  "name": "perf_event_read_local",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581031856,
      "name": "perf_event_read_local",
      "external": true,
      "loc": "kernel/events/core.c:4025",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_perf_prog_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read_value",
        "kernel/trace/bpf_trace.c:bpf_perf_event_read",
        "kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581031856,
      "name": "perf_event_read_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 * value</code>
</li>
<li>
<b>Return type changed. </b>
<code>u64</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 * enabled</code>
</li>
<li>
<b>Param added. </b>
<code>u64 * running</code>
</li>
</ul>
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
