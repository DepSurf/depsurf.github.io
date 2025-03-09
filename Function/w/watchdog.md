# Function: <code>watchdog</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579632103,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2187",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580132352,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:225",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580133664,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/watchdog.c:542",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132352,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 782
    },
    {
      "addr": 18446744071580133664,
      "name": "watchdog",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579646999,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2250",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580166416,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:227",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580167760,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/watchdog.c:558",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580166416,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 806
    },
    {
      "addr": 18446744071580167760,
      "name": "watchdog",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579671687,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2248",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580206832,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:228",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580209680,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/watchdog.c:426",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580206832,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 849
    },
    {
      "addr": 18446744071580209680,
      "name": "watchdog",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579650455,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2341",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580214880,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:237",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580217216,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/watchdog.c:497",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580214880,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 874
    },
    {
      "addr": 18446744071580217216,
      "name": "watchdog",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579680839,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2268",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580266224,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:237",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580267248,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/watchdog.c:513",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580266224,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 877
    },
    {
      "addr": 18446744071580267248,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579711191,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2279",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:240",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580327680,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/watchdog.c:513",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580326704,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
    },
    {
      "addr": 18446744071580327474,
      "name": "watchdog.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071580327680,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579749003,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2290",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:269",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580379584,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 814
    },
    {
      "addr": 18446744071580380450,
      "name": "watchdog.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579777587,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2290",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:271",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580432288,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 910
    },
    {
      "addr": 18446744071580433250,
      "name": "watchdog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579825523,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2280",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:271",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580481040,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 910
    },
    {
      "addr": 18446744071580482002,
      "name": "watchdog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579864689,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2352",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580566688,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:277",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580566688,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579856993,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2392",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580554736,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:276",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580554736,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579865521,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2399",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580557904,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:276",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580557904,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579977602,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2424",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:277",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580727856,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071592165020,
      "name": "watchdog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580122981,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2601",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:351",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580940272,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071593938249,
      "name": "watchdog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580296741,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2600",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:359",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581233680,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071596001555,
      "name": "watchdog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580364197,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2604",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:361",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581328032,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071596520073,
      "name": "watchdog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580419765,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2553",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:361",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434336,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071597420464,
      "name": "watchdog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491010004,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2280",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491756808,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:271",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491756808,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 964
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
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225019544,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2280",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 3225705096,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:271",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225705096,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1136
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
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283886232,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2280",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284797872,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:271",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284797872,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1292
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
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271617706,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2280",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272078182,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:271",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272078182,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579799027,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2280",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:271",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580449840,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 910
    },
    {
      "addr": 18446744071580450802,
      "name": "watchdog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579732275,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2280",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:271",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580396912,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 910
    },
    {
      "addr": 18446744071580397874,
      "name": "watchdog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579785891,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2280",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:271",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580441088,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 910
    },
    {
      "addr": 18446744071580442050,
      "name": "watchdog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
void watchdog(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "watchdog",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579830659,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/sched/rt.c:2280",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:task_tick_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "watchdog",
      "external": false,
      "loc": "kernel/hung_task.c:271",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580496720,
      "name": "watchdog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 911
    },
    {
      "addr": 18446744071580497682,
      "name": "watchdog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
