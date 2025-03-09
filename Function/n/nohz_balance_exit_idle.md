# Function: <code>nohz_balance_exit_idle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579584332,
      "name": "nohz_balance_exit_idle",
      "external": false,
      "loc": "kernel/sched/fair.c:7485",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:trigger_load_balance"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void nohz_balance_exit_idle(unsigned int cpu)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579639428,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:7947",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:trigger_load_balance"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/fair.c:trigger_load_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579594944,
      "name": "nohz_balance_exit_idle.part.80",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071579638992,
      "name": "nohz_balance_exit_idle",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void nohz_balance_exit_idle(unsigned int cpu)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579664016,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:8525",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:trigger_load_balance"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/fair.c:trigger_load_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579621792,
      "name": "nohz_balance_exit_idle.part.88",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071579663584,
      "name": "nohz_balance_exit_idle",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void nohz_balance_exit_idle(unsigned int cpu)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579638570,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:8541",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:trigger_load_balance"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/fair.c:trigger_load_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601232,
      "name": "nohz_balance_exit_idle.part.95",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071579638144,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void nohz_balance_exit_idle(unsigned int cpu)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579669146,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:9014",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:trigger_load_balance"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/fair.c:trigger_load_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629488,
      "name": "nohz_balance_exit_idle.part.98",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071579668704,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void nohz_balance_exit_idle(struct rq * rq)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579701872,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:9475",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/fair.c:trigger_load_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579701872,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void nohz_balance_exit_idle(struct rq * rq)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579741072,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:9578",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/fair.c:trigger_load_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579741072,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void nohz_balance_exit_idle(struct rq * rq)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579770720,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:9519",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/fair.c:trigger_load_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579770720,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void nohz_balance_exit_idle(struct rq * rq)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579811424,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:9503",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/fair.c:trigger_load_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811424,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void nohz_balance_exit_idle(struct rq * rq)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579853968,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:10189",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/fair.c:nohz_balancer_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579853968,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void nohz_balance_exit_idle(struct rq * rq)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579846144,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:10303",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/fair.c:nohz_balancer_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579846144,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void nohz_balance_exit_idle(struct rq * rq)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579854272,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:10342",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:nohz_balancer_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579854272,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void nohz_balance_exit_idle(struct rq * rq)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:10584",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:nohz_balancer_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592109964,
      "name": "nohz_balance_exit_idle.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579960288,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
void nohz_balance_exit_idle(struct rq * rq)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:10689",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:nohz_balancer_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593877440,
      "name": "nohz_balance_exit_idle.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580075264,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void nohz_balance_exit_idle(struct rq * rq)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:11217",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:nohz_balancer_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595979236,
      "name": "nohz_balance_exit_idle.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580246480,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void nohz_balance_exit_idle(struct rq * rq)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580312492,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:11521",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:nohz_balancer_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596497422,
      "name": "nohz_balance_exit_idle.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580312384,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void nohz_balance_exit_idle(struct rq * rq)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580365068,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:11985",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/fair.c:nohz_balancer_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597394566,
      "name": "nohz_balance_exit_idle.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580364960,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void nohz_balance_exit_idle(struct rq * rq)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490992104,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:9503",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/fair.c:trigger_load_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490992104,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void nohz_balance_exit_idle(struct rq * rq)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225001508,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:9503",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/fair.c:trigger_load_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225001508,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void nohz_balance_exit_idle(struct rq * rq)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283862256,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:9503",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/fair.c:trigger_load_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283862256,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
void nohz_balance_exit_idle(struct rq * rq)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271603670,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:9503",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271603670,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
void nohz_balance_exit_idle(struct rq * rq)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579787200,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:9503",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/fair.c:trigger_load_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787200,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void nohz_balance_exit_idle(struct rq * rq)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579717984,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:9503",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/fair.c:trigger_load_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717984,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void nohz_balance_exit_idle(struct rq * rq)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579771792,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:9503",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/fair.c:trigger_load_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771792,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void nohz_balance_exit_idle(struct rq * rq)
```

```json
{
  "name": "nohz_balance_exit_idle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579819824,
      "name": "nohz_balance_exit_idle",
      "external": true,
      "loc": "kernel/sched/fair.c:9503",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/fair.c:trigger_load_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579819824,
      "name": "nohz_balance_exit_idle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void nohz_balance_exit_idle(unsigned int cpu)
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rq * rq</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int cpu</code>
</li>
</ul>
</details>
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
