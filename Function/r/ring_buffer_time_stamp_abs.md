# Function: <code>ring_buffer_time_stamp_abs</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer * buffer)
```

```json
{
  "name": "ring_buffer_time_stamp_abs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580391914,
      "name": "ring_buffer_time_stamp_abs",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:1451",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:__rb_reserve_next",
        "kernel/trace/ring_buffer.c:__rb_reserve_next"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_time_stamp_mode_show",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580402208,
      "name": "ring_buffer_time_stamp_abs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer * buffer)
```

```json
{
  "name": "ring_buffer_time_stamp_abs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580455690,
      "name": "ring_buffer_time_stamp_abs",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:1499",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:__rb_reserve_next",
        "kernel/trace/ring_buffer.c:__rb_reserve_next"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_time_stamp_mode_show",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580457504,
      "name": "ring_buffer_time_stamp_abs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer * buffer)
```

```json
{
  "name": "ring_buffer_time_stamp_abs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580510457,
      "name": "ring_buffer_time_stamp_abs",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:1476",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:__rb_reserve_next",
        "kernel/trace/ring_buffer.c:__rb_reserve_next"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_time_stamp_mode_show",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580512240,
      "name": "ring_buffer_time_stamp_abs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer * buffer)
```

```json
{
  "name": "ring_buffer_time_stamp_abs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580558025,
      "name": "ring_buffer_time_stamp_abs",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:1477",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:__rb_reserve_next",
        "kernel/trace/ring_buffer.c:__rb_reserve_next"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_time_stamp_mode_show",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580559856,
      "name": "ring_buffer_time_stamp_abs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool ring_buffer_time_stamp_abs(struct trace_buffer * buffer)
```

```json
{
  "name": "ring_buffer_time_stamp_abs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580650544,
      "name": "ring_buffer_time_stamp_abs",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:1480",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:__rb_reserve_next",
        "kernel/trace/ring_buffer.c:__rb_reserve_next"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_time_stamp_mode_show",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580653008,
      "name": "ring_buffer_time_stamp_abs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool ring_buffer_time_stamp_abs(struct trace_buffer * buffer)
```

```json
{
  "name": "ring_buffer_time_stamp_abs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580640830,
      "name": "ring_buffer_time_stamp_abs",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:1727",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_time_stamp_mode_show",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580643344,
      "name": "ring_buffer_time_stamp_abs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool ring_buffer_time_stamp_abs(struct trace_buffer * buffer)
```

```json
{
  "name": "ring_buffer_time_stamp_abs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580637533,
      "name": "ring_buffer_time_stamp_abs",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:1810",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_time_stamp_mode_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580646048,
      "name": "ring_buffer_time_stamp_abs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool ring_buffer_time_stamp_abs(struct trace_buffer * buffer)
```

```json
{
  "name": "ring_buffer_time_stamp_abs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580809649,
      "name": "ring_buffer_time_stamp_abs",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:1810",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_time_stamp_mode_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592168244,
      "name": "ring_buffer_time_stamp_abs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580818640,
      "name": "ring_buffer_time_stamp_abs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool ring_buffer_time_stamp_abs(struct trace_buffer * buffer)
```

```json
{
  "name": "ring_buffer_time_stamp_abs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581035770,
      "name": "ring_buffer_time_stamp_abs",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:1846",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_time_stamp_mode_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593941855,
      "name": "ring_buffer_time_stamp_abs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071581043216,
      "name": "ring_buffer_time_stamp_abs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool ring_buffer_time_stamp_abs(struct trace_buffer * buffer)
```

```json
{
  "name": "ring_buffer_time_stamp_abs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581343338,
      "name": "ring_buffer_time_stamp_abs",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:1908",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_time_stamp_mode_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596003942,
      "name": "ring_buffer_time_stamp_abs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071581346112,
      "name": "ring_buffer_time_stamp_abs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool ring_buffer_time_stamp_abs(struct trace_buffer * buffer)
```

```json
{
  "name": "ring_buffer_time_stamp_abs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581437658,
      "name": "ring_buffer_time_stamp_abs",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:1906",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_time_stamp_mode_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596522532,
      "name": "ring_buffer_time_stamp_abs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071581440288,
      "name": "ring_buffer_time_stamp_abs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool ring_buffer_time_stamp_abs(struct trace_buffer * buffer)
```

```json
{
  "name": "ring_buffer_time_stamp_abs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581525760,
      "name": "ring_buffer_time_stamp_abs",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:1747",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_max_event_size",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_time_stamp_mode_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597423173,
      "name": "ring_buffer_time_stamp_abs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071581549568,
      "name": "ring_buffer_time_stamp_abs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer * buffer)
```

```json
{
  "name": "ring_buffer_time_stamp_abs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491845360,
      "name": "ring_buffer_time_stamp_abs",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:1477",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:__rb_reserve_next",
        "kernel/trace/ring_buffer.c:__rb_reserve_next"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_time_stamp_mode_show",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491847416,
      "name": "ring_buffer_time_stamp_abs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer * buffer)
```

```json
{
  "name": "ring_buffer_time_stamp_abs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225792924,
      "name": "ring_buffer_time_stamp_abs",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:1477",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:__rb_reserve_next",
        "kernel/trace/ring_buffer.c:__rb_reserve_next"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_time_stamp_mode_show",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225795072,
      "name": "ring_buffer_time_stamp_abs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer * buffer)
```

```json
{
  "name": "ring_buffer_time_stamp_abs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284915920,
      "name": "ring_buffer_time_stamp_abs",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:1477",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:__rb_reserve_next",
        "kernel/trace/ring_buffer.c:__rb_reserve_next"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_time_stamp_mode_show",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284918592,
      "name": "ring_buffer_time_stamp_abs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer * buffer)
```

```json
{
  "name": "ring_buffer_time_stamp_abs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272146876,
      "name": "ring_buffer_time_stamp_abs",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:1477",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:__rb_reserve_next",
        "kernel/trace/ring_buffer.c:__rb_reserve_next"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_time_stamp_mode_show",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272148212,
      "name": "ring_buffer_time_stamp_abs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer * buffer)
```

```json
{
  "name": "ring_buffer_time_stamp_abs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580526825,
      "name": "ring_buffer_time_stamp_abs",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:1477",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:__rb_reserve_next",
        "kernel/trace/ring_buffer.c:__rb_reserve_next"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_time_stamp_mode_show",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580528656,
      "name": "ring_buffer_time_stamp_abs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer * buffer)
```

```json
{
  "name": "ring_buffer_time_stamp_abs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580473705,
      "name": "ring_buffer_time_stamp_abs",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:1477",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:__rb_reserve_next",
        "kernel/trace/ring_buffer.c:__rb_reserve_next"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_time_stamp_mode_show",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580475536,
      "name": "ring_buffer_time_stamp_abs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer * buffer)
```

```json
{
  "name": "ring_buffer_time_stamp_abs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580518073,
      "name": "ring_buffer_time_stamp_abs",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:1477",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:__rb_reserve_next",
        "kernel/trace/ring_buffer.c:__rb_reserve_next"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_time_stamp_mode_show",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580519904,
      "name": "ring_buffer_time_stamp_abs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool ring_buffer_time_stamp_abs(struct ring_buffer * buffer)
```

```json
{
  "name": "ring_buffer_time_stamp_abs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580574480,
      "name": "ring_buffer_time_stamp_abs",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:1477",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:__rb_reserve_next",
        "kernel/trace/ring_buffer.c:__rb_reserve_next"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_time_stamp_mode_show",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580576336,
      "name": "ring_buffer_time_stamp_abs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 8
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
bool ring_buffer_time_stamp_abs(struct ring_buffer * buffer)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ring_buffer * buffer</code> ➡️ <code>struct trace_buffer * buffer</code>
</li>
</ul>
</details>
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
