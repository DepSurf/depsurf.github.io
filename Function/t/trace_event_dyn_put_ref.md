# Function: <code>trace_event_dyn_put_ref</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void trace_event_dyn_put_ref(struct trace_event_call * call)
```

```json
{
  "name": "trace_event_dyn_put_ref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581082608,
      "name": "trace_event_dyn_put_ref",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:41",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_enable_func",
        "kernel/trace/trace_events.c:trace_put_event_file",
        "kernel/trace/trace_event_perf.c:perf_trace_init",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581082608,
      "name": "trace_event_dyn_put_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void trace_event_dyn_put_ref(struct trace_event_call * call)
```

```json
{
  "name": "trace_event_dyn_put_ref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581344144,
      "name": "trace_event_dyn_put_ref",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:41",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_enable_func",
        "kernel/trace/trace_events.c:trace_put_event_file",
        "kernel/trace/trace_event_perf.c:perf_uprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_trace_destroy",
        "kernel/trace/trace_event_perf.c:perf_trace_init",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_parse",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581344144,
      "name": "trace_event_dyn_put_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void trace_event_dyn_put_ref(struct trace_event_call * call)
```

```json
{
  "name": "trace_event_dyn_put_ref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581677872,
      "name": "trace_event_dyn_put_ref",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:41",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_enable_func",
        "kernel/trace/trace_events.c:trace_put_event_file",
        "kernel/trace/trace_event_perf.c:perf_uprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_trace_destroy",
        "kernel/trace/trace_event_perf.c:perf_trace_init",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_parse",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581677872,
      "name": "trace_event_dyn_put_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void trace_event_dyn_put_ref(struct trace_event_call * call)
```

```json
{
  "name": "trace_event_dyn_put_ref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581819392,
      "name": "trace_event_dyn_put_ref",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:41",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_enable_func",
        "kernel/trace/trace_events.c:trace_put_event_file",
        "kernel/trace/trace_event_perf.c:perf_uprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_trace_destroy",
        "kernel/trace/trace_event_perf.c:perf_trace_init",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_parse",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581819392,
      "name": "trace_event_dyn_put_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void trace_event_dyn_put_ref(struct trace_event_call * call)
```

```json
{
  "name": "trace_event_dyn_put_ref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581941008,
      "name": "trace_event_dyn_put_ref",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:41",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_enable_func",
        "kernel/trace/trace_events.c:trace_put_event_file",
        "kernel/trace/trace_event_perf.c:perf_uprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_kprobe_destroy",
        "kernel/trace/trace_event_perf.c:perf_trace_destroy",
        "kernel/trace/trace_event_perf.c:perf_trace_init",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_parse",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581941008,
      "name": "trace_event_dyn_put_ref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void trace_event_dyn_put_ref(struct trace_event_call * call)
```
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
