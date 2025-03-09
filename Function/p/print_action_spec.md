# Function: <code>print_action_spec</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void print_action_spec(struct seq_file * m, struct hist_trigger_data * hist_data, struct action_data * data)
```

```json
{
  "name": "print_action_spec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580655232,
      "name": "print_action_spec",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4906",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580655232,
      "name": "print_action_spec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
void print_action_spec(struct seq_file * m, struct hist_trigger_data * hist_data, struct action_data * data)
```

```json
{
  "name": "print_action_spec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580701824,
      "name": "print_action_spec",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5016",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580701824,
      "name": "print_action_spec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
void print_action_spec(struct seq_file * m, struct hist_trigger_data * hist_data, struct action_data * data)
```

```json
{
  "name": "print_action_spec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580812128,
      "name": "print_action_spec",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4124",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:print_actions_spec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580812128,
      "name": "print_action_spec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
void print_action_spec(struct seq_file * m, struct hist_trigger_data * hist_data, struct action_data * data)
```

```json
{
  "name": "print_action_spec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580802336,
      "name": "print_action_spec",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4149",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:print_actions_spec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580802336,
      "name": "print_action_spec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
void print_action_spec(struct seq_file * m, struct hist_trigger_data * hist_data, struct action_data * data)
```

```json
{
  "name": "print_action_spec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580808096,
      "name": "print_action_spec",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4217",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580808096,
      "name": "print_action_spec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
void print_action_spec(struct seq_file * m, struct hist_trigger_data * hist_data, struct action_data * data)
```

```json
{
  "name": "print_action_spec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_action_spec",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4312",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006960,
      "name": "print_action_spec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    },
    {
      "addr": 18446744071592177263,
      "name": "print_action_spec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void print_action_spec(struct seq_file * m, struct hist_trigger_data * hist_data, struct action_data * data)
```

```json
{
  "name": "print_action_spec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_action_spec",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4691",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581255840,
      "name": "print_action_spec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446744071593950989,
      "name": "print_action_spec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void print_action_spec(struct seq_file * m, struct hist_trigger_data * hist_data, struct action_data * data)
```

```json
{
  "name": "print_action_spec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_action_spec",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4822",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581576272,
      "name": "print_action_spec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446744071596009629,
      "name": "print_action_spec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void print_action_spec(struct seq_file * m, struct hist_trigger_data * hist_data, struct action_data * data)
```

```json
{
  "name": "print_action_spec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_action_spec",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4899",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581696960,
      "name": "print_action_spec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446744071596528609,
      "name": "print_action_spec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void print_action_spec(struct seq_file * m, struct hist_trigger_data * hist_data, struct action_data * data)
```

```json
{
  "name": "print_action_spec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_action_spec",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4891",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581813264,
      "name": "print_action_spec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446744071597429221,
      "name": "print_action_spec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void print_action_spec(struct seq_file * m, struct hist_trigger_data * hist_data, struct action_data * data)
```

```json
{
  "name": "print_action_spec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492012424,
      "name": "print_action_spec",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5016",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492012424,
      "name": "print_action_spec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
void print_action_spec(struct seq_file * m, struct hist_trigger_data * hist_data, struct action_data * data)
```

```json
{
  "name": "print_action_spec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285150656,
      "name": "print_action_spec",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5016",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285150656,
      "name": "print_action_spec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
void print_action_spec(struct seq_file * m, struct hist_trigger_data * hist_data, struct action_data * data)
```

```json
{
  "name": "print_action_spec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580670624,
      "name": "print_action_spec",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5016",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580670624,
      "name": "print_action_spec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
void print_action_spec(struct seq_file * m, struct hist_trigger_data * hist_data, struct action_data * data)
```

```json
{
  "name": "print_action_spec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580616832,
      "name": "print_action_spec",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5016",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580616832,
      "name": "print_action_spec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
void print_action_spec(struct seq_file * m, struct hist_trigger_data * hist_data, struct action_data * data)
```

```json
{
  "name": "print_action_spec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580661872,
      "name": "print_action_spec",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5016",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580661872,
      "name": "print_action_spec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
void print_action_spec(struct seq_file * m, struct hist_trigger_data * hist_data, struct action_data * data)
```

```json
{
  "name": "print_action_spec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580719376,
      "name": "print_action_spec",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5016",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580719376,
      "name": "print_action_spec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
void print_action_spec(struct seq_file * m, struct hist_trigger_data * hist_data, struct action_data * data)
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
void print_action_spec(struct seq_file * m, struct hist_trigger_data * hist_data, struct action_data * data)
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
void print_action_spec(struct seq_file * m, struct hist_trigger_data * hist_data, struct action_data * data)
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
