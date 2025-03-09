# Function: <code>tracing_set_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580213856,
      "name": "tracing_set_clock",
      "external": false,
      "loc": "kernel/trace/trace.c:5212",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace.c:trace_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580213856,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580249792,
      "name": "tracing_set_clock",
      "external": false,
      "loc": "kernel/trace/trace.c:5613",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:tracing_clock_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580249792,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580295168,
      "name": "tracing_set_clock",
      "external": false,
      "loc": "kernel/trace/trace.c:5889",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:tracing_clock_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580295168,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580308512,
      "name": "tracing_set_clock",
      "external": false,
      "loc": "kernel/trace/trace.c:6205",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracing_clock_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580308512,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580361568,
      "name": "tracing_set_clock",
      "external": false,
      "loc": "kernel/trace/trace.c:6216",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracing_clock_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580361568,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580439504,
      "name": "tracing_set_clock",
      "external": true,
      "loc": "kernel/trace/trace.c:6232",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_set_default_clock",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace_events_hist.c:hist_register_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580439504,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580495104,
      "name": "tracing_set_clock",
      "external": true,
      "loc": "kernel/trace/trace.c:6254",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_set_default_clock",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace_events_hist.c:hist_register_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580495104,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580550800,
      "name": "tracing_set_clock",
      "external": true,
      "loc": "kernel/trace/trace.c:6483",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_set_default_clock",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace_events_hist.c:hist_register_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580550800,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580598464,
      "name": "tracing_set_clock",
      "external": true,
      "loc": "kernel/trace/trace.c:6535",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_set_default_clock",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace_events_hist.c:hist_register_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580598464,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580698720,
      "name": "tracing_set_clock",
      "external": true,
      "loc": "kernel/trace/trace.c:6731",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_set_default_clock",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580698720,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580689504,
      "name": "tracing_set_clock",
      "external": true,
      "loc": "kernel/trace/trace.c:6805",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_set_default_clock",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580689504,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580693728,
      "name": "tracing_set_clock",
      "external": true,
      "loc": "kernel/trace/trace.c:7138",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_set_default_clock",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580693728,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580870224,
      "name": "tracing_set_clock",
      "external": true,
      "loc": "kernel/trace/trace.c:7216",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:late_trace_init",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580870224,
      "name": "tracing_set_clock",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581100400,
      "name": "tracing_set_clock",
      "external": true,
      "loc": "kernel/trace/trace.c:7221",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:late_trace_init",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581100400,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581408224,
      "name": "tracing_set_clock",
      "external": true,
      "loc": "kernel/trace/trace.c:7272",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:late_trace_init",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581408224,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581503200,
      "name": "tracing_set_clock",
      "external": true,
      "loc": "kernel/trace/trace.c:7428",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:late_trace_init",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503200,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581614640,
      "name": "tracing_set_clock",
      "external": true,
      "loc": "kernel/trace/trace.c:7461",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:late_trace_init",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581614640,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491896904,
      "name": "tracing_set_clock",
      "external": true,
      "loc": "kernel/trace/trace.c:6535",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace_events_hist.c:hist_register_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491896904,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225839172,
      "name": "tracing_set_clock",
      "external": true,
      "loc": "kernel/trace/trace.c:6535",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracing_clock_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225839172,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284982336,
      "name": "tracing_set_clock",
      "external": true,
      "loc": "kernel/trace/trace.c:6535",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace_events_hist.c:hist_register_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284982336,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272185390,
      "name": "tracing_set_clock",
      "external": true,
      "loc": "kernel/trace/trace.c:6535",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracing_clock_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272185390,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580567264,
      "name": "tracing_set_clock",
      "external": true,
      "loc": "kernel/trace/trace.c:6535",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_set_default_clock",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace_events_hist.c:hist_register_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580567264,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580513936,
      "name": "tracing_set_clock",
      "external": true,
      "loc": "kernel/trace/trace.c:6535",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_set_default_clock",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace_events_hist.c:hist_register_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580513936,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580558512,
      "name": "tracing_set_clock",
      "external": true,
      "loc": "kernel/trace/trace.c:6535",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_set_default_clock",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace_events_hist.c:hist_register_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580558512,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int tracing_set_clock(struct trace_array * tr, const char * clockstr)
```

```json
{
  "name": "tracing_set_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580615232,
      "name": "tracing_set_clock",
      "external": true,
      "loc": "kernel/trace/trace.c:6535",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_set_default_clock",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracing_clock_write",
        "kernel/trace/trace_events_hist.c:hist_register_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580615232,
      "name": "tracing_set_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
