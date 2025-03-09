# Function: <code>__synth_event_add_val</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__synth_event_add_val",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580806176,
      "name": "__synth_event_add_val",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:1456",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_synth.c:synth_event_add_val",
        "kernel/trace/trace_events_synth.c:synth_event_add_next_val"
      ],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_event_add_val",
        "kernel/trace/trace_events_synth.c:synth_event_add_next_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580805856,
      "name": "__synth_event_add_val.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__synth_event_add_val",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580791984,
      "name": "__synth_event_add_val",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:1751",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_synth.c:synth_event_add_val",
        "kernel/trace/trace_events_synth.c:synth_event_add_next_val"
      ],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_event_add_val",
        "kernel/trace/trace_events_synth.c:synth_event_add_next_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580791648,
      "name": "__synth_event_add_val.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__synth_event_add_val",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580797632,
      "name": "__synth_event_add_val",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:1853",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_synth.c:synth_event_add_val",
        "kernel/trace/trace_events_synth.c:synth_event_add_next_val"
      ],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_event_add_val",
        "kernel/trace/trace_events_synth.c:synth_event_add_next_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580797296,
      "name": "__synth_event_add_val.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int __synth_event_add_val(const char * field_name, u64 val, struct synth_event_trace_state * trace_state)
```

```json
{
  "name": "__synth_event_add_val",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__synth_event_add_val",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:1853",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_event_add_val",
        "kernel/trace/trace_events_synth.c:synth_event_add_next_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580990992,
      "name": "__synth_event_add_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
    },
    {
      "addr": 18446744071592176319,
      "name": "__synth_event_add_val.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int __synth_event_add_val(const char * field_name, u64 val, struct synth_event_trace_state * trace_state)
```

```json
{
  "name": "__synth_event_add_val",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__synth_event_add_val",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:1862",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_event_add_val",
        "kernel/trace/trace_events_synth.c:synth_event_add_next_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237776,
      "name": "__synth_event_add_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    },
    {
      "addr": 18446744071593949968,
      "name": "__synth_event_add_val.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int __synth_event_add_val(const char * field_name, u64 val, struct synth_event_trace_state * trace_state)
```

```json
{
  "name": "__synth_event_add_val",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__synth_event_add_val",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:1870",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_event_add_val",
        "kernel/trace/trace_events_synth.c:synth_event_add_next_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558928,
      "name": "__synth_event_add_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    },
    {
      "addr": 18446744071596008788,
      "name": "__synth_event_add_val.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int __synth_event_add_val(const char * field_name, u64 val, struct synth_event_trace_state * trace_state)
```

```json
{
  "name": "__synth_event_add_val",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__synth_event_add_val",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:1943",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_event_add_val",
        "kernel/trace/trace_events_synth.c:synth_event_add_next_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581677632,
      "name": "__synth_event_add_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    },
    {
      "addr": 18446744071596527625,
      "name": "__synth_event_add_val.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int __synth_event_add_val(const char * field_name, u64 val, struct synth_event_trace_state * trace_state)
```

```json
{
  "name": "__synth_event_add_val",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__synth_event_add_val",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:1944",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_event_add_val",
        "kernel/trace/trace_events_synth.c:synth_event_add_next_val"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793776,
      "name": "__synth_event_add_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    },
    {
      "addr": 18446744071597428237,
      "name": "__synth_event_add_val.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int __synth_event_add_val(const char * field_name, u64 val, struct synth_event_trace_state * trace_state)
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
