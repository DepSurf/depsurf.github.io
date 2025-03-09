# Function: <code>trace_save_cmdline</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580215260,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:1556",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580251308,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:1801",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580296684,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:1845",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trace_save_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580296368,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:1915",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580296368,
      "name": "trace_save_cmdline",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trace_save_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580349616,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:1918",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580349616,
      "name": "trace_save_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
int trace_save_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580411184,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:1930",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580411184,
      "name": "trace_save_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int trace_save_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580466720,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:1931",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580466720,
      "name": "trace_save_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int trace_save_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580521152,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:2114",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580521152,
      "name": "trace_save_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int trace_save_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580568608,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:2140",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580568608,
      "name": "trace_save_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580683581,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:2244",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580670688,
      "name": "trace_save_cmdline.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580674413,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:2388",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580661504,
      "name": "trace_save_cmdline.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
int trace_save_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580662112,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:2395",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:__update_max_tr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580662112,
      "name": "trace_save_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
int trace_save_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580835920,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:2409",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:__update_max_tr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580835920,
      "name": "trace_save_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
int trace_save_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581064416,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:2400",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:__update_max_tr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581064416,
      "name": "trace_save_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
int trace_save_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581369232,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:2420",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:__update_max_tr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581369232,
      "name": "trace_save_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
int trace_save_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463888,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:2491",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:__update_max_tr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463888,
      "name": "trace_save_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
int trace_save_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581572400,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:2486",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:__update_max_tr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572400,
      "name": "trace_save_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int trace_save_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491869808,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:2140",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491869808,
      "name": "trace_save_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int trace_save_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225803816,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:2140",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225803816,
      "name": "trace_save_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int trace_save_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284930640,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:2140",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284930640,
      "name": "trace_save_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
int trace_save_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272157398,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:2140",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272157398,
      "name": "trace_save_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int trace_save_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580537408,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:2140",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580537408,
      "name": "trace_save_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int trace_save_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580484256,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:2140",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580484256,
      "name": "trace_save_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int trace_save_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580528656,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:2140",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580528656,
      "name": "trace_save_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int trace_save_cmdline(struct task_struct * tsk)
```

```json
{
  "name": "trace_save_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580585136,
      "name": "trace_save_cmdline",
      "external": false,
      "loc": "kernel/trace/trace.c:2140",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch",
        "kernel/trace/trace.c:tracing_record_taskinfo_sched_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580585136,
      "name": "trace_save_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int trace_save_cmdline(struct task_struct * tsk)
```
</details>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int trace_save_cmdline(struct task_struct * tsk)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int trace_save_cmdline(struct task_struct * tsk)
```
</details>
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
