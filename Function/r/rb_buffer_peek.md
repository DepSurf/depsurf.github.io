# Function: <code>rb_buffer_peek</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580190864,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3717",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580190864,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580224400,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3712",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580224400,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580269584,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3681",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580269584,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580281600,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3695",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580281600,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580335616,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3687",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580335616,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580395328,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3834",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580395328,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580450224,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3899",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580450224,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580507440,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3876",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507440,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580555072,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3877",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580555072,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580647136,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3958",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647136,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580637856,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:4504",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580637856,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580642272,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:4611",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580642272,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580814800,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:4611",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580814800,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581039088,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:4651",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581039088,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581339376,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:4757",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581339376,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581433728,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:4764",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581433728,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581543040,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:4670",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581543040,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491831752,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3877",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491831752,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225783048,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3877",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225783048,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284912608,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3877",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284912608,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272142534,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3877",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272142534,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580523872,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3877",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580523872,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580467616,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3877",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580467616,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580515120,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3877",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580515120,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
struct ring_buffer_event * rb_buffer_peek(struct ring_buffer_per_cpu * cpu_buffer, u64 * ts, long unsigned int * lost_events)
```

```json
{
  "name": "rb_buffer_peek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580571488,
      "name": "rb_buffer_peek",
      "external": false,
      "loc": "kernel/trace/ring_buffer.c:3877",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:ring_buffer_peek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571488,
      "name": "rb_buffer_peek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
