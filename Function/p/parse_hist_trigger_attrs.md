# Function: <code>parse_hist_trigger_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580367159,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:219",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580412243,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:219",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580423456,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:220",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580479155,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:245",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580554053,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1887",
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
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580618079,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1971",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs * parse_hist_trigger_attrs(struct trace_array * tr, char * trigger_str)
```

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580673712,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2125",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580673712,
      "name": "parse_hist_trigger_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1157
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
struct hist_trigger_attrs * parse_hist_trigger_attrs(struct trace_array * tr, char * trigger_str)
```

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580720848,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2193",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580720848,
      "name": "parse_hist_trigger_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1159
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
struct hist_trigger_attrs * parse_hist_trigger_attrs(struct trace_array * tr, char * trigger_str)
```

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580828496,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1284",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580828496,
      "name": "parse_hist_trigger_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 611
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
struct hist_trigger_attrs * parse_hist_trigger_attrs(struct trace_array * tr, char * trigger_str)
```

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580818816,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1287",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580818816,
      "name": "parse_hist_trigger_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 611
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
struct hist_trigger_attrs * parse_hist_trigger_attrs(struct trace_array * tr, char * trigger_str)
```

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580822352,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1304",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580822352,
      "name": "parse_hist_trigger_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
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
struct hist_trigger_attrs * parse_hist_trigger_attrs(struct trace_array * tr, char * trigger_str)
```

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581018992,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1329",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581018992,
      "name": "parse_hist_trigger_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
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
struct hist_trigger_attrs * parse_hist_trigger_attrs(struct trace_array * tr, char * trigger_str)
```

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581270304,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1503",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581270304,
      "name": "parse_hist_trigger_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
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
struct hist_trigger_attrs * parse_hist_trigger_attrs(struct trace_array * tr, char * trigger_str)
```

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581594352,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1532",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581594352,
      "name": "parse_hist_trigger_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 760
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
struct hist_trigger_attrs * parse_hist_trigger_attrs(struct trace_array * tr, char * trigger_str)
```

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581716416,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1537",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716416,
      "name": "parse_hist_trigger_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 759
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
struct hist_trigger_attrs * parse_hist_trigger_attrs(struct trace_array * tr, char * trigger_str)
```

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581832544,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1530",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832544,
      "name": "parse_hist_trigger_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 806
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
struct hist_trigger_attrs * parse_hist_trigger_attrs(struct trace_array * tr, char * trigger_str)
```

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492014056,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2193",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492014056,
      "name": "parse_hist_trigger_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1072
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct hist_trigger_attrs * parse_hist_trigger_attrs(struct trace_array * tr, char * trigger_str)
```

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285172944,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2193",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285172944,
      "name": "parse_hist_trigger_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3920
    }
  ]
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs * parse_hist_trigger_attrs(struct trace_array * tr, char * trigger_str)
```

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580689648,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2193",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580689648,
      "name": "parse_hist_trigger_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1159
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
struct hist_trigger_attrs * parse_hist_trigger_attrs(struct trace_array * tr, char * trigger_str)
```

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580635856,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2193",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580635856,
      "name": "parse_hist_trigger_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1159
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
struct hist_trigger_attrs * parse_hist_trigger_attrs(struct trace_array * tr, char * trigger_str)
```

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580680896,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2193",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580680896,
      "name": "parse_hist_trigger_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1159
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
struct hist_trigger_attrs * parse_hist_trigger_attrs(struct trace_array * tr, char * trigger_str)
```

```json
{
  "name": "parse_hist_trigger_attrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580738400,
      "name": "parse_hist_trigger_attrs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:2193",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738400,
      "name": "parse_hist_trigger_attrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1159
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
struct hist_trigger_attrs * parse_hist_trigger_attrs(struct trace_array * tr, char * trigger_str)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct hist_trigger_attrs * parse_hist_trigger_attrs(struct trace_array * tr, char * trigger_str)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct hist_trigger_attrs * parse_hist_trigger_attrs(struct trace_array * tr, char * trigger_str)
```
</details>
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
