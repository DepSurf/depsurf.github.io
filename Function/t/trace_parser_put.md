# Function: <code>trace_parser_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580213072,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:914",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_write",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580213072,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580249307,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1149",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_write",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580248400,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580294683,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1193",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_write",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293776,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580307999,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1191",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580307056,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580361071,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1191",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580360128,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580422943,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1198",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580421952,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580478687,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1199",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580477696,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580534319,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1370",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580533520,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580581919,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1388",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580581120,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580681153,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1423",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580680352,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580672063,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1574",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580671184,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580670821,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1571",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669920,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580845749,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1586",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844800,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581073786,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1577",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581072992,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581380266,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1583",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379376,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581474842,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1634",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581473968,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581585818,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1644",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581584944,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491878980,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1388",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491877200,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225820940,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1388",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225819836,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284955512,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1388",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284953904,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272169904,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1388",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272169036,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580550719,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1388",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580549920,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580497487,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1388",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580496688,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580541967,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1388",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541168,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void trace_parser_put(struct trace_parser * parser)
```

```json
{
  "name": "trace_parser_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580598511,
      "name": "trace_parser_put",
      "external": true,
      "loc": "kernel/trace/trace.c:1388",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace_events.c:ftrace_event_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580597712,
      "name": "trace_parser_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
