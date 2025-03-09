# Function: <code>set_next_task_stop</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_next_task_stop(struct rq * rq, struct task_struct * stop, bool first)
```

```json
{
  "name": "set_next_task_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579866545,
      "name": "set_next_task_stop",
      "external": false,
      "loc": "kernel/sched/stop_task.c:32",
      "file": "kernel/sched/stop_task.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866400,
      "name": "set_next_task_stop",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_next_task_stop(struct rq * rq, struct task_struct * stop, bool first)
```

```json
{
  "name": "set_next_task_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579907778,
      "name": "set_next_task_stop",
      "external": false,
      "loc": "kernel/sched/stop_task.c:32",
      "file": "kernel/sched/stop_task.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907648,
      "name": "set_next_task_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void set_next_task_stop(struct rq * rq, struct task_struct * stop, bool first)
```

```json
{
  "name": "set_next_task_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579901410,
      "name": "set_next_task_stop",
      "external": false,
      "loc": "kernel/sched/stop_task.c:32",
      "file": "kernel/sched/stop_task.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579901280,
      "name": "set_next_task_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void set_next_task_stop(struct rq * rq, struct task_struct * stop, bool first)
```

```json
{
  "name": "set_next_task_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579910482,
      "name": "set_next_task_stop",
      "external": false,
      "loc": "kernel/sched/stop_task.c:32",
      "file": "kernel/sched/stop_task.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910352,
      "name": "set_next_task_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void set_next_task_stop(struct rq * rq, struct task_struct * stop, bool first)
```

```json
{
  "name": "set_next_task_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580029524,
      "name": "set_next_task_stop",
      "external": false,
      "loc": "kernel/sched/stop_task.c:32",
      "file": "kernel/sched/stop_task.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029376,
      "name": "set_next_task_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071592114075,
      "name": "set_next_task_stop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void set_next_task_stop(struct rq * rq, struct task_struct * stop, bool first)
```

```json
{
  "name": "set_next_task_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580173289,
      "name": "set_next_task_stop",
      "external": false,
      "loc": "kernel/sched/stop_task.c:31",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:pick_next_task_stop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580166752,
      "name": "set_next_task_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071593884947,
      "name": "set_next_task_stop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void set_next_task_stop(struct rq * rq, struct task_struct * stop, bool first)
```

```json
{
  "name": "set_next_task_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580353001,
      "name": "set_next_task_stop",
      "external": false,
      "loc": "kernel/sched/stop_task.c:31",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:pick_next_task_stop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580344656,
      "name": "set_next_task_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071595982358,
      "name": "set_next_task_stop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void set_next_task_stop(struct rq * rq, struct task_struct * stop, bool first)
```

```json
{
  "name": "set_next_task_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580413401,
      "name": "set_next_task_stop",
      "external": false,
      "loc": "kernel/sched/stop_task.c:31",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:pick_next_task_stop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580409152,
      "name": "set_next_task_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071596500347,
      "name": "set_next_task_stop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void set_next_task_stop(struct rq * rq, struct task_struct * stop, bool first)
```

```json
{
  "name": "set_next_task_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580468313,
      "name": "set_next_task_stop",
      "external": false,
      "loc": "kernel/sched/stop_task.c:31",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:pick_next_task_stop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580464400,
      "name": "set_next_task_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071597397733,
      "name": "set_next_task_stop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void set_next_task_stop(struct rq * rq, struct task_struct * stop, bool first)
```

```json
{
  "name": "set_next_task_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491065064,
      "name": "set_next_task_stop",
      "external": false,
      "loc": "kernel/sched/stop_task.c:32",
      "file": "kernel/sched/stop_task.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491065176,
      "name": "set_next_task_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void set_next_task_stop(struct rq * rq, struct task_struct * stop, bool first)
```

```json
{
  "name": "set_next_task_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225066700,
      "name": "set_next_task_stop",
      "external": false,
      "loc": "kernel/sched/stop_task.c:32",
      "file": "kernel/sched/stop_task.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225066928,
      "name": "set_next_task_stop",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void set_next_task_stop(struct rq * rq, struct task_struct * stop, bool first)
```

```json
{
  "name": "set_next_task_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283944080,
      "name": "set_next_task_stop",
      "external": false,
      "loc": "kernel/sched/stop_task.c:32",
      "file": "kernel/sched/stop_task.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283944272,
      "name": "set_next_task_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void set_next_task_stop(struct rq * rq, struct task_struct * stop, bool first)
```

```json
{
  "name": "set_next_task_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271655852,
      "name": "set_next_task_stop",
      "external": false,
      "loc": "kernel/sched/stop_task.c:32",
      "file": "kernel/sched/stop_task.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271656034,
      "name": "set_next_task_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void set_next_task_stop(struct rq * rq, struct task_struct * stop, bool first)
```

```json
{
  "name": "set_next_task_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579838897,
      "name": "set_next_task_stop",
      "external": false,
      "loc": "kernel/sched/stop_task.c:32",
      "file": "kernel/sched/stop_task.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579838752,
      "name": "set_next_task_stop",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void set_next_task_stop(struct rq * rq, struct task_struct * stop, bool first)
```

```json
{
  "name": "set_next_task_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579773633,
      "name": "set_next_task_stop",
      "external": false,
      "loc": "kernel/sched/stop_task.c:32",
      "file": "kernel/sched/stop_task.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579773488,
      "name": "set_next_task_stop",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void set_next_task_stop(struct rq * rq, struct task_struct * stop, bool first)
```

```json
{
  "name": "set_next_task_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579826913,
      "name": "set_next_task_stop",
      "external": false,
      "loc": "kernel/sched/stop_task.c:32",
      "file": "kernel/sched/stop_task.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579826768,
      "name": "set_next_task_stop",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void set_next_task_stop(struct rq * rq, struct task_struct * stop, bool first)
```

```json
{
  "name": "set_next_task_stop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579872049,
      "name": "set_next_task_stop",
      "external": false,
      "loc": "kernel/sched/stop_task.c:32",
      "file": "kernel/sched/stop_task.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:pick_next_task_stop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871904,
      "name": "set_next_task_stop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void set_next_task_stop(struct rq * rq, struct task_struct * stop, bool first)
```
</details>
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
