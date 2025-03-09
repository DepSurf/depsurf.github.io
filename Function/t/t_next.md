# Function: <code>t_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580159840,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3104",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:t_start"
      ]
    },
    {
      "addr": 18446744071580198976,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:3272",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580247328,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:287",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580253552,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:297",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580276352,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:860",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474832,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:110",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580159840,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071580198976,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071580247328,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071580253552,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071580276352,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071581474832,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580194928,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3124",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:t_start"
      ]
    },
    {
      "addr": 18446744071580234682,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:3609",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580285040,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:292",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580296688,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:301",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580321445,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:895",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659328,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:110",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580194928,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071580234336,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071580285040,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580296688,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071580319696,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071581659328,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580235536,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3142",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:t_start"
      ]
    },
    {
      "addr": 18446744071580275844,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:3833",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580328656,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:292",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580342576,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:301",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580367442,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:864",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581747856,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:110",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580235536,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    },
    {
      "addr": 18446744071580275504,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071580328656,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580342576,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580365856,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071581747856,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580249344,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3390",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580288183,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4063",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580340864,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:292",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580355760,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:307",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580378833,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:904",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581801648,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:110",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580249344,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071580287840,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071580340864,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580355760,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580377536,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071581801648,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580301424,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3358",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580341623,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4078",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580394288,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:292",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580409456,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:297",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580434065,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:904",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581951184,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:112",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580301424,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071580341280,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071580394288,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580409456,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580432720,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071581951184,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580362400,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3347",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580403460,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4084",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580456208,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:292",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580471248,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:297",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580495825,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:902",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582136720,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:112",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580362400,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071580402784,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580456208,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580471248,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071580494544,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071582136720,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580418320,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3306",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580458756,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4088",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580511680,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:293",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580526928,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:297",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580553537,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:903",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582231264,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:112",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580418320,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071580458080,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580511680,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580526928,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071580552256,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071582231264,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580472048,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3312",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580513209,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4293",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580568672,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:293",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580583344,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:271",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580610753,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:896",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582395536,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:112",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580472048,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071580512848,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580568672,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580583344,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580609232,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071582395536,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580520192,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3313",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580560761,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4322",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580615776,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:294",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580630464,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:389",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580658465,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:897",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582494448,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:112",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580520192,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071580560400,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580615776,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580630464,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580656128,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071582494448,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580611312,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3432",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580662281,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4509",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580714368,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:294",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580731088,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:389",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580764161,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:971",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582794336,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:112",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580611312,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071580662368,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580714368,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071580731088,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580758160,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071582794336,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580601504,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3510",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580653081,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4577",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580703840,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:294",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580720144,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:388",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580751969,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:972",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582867904,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:112",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580601504,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071580653168,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580703840,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071580720144,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580746208,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071582867904,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580604432,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3510",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580654873,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4915",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580708432,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:305",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580725184,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:388",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580757809,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1179",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582896320,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:112",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580604432,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071580654960,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580708432,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    },
    {
      "addr": 18446744071580725184,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580750992,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071582896320,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580775792,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3511",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580829195,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4989",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580886256,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:305",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580905968,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:388",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580941825,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1180",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583229872,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:112",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580775792,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071580828992,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071592168670,
      "name": "t_next.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071580886256,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    },
    {
      "addr": 18446744071580905968,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580934496,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071583229872,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580993680,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3523",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581055355,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4990",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581118448,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:305",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581142272,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:388",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581185153,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1200",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583728304,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:112",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993680,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071581055136,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071593942276,
      "name": "t_next.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071581118448,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071581142272,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071581174592,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071583728304,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581292000,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3543",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581357371,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:5014",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581428064,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:305",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581454624,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:388",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581499265,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1215",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584340896,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:110",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581292000,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071581357136,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071596004046,
      "name": "t_next.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071581428064,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071581454624,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071581489728,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071584340896,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581387104,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3635",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581451867,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:5118",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581524816,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:305",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581572032,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:388",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581617313,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1211",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584570992,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:110",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581387104,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071581451632,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071596522629,
      "name": "t_next.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071581524816,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071581572032,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071581607680,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071584570992,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581495120,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3601",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581561675,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:5136",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581636560,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:305",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581684288,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:388",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581730497,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1220",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584802752,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:110",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581495120,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071581561440,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071597423328,
      "name": "t_next.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071581636560,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071581684288,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071581720320,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071584802752,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491801056,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3313",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491851992,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4322",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491916088,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:294",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491933912,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:389",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491962776,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:897",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494118152,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:112",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491801056,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446603336491851672,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336491916088,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446603336491933912,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446603336491961008,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446603336494118152,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225748624,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3313",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225796596,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4322",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3225857444,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:294",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225869896,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:389",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225898396,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:897",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3227567160,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:112",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225748624,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 3225795820,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 3225857444,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 3225869896,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 3225896508,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 3227567160,
      "name": "t_next",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284856208,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3313",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284919944,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4322",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285009216,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:294",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285033232,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:389",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285073384,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:897",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287789312,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:112",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284856208,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    },
    {
      "addr": 13835058055284919360,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 13835058055285009216,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 13835058055285033232,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 13835058055285067792,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 13835058055287789312,
      "name": "t_next",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272113234,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3313",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272149390,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4322",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272201012,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:294",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272210524,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:389",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272236858,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:897",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273601028,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:112",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272113234,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446743936272148944,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446743936272201012,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446743936272210524,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446743936272234626,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446743936273601028,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580488992,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3313",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580529561,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4322",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580584576,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:294",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580599264,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:389",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580627265,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:897",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582463184,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:112",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580488992,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071580529200,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580584576,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580599264,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580624928,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071582463184,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580436016,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3313",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580476441,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4322",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580531200,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:294",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580545712,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:389",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580573505,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:897",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582400416,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:112",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580436016,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071580476080,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580531200,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580545712,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580571184,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071582400416,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580480240,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3313",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580520809,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4322",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580575824,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:294",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580590512,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:389",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580618513,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:897",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582453664,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:112",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580480240,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071580520448,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580575824,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580590512,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580616176,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071582453664,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * t_next(struct seq_file * m, void * v, loff_t * pos)
```

```json
{
  "name": "t_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580536480,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3313",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580577225,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4322",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580632560,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:294",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580647408,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:389",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580676001,
      "name": "t_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:897",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:t_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582534016,
      "name": "t_next",
      "external": false,
      "loc": "fs/proc/proc_tty.c:112",
      "file": "fs/proc/proc_tty.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580536480,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071580576896,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580632560,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580647408,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580673664,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071582534016,
      "name": "t_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
