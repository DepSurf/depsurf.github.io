# Function: <code>t_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580174528,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3238",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580203440,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:3305",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580246576,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:293",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580254048,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:350",
      "file": "kernel/trace/trace_stack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580279136,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:932",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580174528,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    },
    {
      "addr": 18446744071580203440,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071580246576,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071580254048,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071580279136,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580204320,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3258",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580238800,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:3642",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580284256,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:298",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580297184,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:354",
      "file": "kernel/trace/trace_stack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580322544,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:967",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204320,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
    },
    {
      "addr": 18446744071580238800,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071580284256,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071580297184,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071580322544,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580245024,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3276",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580280400,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:3866",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580327872,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:298",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580343056,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:354",
      "file": "kernel/trace/trace_stack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580368720,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:936",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580245024,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
    },
    {
      "addr": 18446744071580280400,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071580327872,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071580343056,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071580368720,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580255744,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3502",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580298672,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4096",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580340080,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:298",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580356192,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:354",
      "file": "kernel/trace/trace_stack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580380176,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:976",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580255744,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
    },
    {
      "addr": 18446744071580298672,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071580340080,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071580356192,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071580380176,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580307696,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3470",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580351824,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4111",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580393504,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:298",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580409888,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:344",
      "file": "kernel/trace/trace_stack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580435424,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:976",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580307696,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
    },
    {
      "addr": 18446744071580351824,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071580393504,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071580409888,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071580435424,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580368336,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3459",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580412976,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4117",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580455392,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:298",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580471664,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:344",
      "file": "kernel/trace/trace_stack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580497120,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:974",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580368336,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
    },
    {
      "addr": 18446744071580412976,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071580455392,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071580471664,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071580497120,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580424736,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3418",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580468528,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4121",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580510864,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:299",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580527344,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:344",
      "file": "kernel/trace/trace_stack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580554832,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:975",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580424736,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
    },
    {
      "addr": 18446744071580468528,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071580510864,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071580527344,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071580554832,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580477376,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3424",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580523376,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4326",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580567856,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:299",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580583760,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:318",
      "file": "kernel/trace/trace_stack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580611968,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:968",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580477376,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    },
    {
      "addr": 18446744071580523376,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071580567856,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071580583760,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071580611968,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580526400,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3425",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580570912,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4355",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580614960,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:300",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580630896,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:436",
      "file": "kernel/trace/trace_stack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580658688,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:969",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580526400,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    },
    {
      "addr": 18446744071580570912,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071580614960,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071580630896,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071580658688,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580615856,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3544",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580660240,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4542",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580713680,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:300",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580731168,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:436",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580765744,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1043",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580615856,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
    },
    {
      "addr": 18446744071580660240,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071580713680,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071580731168,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071580765744,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580606256,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3622",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580651104,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4610",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580703168,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:300",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580720224,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:435",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580753856,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1044",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580606256,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
    },
    {
      "addr": 18446744071580651104,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071580703168,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071580720224,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071580753856,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580608768,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3622",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580653328,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4948",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580707760,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:311",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580725264,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:435",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580759280,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1251",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580608768,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
    },
    {
      "addr": 18446744071580653328,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071580707760,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071580725264,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071580759280,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580780320,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3623",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580827248,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:5022",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580885104,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:311",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580906048,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:435",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580943152,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1252",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580780320,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 817
    },
    {
      "addr": 18446744071580827248,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071580885104,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071580906048,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    },
    {
      "addr": 18446744071580943152,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580999920,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3734",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581053216,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:5023",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581117120,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:311",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581142384,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:435",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581187760,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1272",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580999920,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 892
    },
    {
      "addr": 18446744071581053216,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071581117120,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071581142384,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
    },
    {
      "addr": 18446744071581187760,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581299600,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3754",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581354784,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:5047",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581426592,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:311",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581454768,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:435",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581501408,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1287",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581299600,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 892
    },
    {
      "addr": 18446744071581354784,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071581426592,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071581454768,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
    },
    {
      "addr": 18446744071581501408,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581395136,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3846",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581449200,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:5151",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581523296,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:311",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581572176,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:435",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581619472,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1283",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395136,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1100
    },
    {
      "addr": 18446744071581449200,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071581523296,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071581572176,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
    },
    {
      "addr": 18446744071581619472,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581503152,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3812",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581559008,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:5169",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581634992,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:311",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581684432,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:435",
      "file": "kernel/trace/trace_stack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581732656,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1292",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503152,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1100
    },
    {
      "addr": 18446744071581559008,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071581634992,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071581684432,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
    },
    {
      "addr": 18446744071581732656,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491807856,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3425",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491861728,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4355",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491915144,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:300",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491934200,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:436",
      "file": "kernel/trace/trace_stack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491963000,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:969",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491807856,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
    },
    {
      "addr": 18446603336491861728,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446603336491915144,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446603336491934200,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446603336491963000,
      "name": "t_show",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225756268,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3425",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225805980,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4355",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225857852,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:300",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225870268,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:436",
      "file": "kernel/trace/trace_stack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225907212,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:969",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225756268,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
    },
    {
      "addr": 3225805980,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 3225857852,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 3225870268,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 3225907212,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284865024,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3425",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284934368,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4355",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285007456,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:300",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285033728,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:436",
      "file": "kernel/trace/trace_stack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285073808,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:969",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284865024,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 968
    },
    {
      "addr": 13835058055284934368,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 13835058055285007456,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    },
    {
      "addr": 13835058055285033728,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 13835058055285073808,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272119564,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3425",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272158714,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4355",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272200134,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:300",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272211812,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:436",
      "file": "kernel/trace/trace_stack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272237028,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:969",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272119564,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
    },
    {
      "addr": 18446743936272158714,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446743936272200134,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446743936272211812,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446743936272237028,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580495200,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3425",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580539712,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4355",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580583760,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:300",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580599696,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:436",
      "file": "kernel/trace/trace_stack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580627488,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:969",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580495200,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    },
    {
      "addr": 18446744071580539712,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071580583760,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071580599696,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071580627488,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580442224,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3425",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580486560,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4355",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580530384,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:300",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580547024,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:436",
      "file": "kernel/trace/trace_stack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580573728,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:969",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580442224,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    },
    {
      "addr": 18446744071580486560,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071580530384,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071580547024,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071580573728,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580486448,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3425",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580530960,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4355",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580575008,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:300",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580590944,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:436",
      "file": "kernel/trace/trace_stack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580618736,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:969",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486448,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    },
    {
      "addr": 18446744071580530960,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071580575008,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071580590944,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071580618736,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int t_show(struct seq_file * m, void * v)
```

```json
{
  "name": "t_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580542656,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/ftrace.c:3425",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580587440,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4355",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580631744,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_printk.c:300",
      "file": "kernel/trace/trace_printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580647840,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_stack.c:436",
      "file": "kernel/trace/trace_stack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580676240,
      "name": "t_show",
      "external": false,
      "loc": "kernel/trace/trace_events.c:969",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580542656,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    },
    {
      "addr": 18446744071580587440,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071580631744,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071580647840,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071580676240,
      "name": "t_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
