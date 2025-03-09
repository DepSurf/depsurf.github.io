# Function: <code>trace_find_filtered_pid</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580247792,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:336",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580247792,
      "name": "trace_find_filtered_pid",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580293120,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:338",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293120,
      "name": "trace_find_filtered_pid",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580306304,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:330",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580306304,
      "name": "trace_find_filtered_pid",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580359462,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:330",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351904,
      "name": "trace_find_filtered_pid.part.56",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580359360,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580421238,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:331",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580413056,
      "name": "trace_find_filtered_pid.part.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580421136,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580476982,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:332",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580468608,
      "name": "trace_find_filtered_pid.part.54",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580476880,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580532831,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:334",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580523664,
      "name": "trace_find_filtered_pid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071580532720,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580580431,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:352",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571200,
      "name": "trace_find_filtered_pid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071580580320,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580679619,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:367",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task",
        "kernel/trace/trace.c:trace_ignore_this_task",
        "kernel/trace/trace.c:trace_ignore_this_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580679488,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580670451,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:518",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task",
        "kernel/trace/trace.c:trace_ignore_this_task",
        "kernel/trace/trace.c:trace_ignore_this_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580670320,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580669171,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:520",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task",
        "kernel/trace/trace.c:trace_ignore_this_task",
        "kernel/trace/trace.c:trace_ignore_this_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669040,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580844003,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:533",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task",
        "kernel/trace/trace.c:trace_ignore_this_task",
        "kernel/trace/trace.c:trace_ignore_this_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580843872,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581071959,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:537",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581071808,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581378135,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:536",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581377952,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581472727,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:577",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581472544,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581582983,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:579",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581582800,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491876296,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:352",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491876136,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225818956,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:352",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225818760,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284952504,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:352",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284952304,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272168260,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:352",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272168120,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580549231,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:352",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580540000,
      "name": "trace_find_filtered_pid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071580549120,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580495999,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:352",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486848,
      "name": "trace_find_filtered_pid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071580495888,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580540479,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:352",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580531248,
      "name": "trace_find_filtered_pid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071580540368,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```

```json
{
  "name": "trace_find_filtered_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580597023,
      "name": "trace_find_filtered_pid",
      "external": true,
      "loc": "kernel/trace/trace.c:352",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ],
      "caller_func": [
        "kernel/trace/trace.c:trace_filter_add_remove_task",
        "kernel/trace/trace.c:trace_ignore_this_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580587728,
      "name": "trace_find_filtered_pid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071580596912,
      "name": "trace_find_filtered_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
bool trace_find_filtered_pid(struct trace_pid_list * filtered_pids, pid_t search_pid)
```
</details>
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
