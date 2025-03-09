# Function: <code>ring_buffer_event_time_stamp</code>

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
u64 ring_buffer_event_time_stamp(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_time_stamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580397975,
      "name": "ring_buffer_event_time_stamp",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:294",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_iter_peek",
        "kernel/trace/ring_buffer.c:rb_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_field_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580401328,
      "name": "ring_buffer_event_time_stamp",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 ring_buffer_event_time_stamp(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_time_stamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580452714,
      "name": "ring_buffer_event_time_stamp",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:295",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_iter_peek",
        "kernel/trace/ring_buffer.c:rb_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_field_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580454832,
      "name": "ring_buffer_event_time_stamp",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 ring_buffer_event_time_stamp(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_time_stamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580505055,
      "name": "ring_buffer_event_time_stamp",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:286",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_iter_peek",
        "kernel/trace/ring_buffer.c:rb_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_field_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580509600,
      "name": "ring_buffer_event_time_stamp",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 ring_buffer_event_time_stamp(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_time_stamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580553935,
      "name": "ring_buffer_event_time_stamp",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:287",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_iter_peek",
        "kernel/trace/ring_buffer.c:rb_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_field_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580557168,
      "name": "ring_buffer_event_time_stamp",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 ring_buffer_event_time_stamp(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_time_stamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580640760,
      "name": "ring_buffer_event_time_stamp",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:287",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_iter_peek",
        "kernel/trace/ring_buffer.c:rb_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_field_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580651824,
      "name": "ring_buffer_event_time_stamp",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 ring_buffer_event_time_stamp(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_time_stamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580631208,
      "name": "ring_buffer_event_time_stamp",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:300",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_iter_peek",
        "kernel/trace/ring_buffer.c:rb_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_field_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580642112,
      "name": "ring_buffer_event_time_stamp",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
u64 ring_buffer_event_time_stamp(struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_time_stamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580644880,
      "name": "ring_buffer_event_time_stamp",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:806",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_event_time_stamp",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace_events_hist.c:hist_field_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580644880,
      "name": "ring_buffer_event_time_stamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
u64 ring_buffer_event_time_stamp(struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_time_stamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ring_buffer_event_time_stamp",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:806",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_event_time_stamp",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace_events_hist.c:hist_field_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592168223,
      "name": "ring_buffer_event_time_stamp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580817424,
      "name": "ring_buffer_event_time_stamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
u64 ring_buffer_event_time_stamp(struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_time_stamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ring_buffer_event_time_stamp",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:840",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_event_time_stamp",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace_events_hist.c:hist_field_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593941834,
      "name": "ring_buffer_event_time_stamp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581041760,
      "name": "ring_buffer_event_time_stamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
u64 ring_buffer_event_time_stamp(struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_time_stamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ring_buffer_event_time_stamp",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:842",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_event_time_stamp",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace_events_hist.c:hist_fn_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596003572,
      "name": "ring_buffer_event_time_stamp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581342144,
      "name": "ring_buffer_event_time_stamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
u64 ring_buffer_event_time_stamp(struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_time_stamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ring_buffer_event_time_stamp",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:840",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_event_time_stamp",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace_events_hist.c:hist_fn_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596522165,
      "name": "ring_buffer_event_time_stamp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581436480,
      "name": "ring_buffer_event_time_stamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
u64 ring_buffer_event_time_stamp(struct trace_buffer * buffer, struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_time_stamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ring_buffer_event_time_stamp",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:652",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_event_time_stamp",
        "kernel/trace/trace.c:trace_last_func_repeats",
        "kernel/trace/trace_events_hist.c:hist_fn_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597422812,
      "name": "ring_buffer_event_time_stamp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581545728,
      "name": "ring_buffer_event_time_stamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
u64 ring_buffer_event_time_stamp(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_time_stamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491842532,
      "name": "ring_buffer_event_time_stamp",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:287",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_iter_peek",
        "kernel/trace/ring_buffer.c:rb_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_field_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491844520,
      "name": "ring_buffer_event_time_stamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
u64 ring_buffer_event_time_stamp(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_time_stamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225785168,
      "name": "ring_buffer_event_time_stamp",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:287",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_iter_peek",
        "kernel/trace/ring_buffer.c:rb_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225791956,
      "name": "ring_buffer_event_time_stamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
u64 ring_buffer_event_time_stamp(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_time_stamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284906740,
      "name": "ring_buffer_event_time_stamp",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:287",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_iter_peek",
        "kernel/trace/ring_buffer.c:rb_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_field_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284914720,
      "name": "ring_buffer_event_time_stamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
u64 ring_buffer_event_time_stamp(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_time_stamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272144748,
      "name": "ring_buffer_event_time_stamp",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:287",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_iter_peek",
        "kernel/trace/ring_buffer.c:rb_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272146178,
      "name": "ring_buffer_event_time_stamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
u64 ring_buffer_event_time_stamp(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_time_stamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580522735,
      "name": "ring_buffer_event_time_stamp",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:287",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_iter_peek",
        "kernel/trace/ring_buffer.c:rb_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_field_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580525968,
      "name": "ring_buffer_event_time_stamp",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
u64 ring_buffer_event_time_stamp(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_time_stamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580471167,
      "name": "ring_buffer_event_time_stamp",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:287",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_iter_peek",
        "kernel/trace/ring_buffer.c:rb_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_field_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580472848,
      "name": "ring_buffer_event_time_stamp",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
u64 ring_buffer_event_time_stamp(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_time_stamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580513983,
      "name": "ring_buffer_event_time_stamp",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:287",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_iter_peek",
        "kernel/trace/ring_buffer.c:rb_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_field_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580517216,
      "name": "ring_buffer_event_time_stamp",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
u64 ring_buffer_event_time_stamp(struct ring_buffer_event * event)
```

```json
{
  "name": "ring_buffer_event_time_stamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580570351,
      "name": "ring_buffer_event_time_stamp",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:287",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_iter_peek",
        "kernel/trace/ring_buffer.c:rb_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_field_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580573584,
      "name": "ring_buffer_event_time_stamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
u64 ring_buffer_event_time_stamp(struct ring_buffer_event * event)
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct trace_buffer * buffer</code>
</li>
<li>
<b>Param reordered. </b>
<code>event</code> ➡️ <code>buffer, event</code>
</li>
</ul>
</details>
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
