# Function: <code>hist_fn_call</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
u64 hist_fn_call(struct hist_field * hist_field, struct tracing_map_elt * elt, struct trace_buffer * buffer, struct ring_buffer_event * rbe, void * event)
```

```json
{
  "name": "hist_fn_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hist_fn_call",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4245",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_update",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_update",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:__update_field_vars",
        "kernel/trace/trace_events_hist.c:parse_expr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581585904,
      "name": "hist_fn_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1286
    },
    {
      "addr": 18446744071596010222,
      "name": "hist_fn_call.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
u64 hist_fn_call(struct hist_field * hist_field, struct tracing_map_elt * elt, struct trace_buffer * buffer, struct ring_buffer_event * rbe, void * event)
```

```json
{
  "name": "hist_fn_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hist_fn_call",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4319",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_update",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_update",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:__update_field_vars",
        "kernel/trace/trace_events_hist.c:parse_expr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581707136,
      "name": "hist_fn_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1265
    },
    {
      "addr": 18446744071596529195,
      "name": "hist_fn_call.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
u64 hist_fn_call(struct hist_field * hist_field, struct tracing_map_elt * elt, struct trace_buffer * buffer, struct ring_buffer_event * rbe, void * event)
```

```json
{
  "name": "hist_fn_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hist_fn_call",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4312",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_update",
        "kernel/trace/trace_events_hist.c:hist_trigger_elt_update",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:hist_fn_call",
        "kernel/trace/trace_events_hist.c:__update_field_vars",
        "kernel/trace/trace_events_hist.c:parse_expr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581823440,
      "name": "hist_fn_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1265
    },
    {
      "addr": 18446744071597429807,
      "name": "hist_fn_call.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
u64 hist_fn_call(struct hist_field * hist_field, struct tracing_map_elt * elt, struct trace_buffer * buffer, struct ring_buffer_event * rbe, void * event)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
