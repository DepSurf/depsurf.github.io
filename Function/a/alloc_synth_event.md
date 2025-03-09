# Function: <code>alloc_synth_event</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580565715,
      "name": "alloc_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:953",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:create_synth_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580612558,
      "name": "alloc_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1043",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580682562,
      "name": "alloc_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1197",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580729842,
      "name": "alloc_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1267",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct synth_event * alloc_synth_event(const char * name, int n_fields, struct synth_field * * fields)
```

```json
{
  "name": "alloc_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580808912,
      "name": "alloc_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:671",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580808912,
      "name": "alloc_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
struct synth_event * alloc_synth_event(const char * name, int n_fields, struct synth_field * * fields)
```

```json
{
  "name": "alloc_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580798608,
      "name": "alloc_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:834",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580798608,
      "name": "alloc_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
struct synth_event * alloc_synth_event(const char * name, int n_fields, struct synth_field * * fields)
```

```json
{
  "name": "alloc_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580803312,
      "name": "alloc_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:852",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580803312,
      "name": "alloc_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
struct synth_event * alloc_synth_event(const char * name, int n_fields, struct synth_field * * fields)
```

```json
{
  "name": "alloc_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:852",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580997968,
      "name": "alloc_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
    },
    {
      "addr": 18446744071592177153,
      "name": "alloc_synth_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
struct synth_event * alloc_synth_event(const char * name, int n_fields, struct synth_field * * fields)
```

```json
{
  "name": "alloc_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:860",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581243744,
      "name": "alloc_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
    },
    {
      "addr": 18446744071593950721,
      "name": "alloc_synth_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
struct synth_event * alloc_synth_event(const char * name, int n_fields, struct synth_field * * fields)
```

```json
{
  "name": "alloc_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:870",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581564048,
      "name": "alloc_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
    },
    {
      "addr": 18446744071596009174,
      "name": "alloc_synth_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
struct synth_event * alloc_synth_event(const char * name, int n_fields, struct synth_field * * fields)
```

```json
{
  "name": "alloc_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:942",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581682944,
      "name": "alloc_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
    },
    {
      "addr": 18446744071596528069,
      "name": "alloc_synth_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
struct synth_event * alloc_synth_event(const char * name, int n_fields, struct synth_field * * fields)
```

```json
{
  "name": "alloc_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:943",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:__create_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581799200,
      "name": "alloc_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
    },
    {
      "addr": 18446744071597428681,
      "name": "alloc_synth_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492039972,
      "name": "alloc_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1267",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "alloc_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285207512,
      "name": "alloc_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1267",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580698642,
      "name": "alloc_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1267",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580644850,
      "name": "alloc_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1267",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580689890,
      "name": "alloc_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1267",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580747394,
      "name": "alloc_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1267",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:__create_synth_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct synth_event * alloc_synth_event(const char * name, int n_fields, struct synth_field * * fields)
```
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
