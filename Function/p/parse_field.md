# Function: <code>parse_field</code>

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
  "name": "parse_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580550977,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2441",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_atom"
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
  "name": "parse_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580606113,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2559",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_atom"
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
  "name": "parse_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580663307,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2713",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_atom"
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
  "name": "parse_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580710491,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2824",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_atom"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
int parse_field(char * str, struct trace_event_call * call, struct ftrace_event_field * * pf, u64 * pv)
```

```json
{
  "name": "parse_field",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580799712,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:36",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_inject.c:parse_entry"
      ]
    },
    {
      "addr": 18446744071580818240,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1919",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580799712,
      "name": "parse_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
    },
    {
      "addr": 18446744071580818240,
      "name": "parse_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
int parse_field(char * str, struct trace_event_call * call, struct ftrace_event_field * * pf, u64 * pv)
```

```json
{
  "name": "parse_field",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580787696,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:36",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_inject.c:parse_entry"
      ]
    },
    {
      "addr": 18446744071580809056,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1929",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580787696,
      "name": "parse_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
    },
    {
      "addr": 18446744071580809056,
      "name": "parse_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
int parse_field(char * str, struct trace_event_call * call, struct ftrace_event_field * * pf, u64 * pv)
```

```json
{
  "name": "parse_field",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580793168,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:36",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_inject.c:parse_entry"
      ]
    },
    {
      "addr": 18446744071580813728,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1955",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580793168,
      "name": "parse_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
    },
    {
      "addr": 18446744071580813728,
      "name": "parse_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
int parse_field(char * str, struct trace_event_call * call, struct ftrace_event_field * * pf, u64 * pv)
```

```json
{
  "name": "parse_field",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580987520,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:36",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_inject.c:parse_entry"
      ]
    },
    {
      "addr": 18446744071581006048,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1989",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580987520,
      "name": "parse_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
    },
    {
      "addr": 18446744071581006048,
      "name": "parse_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 750
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int parse_field(char * str, struct trace_event_call * call, struct ftrace_event_field * * pf, u64 * pv)
```

```json
{
  "name": "parse_field",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581233472,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:36",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581274256,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2247",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581233472,
      "name": "parse_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 658
    },
    {
      "addr": 18446744071581274256,
      "name": "parse_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 879
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int parse_field(char * str, struct trace_event_call * call, struct ftrace_event_field * * pf, u64 * pv)
```

```json
{
  "name": "parse_field",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581554384,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:36",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581598448,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2287",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581554384,
      "name": "parse_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 658
    },
    {
      "addr": 18446744071581598448,
      "name": "parse_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1002
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
int parse_field(char * str, struct trace_event_call * call, struct ftrace_event_field * * pf, u64 * pv)
```

```json
{
  "name": "parse_field",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581672928,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:36",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581720704,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2301",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581672928,
      "name": "parse_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 658
    },
    {
      "addr": 18446744071581720704,
      "name": "parse_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1094
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
int parse_field(char * str, struct trace_event_call * call, struct ftrace_event_field * * pf, u64 * pv)
```

```json
{
  "name": "parse_field",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581789072,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_inject.c:36",
      "file": "kernel/trace/trace_events_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581837024,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2294",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_atom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581789072,
      "name": "parse_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 658
    },
    {
      "addr": 18446744071581837024,
      "name": "parse_field",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1094
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
  "name": "parse_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492022068,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2824",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_atom"
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
  "name": "parse_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285179276,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2824",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_atom"
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
  "name": "parse_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580679291,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2824",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_atom"
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
  "name": "parse_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580625499,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2824",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_atom"
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
  "name": "parse_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580670539,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2824",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_atom"
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
  "name": "parse_field",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580728043,
      "name": "parse_field",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2824",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_atom"
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
int parse_field(char * str, struct trace_event_call * call, struct ftrace_event_field * * pf, u64 * pv)
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
