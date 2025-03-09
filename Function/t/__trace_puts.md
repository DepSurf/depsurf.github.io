# Function: <code>__trace_puts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580216704,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:541",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580216704,
      "name": "__trace_puts.part.52",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071580217008,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580253859,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:776",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580253536,
      "name": "__trace_puts.part.57",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    },
    {
      "addr": 18446744071580253808,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580297379,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:819",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot",
        "kernel/trace/trace.c:tracing_snapshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580291344,
      "name": "__trace_puts.part.48",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
    },
    {
      "addr": 18446744071580291680,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580310595,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:811",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580304496,
      "name": "__trace_puts.part.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
    },
    {
      "addr": 18446744071580304864,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580363731,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:811",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580357552,
      "name": "__trace_puts.part.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
    },
    {
      "addr": 18446744071580357920,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580425201,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:810",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580419360,
      "name": "__trace_puts.part.50",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071580419696,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580480945,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:811",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance",
        "kernel/trace/trace.c:tracing_snapshot_instance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580475024,
      "name": "__trace_puts.part.50",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071580475360,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580536753,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:815",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580530704,
      "name": "__trace_puts.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071580531056,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580584289,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:833",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580578304,
      "name": "__trace_puts.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071580578656,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580682999,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:854",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669824,
      "name": "__trace_puts.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    },
    {
      "addr": 18446744071580670192,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580673831,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:1005",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580660064,
      "name": "__trace_puts.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    },
    {
      "addr": 18446744071580660432,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580674822,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:1008",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580674304,
      "name": "__trace_puts.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
    },
    {
      "addr": 18446744071580674656,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580848560,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:1021",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580848560,
      "name": "__trace_puts.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
    },
    {
      "addr": 18446744071592170170,
      "name": "__trace_puts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580848912,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:1011",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:ftrace_boot_snapshot",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593943947,
      "name": "__trace_puts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581079024,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:1010",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:ftrace_boot_snapshot",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596004894,
      "name": "__trace_puts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581385952,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581480912,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:1101",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581480912,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581591760,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:1103",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581591760,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491881688,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:833",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491870520,
      "name": "__trace_puts.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
    },
    {
      "addr": 18446603336491870984,
      "name": "__trace_puts",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225823784,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:833",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225809176,
      "name": "__trace_puts.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    },
    {
      "addr": 3225809556,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284960124,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:833",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284937392,
      "name": "__trace_puts.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    },
    {
      "addr": 13835058055284938032,
      "name": "__trace_puts",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272172022,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:833",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272162768,
      "name": "__trace_puts.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 18446743936272163144,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580553089,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:833",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580547104,
      "name": "__trace_puts.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071580547456,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580499825,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:833",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580493936,
      "name": "__trace_puts.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    },
    {
      "addr": 18446744071580494272,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580544337,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:833",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580538352,
      "name": "__trace_puts.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071580538704,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __trace_puts(long unsigned int ip, const char * str, int size)
```

```json
{
  "name": "__trace_puts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580600913,
      "name": "__trace_puts",
      "external": true,
      "loc": "kernel/trace/trace.c:833",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580594864,
      "name": "__trace_puts.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071580595216,
      "name": "__trace_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
