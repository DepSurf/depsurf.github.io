# Function: <code>stack_trace_save</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
unsigned int stack_trace_save(long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580048704,
      "name": "stack_trace_save",
      "external": true,
      "loc": "kernel/stacktrace.c:113",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace_stack.c:stack_trace_call",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "mm/slub.c:set_track"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048704,
      "name": "stack_trace_save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
unsigned int stack_trace_save(long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580097808,
      "name": "stack_trace_save",
      "external": true,
      "loc": "kernel/stacktrace.c:113",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace_stack.c:stack_trace_call",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "mm/slub.c:set_track"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097808,
      "name": "stack_trace_save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
unsigned int stack_trace_save(long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580160304,
      "name": "stack_trace_save",
      "external": true,
      "loc": "kernel/stacktrace.c:113",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace_stack.c:check_stack",
        "kernel/trace/trace_events_hist.c:event_hist_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580160304,
      "name": "stack_trace_save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
unsigned int stack_trace_save(long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580144592,
      "name": "stack_trace_save",
      "external": true,
      "loc": "kernel/stacktrace.c:111",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace_stack.c:check_stack",
        "kernel/trace/trace_events_hist.c:event_hist_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580144592,
      "name": "stack_trace_save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
unsigned int stack_trace_save(long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580149280,
      "name": "stack_trace_save",
      "external": true,
      "loc": "kernel/stacktrace.c:111",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace_stack.c:check_stack",
        "kernel/trace/trace_events_hist.c:event_hist_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149280,
      "name": "stack_trace_save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
unsigned int stack_trace_save(long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580293808,
      "name": "stack_trace_save",
      "external": true,
      "loc": "kernel/stacktrace.c:111",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace_stack.c:check_stack",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "mm/kfence/core.c:metadata_update_state",
        "mm/kfence/report.c:kfence_report_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293808,
      "name": "stack_trace_save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
unsigned int stack_trace_save(long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580502384,
      "name": "stack_trace_save",
      "external": true,
      "loc": "kernel/stacktrace.c:112",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace_stack.c:check_stack",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "mm/slub.c:set_track_prepare",
        "mm/kfence/core.c:__kfence_alloc",
        "mm/kfence/core.c:metadata_update_state",
        "mm/kfence/report.c:kfence_report_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580502384,
      "name": "stack_trace_save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
unsigned int stack_trace_save(long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580755408,
      "name": "stack_trace_save",
      "external": true,
      "loc": "kernel/stacktrace.c:112",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace_stack.c:check_stack",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "mm/slub.c:set_track_prepare",
        "mm/kfence/core.c:__kfence_alloc",
        "mm/kfence/core.c:metadata_update_state",
        "mm/kfence/report.c:kfence_report_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580755408,
      "name": "stack_trace_save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
unsigned int stack_trace_save(long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580838080,
      "name": "stack_trace_save",
      "external": true,
      "loc": "kernel/stacktrace.c:112",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace_osnoise.c:timerlat_irq",
        "kernel/trace/trace_osnoise.c:timerlat_irq",
        "kernel/trace/trace_stack.c:check_stack",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_update",
        "kernel/trace/trace_events_hist.c:__update_field_vars",
        "mm/slub.c:set_track_prepare",
        "mm/kfence/core.c:__kfence_alloc",
        "mm/kfence/core.c:metadata_update_state",
        "mm/kfence/report.c:kfence_report_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580838080,
      "name": "stack_trace_save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
unsigned int stack_trace_save(long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580927504,
      "name": "stack_trace_save",
      "external": true,
      "loc": "kernel/stacktrace.c:112",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace_osnoise.c:timerlat_irq",
        "kernel/trace/trace_osnoise.c:timerlat_irq",
        "kernel/trace/trace_stack.c:check_stack",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_update",
        "kernel/trace/trace_events_hist.c:__update_field_vars",
        "mm/slub.c:set_track_prepare",
        "mm/kfence/core.c:__kfence_alloc",
        "mm/kfence/core.c:metadata_update_state",
        "mm/kfence/report.c:kfence_report_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580927504,
      "name": "stack_trace_save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
unsigned int stack_trace_save(long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491308960,
      "name": "stack_trace_save",
      "external": true,
      "loc": "kernel/stacktrace.c:272",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace_stack.c:stack_trace_call",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "mm/slub.c:set_track"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491308960,
      "name": "stack_trace_save",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
unsigned int stack_trace_save(long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225305536,
      "name": "stack_trace_save",
      "external": true,
      "loc": "kernel/stacktrace.c:272",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace_stack.c:stack_trace_call",
        "mm/slub.c:set_track"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225305536,
      "name": "stack_trace_save",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
unsigned int stack_trace_save(long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284234608,
      "name": "stack_trace_save",
      "external": true,
      "loc": "kernel/stacktrace.c:272",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/eeh_event.c:__eeh_send_failure_event",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace_stack.c:stack_trace_call",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "mm/slub.c:set_track"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284234608,
      "name": "stack_trace_save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
unsigned int stack_trace_save(long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271818184,
      "name": "stack_trace_save",
      "external": true,
      "loc": "kernel/stacktrace.c:272",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace_stack.c:stack_trace_call",
        "mm/slub.c:set_track"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271818184,
      "name": "stack_trace_save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
unsigned int stack_trace_save(long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580067008,
      "name": "stack_trace_save",
      "external": true,
      "loc": "kernel/stacktrace.c:113",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace_stack.c:stack_trace_call",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "mm/slub.c:set_track"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067008,
      "name": "stack_trace_save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
unsigned int stack_trace_save(long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580011824,
      "name": "stack_trace_save",
      "external": true,
      "loc": "kernel/stacktrace.c:113",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace_stack.c:stack_trace_call",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "mm/slub.c:set_track"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580011824,
      "name": "stack_trace_save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
unsigned int stack_trace_save(long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580058080,
      "name": "stack_trace_save",
      "external": true,
      "loc": "kernel/stacktrace.c:113",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace_stack.c:stack_trace_call",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "mm/slub.c:set_track"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580058080,
      "name": "stack_trace_save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
unsigned int stack_trace_save(long unsigned int * store, unsigned int size, unsigned int skipnr)
```

```json
{
  "name": "stack_trace_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580108912,
      "name": "stack_trace_save",
      "external": true,
      "loc": "kernel/stacktrace.c:113",
      "file": "kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace_stack.c:stack_trace_call",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "mm/slub.c:set_track"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580108912,
      "name": "stack_trace_save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
unsigned int stack_trace_save(long unsigned int * store, unsigned int size, unsigned int skipnr)
```
</details>
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
