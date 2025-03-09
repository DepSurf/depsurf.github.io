# Function: <code>hist_field_print</code>

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
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580360592,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1142",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580360592,
      "name": "hist_field_print.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580407696,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1142",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580407696,
      "name": "hist_field_print.isra.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580418832,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1143",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580418832,
      "name": "hist_field_print.isra.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
```

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580474368,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1185",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580474368,
      "name": "hist_field_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
```

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580538944,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4902",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580538944,
      "name": "hist_field_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
```

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580596784,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4988",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580596784,
      "name": "hist_field_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
```

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580654896,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5507",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580654896,
      "name": "hist_field_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
```

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580701440,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5623",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580701440,
      "name": "hist_field_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
```

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580823184,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5004",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823184,
      "name": "hist_field_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
```

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580814000,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5045",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580814000,
      "name": "hist_field_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
```

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580818560,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5114",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580818560,
      "name": "hist_field_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
```

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581015088,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5217",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581015088,
      "name": "hist_field_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
```

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581262944,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5597",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581262944,
      "name": "hist_field_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
```

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581581136,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5824",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581581136,
      "name": "hist_field_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
```

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581701840,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5925",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581701840,
      "name": "hist_field_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
```

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581818144,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5921",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581818144,
      "name": "hist_field_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
```

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492011800,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5623",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492011800,
      "name": "hist_field_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
```

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285149792,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5623",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285149792,
      "name": "hist_field_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
```

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580670240,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5623",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580670240,
      "name": "hist_field_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
```

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580616448,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5623",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580616448,
      "name": "hist_field_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
```

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580661488,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5623",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580661488,
      "name": "hist_field_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
```

```json
{
  "name": "hist_field_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580718992,
      "name": "hist_field_print",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5623",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580718992,
      "name": "hist_field_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
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
void hist_field_print(struct seq_file * m, struct hist_field * hist_field)
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
