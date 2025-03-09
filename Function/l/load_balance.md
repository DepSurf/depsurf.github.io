# Function: <code>load_balance</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579619776,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:6965",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:rebalance_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579619776,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2419
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579634000,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:7431",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579634000,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2553
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
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579658576,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:8008",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579658576,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2546
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
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579633024,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:8002",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579633024,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2449
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
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579663504,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:8462",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663504,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2481
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
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579696272,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:8815",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579696272,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2502
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
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579735136,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:8909",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579735136,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2609
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
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579764432,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:8822",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:rebalance_domains",
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579764432,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2799
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
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579807072,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:8805",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:rebalance_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807072,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2805
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
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579848192,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9485",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:rebalance_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848192,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2076
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
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579840112,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9586",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:rebalance_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579840112,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2195
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
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579848784,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9652",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:rebalance_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848784,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1686
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
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9893",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:rebalance_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953984,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2127
    },
    {
      "addr": 18446744071592109833,
      "name": "load_balance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9976",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:rebalance_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580068464,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2268
    },
    {
      "addr": 18446744071593877290,
      "name": "load_balance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:10503",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:rebalance_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580238912,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2244
    },
    {
      "addr": 18446744071595979036,
      "name": "load_balance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:10803",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:rebalance_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580304816,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2317
    },
    {
      "addr": 18446744071596497220,
      "name": "load_balance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:11264",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:rebalance_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580357472,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2221
    },
    {
      "addr": 18446744071597394343,
      "name": "load_balance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490987152,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:8805",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:rebalance_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490987152,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3136
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
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224996776,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:8805",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:rebalance_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224996776,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2988
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
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283856304,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:8805",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:rebalance_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283856304,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3612
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
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271599540,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:8805",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:rebalance_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271599540,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2684
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
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579782848,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:8805",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:rebalance_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782848,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2805
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
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579713648,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:8805",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:rebalance_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713648,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2799
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
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579767440,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:8805",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:rebalance_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579767440,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2805
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
int load_balance(int this_cpu, struct rq * this_rq, struct sched_domain * sd, enum cpu_idle_type idle, int * continue_balancing)
```

```json
{
  "name": "load_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579815472,
      "name": "load_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:8805",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:newidle_balance",
        "kernel/sched/fair.c:rebalance_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815472,
      "name": "load_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2836
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
