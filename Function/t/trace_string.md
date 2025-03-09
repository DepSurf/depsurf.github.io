# Function: <code>trace_string</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
unsigned int trace_string(struct synth_trace_event * entry, struct synth_event * event, char * str_val, bool is_dynamic, unsigned int data_size, unsigned int * n_u64)
```

```json
{
  "name": "trace_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580790176,
      "name": "trace_string",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:394",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_event_trace_array",
        "kernel/trace/trace_events_synth.c:synth_event_trace",
        "kernel/trace/trace_events_synth.c:trace_event_raw_event_synth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580790176,
      "name": "trace_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
unsigned int trace_string(struct synth_trace_event * entry, struct synth_event * event, char * str_val, bool is_dynamic, unsigned int data_size, unsigned int * n_u64)
```

```json
{
  "name": "trace_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580795824,
      "name": "trace_string",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:395",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_event_trace_array",
        "kernel/trace/trace_events_synth.c:synth_event_trace",
        "kernel/trace/trace_events_synth.c:trace_event_raw_event_synth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580795824,
      "name": "trace_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
unsigned int trace_string(struct synth_trace_event * entry, struct synth_event * event, char * str_val, bool is_dynamic, unsigned int data_size, unsigned int * n_u64)
```

```json
{
  "name": "trace_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580990208,
      "name": "trace_string",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:395",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_event_trace_array",
        "kernel/trace/trace_events_synth.c:synth_event_trace",
        "kernel/trace/trace_events_synth.c:trace_event_raw_event_synth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580990208,
      "name": "trace_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
unsigned int trace_string(struct synth_trace_event * entry, struct synth_event * event, char * str_val, bool is_dynamic, unsigned int data_size, unsigned int * n_u64)
```

```json
{
  "name": "trace_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581236384,
      "name": "trace_string",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:403",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_event_trace_array",
        "kernel/trace/trace_events_synth.c:synth_event_trace",
        "kernel/trace/trace_events_synth.c:trace_event_raw_event_synth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581236384,
      "name": "trace_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
unsigned int trace_string(struct synth_trace_event * entry, struct synth_event * event, char * str_val, bool is_dynamic, unsigned int data_size, unsigned int * n_u64)
```

```json
{
  "name": "trace_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581564496,
      "name": "trace_string",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:405",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_event_trace_array",
        "kernel/trace/trace_events_synth.c:synth_event_trace",
        "kernel/trace/trace_events_synth.c:trace_event_raw_event_synth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581564496,
      "name": "trace_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 733
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
unsigned int trace_string(struct synth_trace_event * entry, struct synth_event * event, char * str_val, bool is_dynamic, unsigned int data_size, unsigned int * n_u64)
```

```json
{
  "name": "trace_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581683392,
      "name": "trace_string",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:430",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_event_trace_array",
        "kernel/trace/trace_events_synth.c:synth_event_trace",
        "kernel/trace/trace_events_synth.c:trace_event_raw_event_synth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581683392,
      "name": "trace_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
unsigned int trace_string(struct synth_trace_event * entry, struct synth_event * event, char * str_val, bool is_dynamic, unsigned int data_size, unsigned int * n_u64)
```

```json
{
  "name": "trace_string",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581799696,
      "name": "trace_string",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:430",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_event_trace_array",
        "kernel/trace/trace_events_synth.c:synth_event_trace",
        "kernel/trace/trace_events_synth.c:trace_event_raw_event_synth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581799696,
      "name": "trace_string",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
unsigned int trace_string(struct synth_trace_event * entry, struct synth_event * event, char * str_val, bool is_dynamic, unsigned int data_size, unsigned int * n_u64)
```
</details>
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
