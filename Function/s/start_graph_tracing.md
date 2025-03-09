# Function: <code>start_graph_tracing</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580179667,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5743",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:register_ftrace_graph"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580214549,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5776",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:register_ftrace_graph"
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
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580255317,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5825",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:register_ftrace_graph"
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
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580268447,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6606",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:register_ftrace_graph"
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
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580321919,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6905",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:register_ftrace_graph"
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
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580382565,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6892",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:register_ftrace_graph"
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
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580551378,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/fgraph.c:537",
      "file": "kernel/trace/fgraph.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/fgraph.c:register_ftrace_graph"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int start_graph_tracing()
```

```json
{
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/fgraph.c:537",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fgraph.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580608096,
      "name": "start_graph_tracing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
    },
    {
      "addr": 18446744071580609183,
      "name": "start_graph_tracing.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int start_graph_tracing()
```

```json
{
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/fgraph.c:537",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fgraph.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580655072,
      "name": "start_graph_tracing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
    },
    {
      "addr": 18446744071580656068,
      "name": "start_graph_tracing.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int start_graph_tracing()
```

```json
{
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/fgraph.c:565",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fgraph.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757376,
      "name": "start_graph_tracing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071580758084,
      "name": "start_graph_tracing.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int start_graph_tracing()
```

```json
{
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/fgraph.c:562",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fgraph.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580745440,
      "name": "start_graph_tracing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071591321010,
      "name": "start_graph_tracing.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int start_graph_tracing()
```

```json
{
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/fgraph.c:562",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fgraph.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749904,
      "name": "start_graph_tracing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    },
    {
      "addr": 18446744071591263184,
      "name": "start_graph_tracing.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int start_graph_tracing()
```

```json
{
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/fgraph.c:562",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fgraph.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933456,
      "name": "start_graph_tracing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    },
    {
      "addr": 18446744071592173962,
      "name": "start_graph_tracing.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int start_graph_tracing()
```

```json
{
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/fgraph.c:575",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fgraph.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581173472,
      "name": "start_graph_tracing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
    },
    {
      "addr": 18446744071593947513,
      "name": "start_graph_tracing.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int start_graph_tracing()
```

```json
{
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581488496,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/fgraph.c:575",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fgraph.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581488496,
      "name": "start_graph_tracing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
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
int start_graph_tracing()
```

```json
{
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581606432,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/fgraph.c:600",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fgraph.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581606432,
      "name": "start_graph_tracing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
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
int start_graph_tracing()
```

```json
{
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581718912,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/fgraph.c:600",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fgraph.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581718912,
      "name": "start_graph_tracing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 717
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
int start_graph_tracing()
```

```json
{
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491959656,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/fgraph.c:537",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fgraph.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491959656,
      "name": "start_graph_tracing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int start_graph_tracing()
```

```json
{
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225895328,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/fgraph.c:537",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fgraph.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225895328,
      "name": "start_graph_tracing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int start_graph_tracing()
```

```json
{
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285066064,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/fgraph.c:537",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fgraph.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285066064,
      "name": "start_graph_tracing",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272233788,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/fgraph.c:537",
      "file": "kernel/trace/fgraph.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/fgraph.c:register_ftrace_graph"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int start_graph_tracing()
```

```json
{
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/fgraph.c:537",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fgraph.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580623872,
      "name": "start_graph_tracing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
    },
    {
      "addr": 18446744071580624868,
      "name": "start_graph_tracing.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int start_graph_tracing()
```

```json
{
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/fgraph.c:537",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fgraph.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580570128,
      "name": "start_graph_tracing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
    },
    {
      "addr": 18446744071580571124,
      "name": "start_graph_tracing.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int start_graph_tracing()
```

```json
{
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/fgraph.c:537",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fgraph.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580615120,
      "name": "start_graph_tracing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
    },
    {
      "addr": 18446744071580616116,
      "name": "start_graph_tracing.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int start_graph_tracing()
```

```json
{
  "name": "start_graph_tracing",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "start_graph_tracing",
      "external": false,
      "loc": "kernel/trace/fgraph.c:537",
      "file": "kernel/trace/fgraph.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/fgraph.c:register_ftrace_graph"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580672576,
      "name": "start_graph_tracing",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
    },
    {
      "addr": 18446744071580673604,
      "name": "start_graph_tracing.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int start_graph_tracing()
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int start_graph_tracing()
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
