# Function: <code>find_var_file</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct trace_event_file * find_var_file(struct trace_array * tr, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_var_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580545936,
      "name": "find_var_file",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1502",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545936,
      "name": "find_var_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct trace_event_file * find_var_file(struct trace_array * tr, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_var_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580605056,
      "name": "find_var_file",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1586",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580605056,
      "name": "find_var_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct trace_event_file * find_var_file(struct trace_array * tr, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_var_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580662176,
      "name": "find_var_file",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1740",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580662176,
      "name": "find_var_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct trace_event_file * find_var_file(struct trace_array * tr, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_var_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580709360,
      "name": "find_var_file",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1816",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580709360,
      "name": "find_var_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
  "name": "find_var_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580827136,
      "name": "find_var_file",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:907",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_match_var"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_match_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580826224,
      "name": "find_var_file.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
  "name": "find_var_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580817392,
      "name": "find_var_file",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:910",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_match_var"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_match_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816272,
      "name": "find_var_file.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
  "name": "find_var_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580824342,
      "name": "find_var_file",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:926",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580821232,
      "name": "find_var_file.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_var_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581021130,
      "name": "find_var_file",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:950",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581018672,
      "name": "find_var_file.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_var_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581271956,
      "name": "find_var_file",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1124",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268112,
      "name": "find_var_file.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_var_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581596132,
      "name": "find_var_file",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1157",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581592096,
      "name": "find_var_file.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_var_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581719095,
      "name": "find_var_file",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1154",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714080,
      "name": "find_var_file.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_var_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581835367,
      "name": "find_var_file",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1147",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581830032,
      "name": "find_var_file.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct trace_event_file * find_var_file(struct trace_array * tr, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_var_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492020928,
      "name": "find_var_file",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1816",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492020928,
      "name": "find_var_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct trace_event_file * find_var_file(struct trace_array * tr, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_var_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285164480,
      "name": "find_var_file",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1816",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285164480,
      "name": "find_var_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct trace_event_file * find_var_file(struct trace_array * tr, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_var_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580678160,
      "name": "find_var_file",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1816",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580678160,
      "name": "find_var_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct trace_event_file * find_var_file(struct trace_array * tr, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_var_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580624368,
      "name": "find_var_file",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1816",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580624368,
      "name": "find_var_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct trace_event_file * find_var_file(struct trace_array * tr, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_var_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580669408,
      "name": "find_var_file",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1816",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669408,
      "name": "find_var_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct trace_event_file * find_var_file(struct trace_array * tr, char * system, char * event_name, char * var_name)
```

```json
{
  "name": "find_var_file",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580726912,
      "name": "find_var_file",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1816",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:find_event_var",
        "kernel/trace/trace_events_hist.c:find_event_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580726912,
      "name": "find_var_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
struct trace_event_file * find_var_file(struct trace_array * tr, char * system, char * event_name, char * var_name)
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
struct trace_event_file * find_var_file(struct trace_array * tr, char * system, char * event_name, char * var_name)
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
struct trace_event_file * find_var_file(struct trace_array * tr, char * system, char * event_name, char * var_name)
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
struct trace_event_file * find_var_file(struct trace_array * tr, char * system, char * event_name, char * var_name)
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
