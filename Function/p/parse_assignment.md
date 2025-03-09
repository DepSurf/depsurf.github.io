# Function: <code>parse_assignment</code>

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
  "name": "parse_assignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580554148,
      "name": "parse_assignment",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1814",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
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
  "name": "parse_assignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580618165,
      "name": "parse_assignment",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1898",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
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
  "name": "parse_assignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580673839,
      "name": "parse_assignment",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2050",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs"
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
  "name": "parse_assignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580720962,
      "name": "parse_assignment",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2122",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs"
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
int parse_assignment(struct trace_array * tr, char * str, struct hist_trigger_attrs * attrs)
```

```json
{
  "name": "parse_assignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580817456,
      "name": "parse_assignment",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1213",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580817456,
      "name": "parse_assignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
int parse_assignment(struct trace_array * tr, char * str, struct hist_trigger_attrs * attrs)
```

```json
{
  "name": "parse_assignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580808272,
      "name": "parse_assignment",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1216",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580808272,
      "name": "parse_assignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
int parse_assignment(struct trace_array * tr, char * str, struct hist_trigger_attrs * attrs)
```

```json
{
  "name": "parse_assignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580812800,
      "name": "parse_assignment",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1233",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580812800,
      "name": "parse_assignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
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
int parse_assignment(struct trace_array * tr, char * str, struct hist_trigger_attrs * attrs)
```

```json
{
  "name": "parse_assignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_assignment",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1258",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581004832,
      "name": "parse_assignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 747
    },
    {
      "addr": 18446744071592177217,
      "name": "parse_assignment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int parse_assignment(struct trace_array * tr, char * str, struct hist_trigger_attrs * attrs)
```

```json
{
  "name": "parse_assignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_assignment",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1432",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581254240,
      "name": "parse_assignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 734
    },
    {
      "addr": 18446744071593950944,
      "name": "parse_assignment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int parse_assignment(struct trace_array * tr, char * str, struct hist_trigger_attrs * attrs)
```

```json
{
  "name": "parse_assignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_assignment",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1461",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581574576,
      "name": "parse_assignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 734
    },
    {
      "addr": 18446744071596009584,
      "name": "parse_assignment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int parse_assignment(struct trace_array * tr, char * str, struct hist_trigger_attrs * attrs)
```

```json
{
  "name": "parse_assignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_assignment",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1466",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581695264,
      "name": "parse_assignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 734
    },
    {
      "addr": 18446744071596528564,
      "name": "parse_assignment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int parse_assignment(struct trace_array * tr, char * str, struct hist_trigger_attrs * attrs)
```

```json
{
  "name": "parse_assignment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_assignment",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1459",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581811568,
      "name": "parse_assignment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 734
    },
    {
      "addr": 18446744071597429176,
      "name": "parse_assignment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
  "name": "parse_assignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492014216,
      "name": "parse_assignment",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2122",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs"
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
  "name": "parse_assignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285173228,
      "name": "parse_assignment",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2122",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs"
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
  "name": "parse_assignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580689762,
      "name": "parse_assignment",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2122",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs"
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
  "name": "parse_assignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580635970,
      "name": "parse_assignment",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2122",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs"
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
  "name": "parse_assignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580681010,
      "name": "parse_assignment",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2122",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs"
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
  "name": "parse_assignment",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580738514,
      "name": "parse_assignment",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2122",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs"
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
int parse_assignment(struct trace_array * tr, char * str, struct hist_trigger_attrs * attrs)
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
