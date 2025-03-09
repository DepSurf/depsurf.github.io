# Function: <code>trace_buffered_event_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580252304,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2013",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580252304,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580297920,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2041",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580297920,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580311472,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2218",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311472,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580364608,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2221",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580364608,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580426016,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2233",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580426016,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580481760,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2234",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580481760,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580537616,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2418",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580537616,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580585152,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2444",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580585152,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580684192,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2548",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580684192,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580675024,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2692",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580675024,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580677280,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2701",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580677280,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580851504,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2725",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580851504,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581080320,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2718",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581080320,
      "name": "trace_buffered_event_disable",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581387376,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2742",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581387376,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581481984,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2813",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581481984,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581593344,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2807",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581593344,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491882920,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2444",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491882920,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225824692,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2444",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225824692,
      "name": "trace_buffered_event_disable",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284961456,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2444",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284961456,
      "name": "trace_buffered_event_disable",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272173040,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2444",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272173040,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580553952,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2444",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580553952,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580500656,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2444",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580500656,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580545200,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2444",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545200,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void trace_buffered_event_disable()
```

```json
{
  "name": "trace_buffered_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580601776,
      "name": "trace_buffered_event_disable",
      "external": true,
      "loc": "kernel/trace/trace.c:2444",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580601776,
      "name": "trace_buffered_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void trace_buffered_event_disable()
```
</details>
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
