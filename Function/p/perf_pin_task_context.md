# Function: <code>perf_pin_task_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580437955,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1107",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_task"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct perf_event_context * perf_pin_task_context(struct task_struct * task, int ctxn)
```

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580470080,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1356",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580470080,
      "name": "perf_pin_task_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct perf_event_context * perf_pin_task_context(struct task_struct * task, int ctxn)
```

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580531872,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1364",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580531872,
      "name": "perf_pin_task_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct perf_event_context * perf_pin_task_context(struct task_struct * task, int ctxn)
```

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580564112,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1356",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580564112,
      "name": "perf_pin_task_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
struct perf_event_context * perf_pin_task_context(struct task_struct * task, int ctxn)
```

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580646496,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1404",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580646496,
      "name": "perf_pin_task_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
struct perf_event_context * perf_pin_task_context(struct task_struct * task, int ctxn)
```

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580790496,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1427",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580790496,
      "name": "perf_pin_task_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
struct perf_event_context * perf_pin_task_context(struct task_struct * task, int ctxn)
```

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580855920,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1427",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580855920,
      "name": "perf_pin_task_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
struct perf_event_context * perf_pin_task_context(struct task_struct * task, int ctxn)
```

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580949712,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1429",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580949712,
      "name": "perf_pin_task_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
struct perf_event_context * perf_pin_task_context(struct task_struct * task, int ctxn)
```

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581002624,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1429",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581002624,
      "name": "perf_pin_task_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581196292,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1491",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_context",
        "kernel/events/core.c:perf_event_exit_task_context"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581238212,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1509",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_context",
        "kernel/events/core.c:perf_event_exit_task_context"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581254327,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1507",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_context",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581498294,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1538",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_context",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581844414,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1447",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_context",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582271175,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1420",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_context",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582472039,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1420",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_context",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582640791,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1431",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init_context",
        "kernel/events/core.c:perf_event_exit_task",
        "kernel/events/core.c:perf_event_exec"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct perf_event_context * perf_pin_task_context(struct task_struct * task, int ctxn)
```

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492340680,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1429",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_exit_task_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492340680,
      "name": "perf_pin_task_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
struct perf_event_context * perf_pin_task_context(struct task_struct * task, int ctxn)
```

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226209000,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1429",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_exit_task_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226209000,
      "name": "perf_pin_task_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
struct perf_event_context * perf_pin_task_context(struct task_struct * task, int ctxn)
```

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285565760,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1429",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285565760,
      "name": "perf_pin_task_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct perf_event_context * perf_pin_task_context(struct task_struct * task, int ctxn)
```

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272468610,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1429",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272468610,
      "name": "perf_pin_task_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct perf_event_context * perf_pin_task_context(struct task_struct * task, int ctxn)
```

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580971424,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1429",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580971424,
      "name": "perf_pin_task_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
struct perf_event_context * perf_pin_task_context(struct task_struct * task, int ctxn)
```

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580918080,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1429",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580918080,
      "name": "perf_pin_task_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
struct perf_event_context * perf_pin_task_context(struct task_struct * task, int ctxn)
```

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580962672,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1429",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962672,
      "name": "perf_pin_task_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
struct perf_event_context * perf_pin_task_context(struct task_struct * task, int ctxn)
```

```json
{
  "name": "perf_pin_task_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581013440,
      "name": "perf_pin_task_context",
      "external": false,
      "loc": "kernel/events/core.c:1429",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init_task",
        "kernel/events/core.c:perf_event_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013440,
      "name": "perf_pin_task_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
struct perf_event_context * perf_pin_task_context(struct task_struct * task, int ctxn)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct perf_event_context * perf_pin_task_context(struct task_struct * task, int ctxn)
```
</details>
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
