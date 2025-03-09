# Function: <code>__find_event_file</code>

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
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
```

```json
{
  "name": "__find_event_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580508192,
      "name": "__find_event_file",
      "external": true,
      "loc": "kernel/trace/trace_events.c:2480",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace_events.c:find_event_file",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580508192,
      "name": "__find_event_file",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
```

```json
{
  "name": "__find_event_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580565888,
      "name": "__find_event_file",
      "external": true,
      "loc": "kernel/trace/trace_events.c:2481",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace_events.c:find_event_file",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580565888,
      "name": "__find_event_file",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
```

```json
{
  "name": "__find_event_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580622896,
      "name": "__find_event_file",
      "external": true,
      "loc": "kernel/trace/trace_events.c:2471",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace_events.c:find_event_file",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580622896,
      "name": "__find_event_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
```

```json
{
  "name": "__find_event_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580669616,
      "name": "__find_event_file",
      "external": true,
      "loc": "kernel/trace/trace_events.c:2470",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace_events.c:find_event_file",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669616,
      "name": "__find_event_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
```

```json
{
  "name": "__find_event_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580773008,
      "name": "__find_event_file",
      "external": true,
      "loc": "kernel/trace/trace_events.c:2675",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace_events.c:event_enable_func",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580773008,
      "name": "__find_event_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
```

```json
{
  "name": "__find_event_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580761616,
      "name": "__find_event_file",
      "external": true,
      "loc": "kernel/trace/trace_events.c:2691",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace_events.c:event_enable_func",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580761616,
      "name": "__find_event_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
```

```json
{
  "name": "__find_event_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580767488,
      "name": "__find_event_file",
      "external": true,
      "loc": "kernel/trace/trace_events.c:2902",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace_events.c:event_enable_func",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580767488,
      "name": "__find_event_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
```

```json
{
  "name": "__find_event_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580951360,
      "name": "__find_event_file",
      "external": true,
      "loc": "kernel/trace/trace_events.c:2919",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace_events.c:event_enable_func",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580951360,
      "name": "__find_event_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
```

```json
{
  "name": "__find_event_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581194048,
      "name": "__find_event_file",
      "external": true,
      "loc": "kernel/trace/trace_events.c:3022",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace_events.c:event_enable_func",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194048,
      "name": "__find_event_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
```

```json
{
  "name": "__find_event_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581511248,
      "name": "__find_event_file",
      "external": true,
      "loc": "kernel/trace/trace_events.c:3113",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace_events.c:event_enable_func",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581511248,
      "name": "__find_event_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
```

```json
{
  "name": "__find_event_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581629856,
      "name": "__find_event_file",
      "external": true,
      "loc": "kernel/trace/trace_events.c:3107",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace_events.c:event_enable_func",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581629856,
      "name": "__find_event_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
```

```json
{
  "name": "__find_event_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581743680,
      "name": "__find_event_file",
      "external": true,
      "loc": "kernel/trace/trace_events.c:3299",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace_events.c:event_enable_func",
        "kernel/trace/trace_events.c:trace_get_event_file",
        "kernel/trace/trace_events_hist.c:onmatch_parse",
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581743680,
      "name": "__find_event_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
```

```json
{
  "name": "__find_event_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491977184,
      "name": "__find_event_file",
      "external": true,
      "loc": "kernel/trace/trace_events.c:2470",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace_events.c:find_event_file",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491977184,
      "name": "__find_event_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
```

```json
{
  "name": "__find_event_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225912036,
      "name": "__find_event_file",
      "external": true,
      "loc": "kernel/trace/trace_events.c:2470",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace_events.c:find_event_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225912036,
      "name": "__find_event_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
```

```json
{
  "name": "__find_event_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285094720,
      "name": "__find_event_file",
      "external": true,
      "loc": "kernel/trace/trace_events.c:2470",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace_events.c:find_event_file",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285094720,
      "name": "__find_event_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 920
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
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
```

```json
{
  "name": "__find_event_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272247586,
      "name": "__find_event_file",
      "external": true,
      "loc": "kernel/trace/trace_events.c:2470",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace_events.c:find_event_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272247586,
      "name": "__find_event_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
```

```json
{
  "name": "__find_event_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580638416,
      "name": "__find_event_file",
      "external": true,
      "loc": "kernel/trace/trace_events.c:2470",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace_events.c:find_event_file",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580638416,
      "name": "__find_event_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
```

```json
{
  "name": "__find_event_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580584656,
      "name": "__find_event_file",
      "external": true,
      "loc": "kernel/trace/trace_events.c:2470",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace_events.c:find_event_file",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580584656,
      "name": "__find_event_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
```

```json
{
  "name": "__find_event_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580629664,
      "name": "__find_event_file",
      "external": true,
      "loc": "kernel/trace/trace_events.c:2470",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace_events.c:find_event_file",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580629664,
      "name": "__find_event_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
```

```json
{
  "name": "__find_event_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580687168,
      "name": "__find_event_file",
      "external": true,
      "loc": "kernel/trace/trace_events.c:2470",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:init_tracer_tracefs",
        "kernel/trace/trace_events.c:find_event_file",
        "kernel/trace/trace_events_hist.c:create_hist_data",
        "kernel/trace/trace_events_hist.c:create_field_var_hist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580687168,
      "name": "__find_event_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct trace_event_file * __find_event_file(struct trace_array * tr, const char * system, const char * event)
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
