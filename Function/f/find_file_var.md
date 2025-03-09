# Function: <code>find_file_var</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct hist_field * find_file_var(struct trace_event_file * file, const char * var_name)
```

```json
{
  "name": "find_file_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580535808,
      "name": "find_file_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1533",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580535808,
      "name": "find_file_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
struct hist_field * find_file_var(struct trace_event_file * file, const char * var_name)
```

```json
{
  "name": "find_file_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580594240,
      "name": "find_file_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1617",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580594240,
      "name": "find_file_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
struct hist_field * find_file_var(struct trace_event_file * file, const char * var_name)
```

```json
{
  "name": "find_file_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580651712,
      "name": "find_file_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1771",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580651712,
      "name": "find_file_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
struct hist_field * find_file_var(struct trace_event_file * file, const char * var_name)
```

```json
{
  "name": "find_file_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580698272,
      "name": "find_file_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1847",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580698272,
      "name": "find_file_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_file_var",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580826974,
      "name": "find_file_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:938",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_match_var"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_file_var",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580817230,
      "name": "find_file_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:941",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_match_var"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_file_var",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580823931,
      "name": "find_file_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:957",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_file_var",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581020651,
      "name": "find_file_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:981",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_file_var",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581271436,
      "name": "find_file_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1155",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_file_var",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581595612,
      "name": "find_file_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1188",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_file_var",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581718572,
      "name": "find_file_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1185",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_file_var",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581834844,
      "name": "find_file_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1178",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct hist_field * find_file_var(struct trace_event_file * file, const char * var_name)
```

```json
{
  "name": "find_file_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492008096,
      "name": "find_file_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1847",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492008096,
      "name": "find_file_var",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct hist_field * find_file_var(struct trace_event_file * file, const char * var_name)
```

```json
{
  "name": "find_file_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285144272,
      "name": "find_file_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1847",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285144272,
      "name": "find_file_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
struct hist_field * find_file_var(struct trace_event_file * file, const char * var_name)
```

```json
{
  "name": "find_file_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580667072,
      "name": "find_file_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1847",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580667072,
      "name": "find_file_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
struct hist_field * find_file_var(struct trace_event_file * file, const char * var_name)
```

```json
{
  "name": "find_file_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580613280,
      "name": "find_file_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1847",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580613280,
      "name": "find_file_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
struct hist_field * find_file_var(struct trace_event_file * file, const char * var_name)
```

```json
{
  "name": "find_file_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580658320,
      "name": "find_file_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1847",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580658320,
      "name": "find_file_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
struct hist_field * find_file_var(struct trace_event_file * file, const char * var_name)
```

```json
{
  "name": "find_file_var",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580715824,
      "name": "find_file_var",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1847",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580715824,
      "name": "find_file_var",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct hist_field * find_file_var(struct trace_event_file * file, const char * var_name)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct hist_field * find_file_var(struct trace_event_file * file, const char * var_name)
```
</details>
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
struct hist_field * find_file_var(struct trace_event_file * file, const char * var_name)
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
struct hist_field * find_file_var(struct trace_event_file * file, const char * var_name)
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
