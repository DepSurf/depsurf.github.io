# Function: <code>ring_buffer_empty_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool ring_buffer_empty_cpu(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580188912,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4301",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580188912,
      "name": "ring_buffer_empty_cpu.part.41",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071580189056,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
bool ring_buffer_empty_cpu(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580233976,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4296",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580222960,
      "name": "ring_buffer_empty_cpu.part.41",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071580223088,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool ring_buffer_empty_cpu(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580274921,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4265",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268368,
      "name": "ring_buffer_empty_cpu.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071580268496,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool ring_buffer_empty_cpu(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580287225,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4279",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580282368,
      "name": "ring_buffer_empty_cpu.part.39",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071580282512,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool ring_buffer_empty_cpu(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580340670,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4271",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580333792,
      "name": "ring_buffer_empty_cpu.part.39",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071580333936,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
bool ring_buffer_empty_cpu(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580402111,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4433",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580396368,
      "name": "ring_buffer_empty_cpu.part.41",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071580396512,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
bool ring_buffer_empty_cpu(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580457407,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4502",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580449040,
      "name": "ring_buffer_empty_cpu.part.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071580449184,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
bool ring_buffer_empty_cpu(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580504336,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4480",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580504336,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
bool ring_buffer_empty_cpu(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580552144,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4481",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580552144,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
bool ring_buffer_empty_cpu(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580652858,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4572",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:trace_empty",
        "kernel/trace/trace.c:trace_empty",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580643808,
      "name": "ring_buffer_empty_cpu.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071580643952,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
bool ring_buffer_empty_cpu(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580643194,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5182",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:trace_empty",
        "kernel/trace/trace.c:trace_empty",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580634528,
      "name": "ring_buffer_empty_cpu.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071580634672,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
bool ring_buffer_empty_cpu(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580645898,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5291",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:trace_empty",
        "kernel/trace/trace.c:trace_empty",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641296,
      "name": "ring_buffer_empty_cpu.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071580641456,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
bool ring_buffer_empty_cpu(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580818490,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5296",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:trace_empty",
        "kernel/trace/trace.c:trace_empty",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580813824,
      "name": "ring_buffer_empty_cpu.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071580813984,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool ring_buffer_empty_cpu(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581043044,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5338",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:trace_empty",
        "kernel/trace/trace.c:trace_empty",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581022400,
      "name": "ring_buffer_empty_cpu.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071581022544,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool ring_buffer_empty_cpu(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581345754,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5445",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:trace_empty",
        "kernel/trace/trace.c:trace_empty",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323568,
      "name": "ring_buffer_empty_cpu.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071581323744,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool ring_buffer_empty_cpu(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581439930,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5468",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:trace_empty",
        "kernel/trace/trace.c:trace_empty",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581418416,
      "name": "ring_buffer_empty_cpu.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071581418592,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool ring_buffer_empty_cpu(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581549345,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5385",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:rb_watermark_hit"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:rb_watermark_hit",
        "kernel/trace/trace.c:trace_empty",
        "kernel/trace/trace.c:trace_empty",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581526560,
      "name": "ring_buffer_empty_cpu.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071581526736,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
bool ring_buffer_empty_cpu(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491836144,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4481",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491836144,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
bool ring_buffer_empty_cpu(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225776268,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4481",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225776268,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
bool ring_buffer_empty_cpu(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284894592,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4481",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284894592,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
bool ring_buffer_empty_cpu(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272141972,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4481",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272141972,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
bool ring_buffer_empty_cpu(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580520944,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4481",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580520944,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
bool ring_buffer_empty_cpu(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580461264,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4481",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580461264,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
bool ring_buffer_empty_cpu(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580512192,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4481",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580512192,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
bool ring_buffer_empty_cpu(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_empty_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580568528,
      "name": "ring_buffer_empty_cpu",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4481",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait",
        "kernel/trace/trace.c:__find_next_entry",
        "kernel/trace/trace.c:__find_next_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580568528,
      "name": "ring_buffer_empty_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ring_buffer * buffer</code> ➡️ <code>struct trace_buffer * buffer</code>
</li>
</ul>
</details>
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
