# Function: <code>_nohz_idle_balance</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool _nohz_idle_balance(struct rq * this_rq, unsigned int flags, enum cpu_idle_type idle)
```

```json
{
  "name": "_nohz_idle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579699504,
      "name": "_nohz_idle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9572",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579699504,
      "name": "_nohz_idle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
bool _nohz_idle_balance(struct rq * this_rq, unsigned int flags, enum cpu_idle_type idle)
```

```json
{
  "name": "_nohz_idle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579738480,
      "name": "_nohz_idle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9675",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738480,
      "name": "_nohz_idle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
bool _nohz_idle_balance(struct rq * this_rq, unsigned int flags, enum cpu_idle_type idle)
```

```json
{
  "name": "_nohz_idle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579768016,
      "name": "_nohz_idle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9616",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768016,
      "name": "_nohz_idle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
bool _nohz_idle_balance(struct rq * this_rq, unsigned int flags, enum cpu_idle_type idle)
```

```json
{
  "name": "_nohz_idle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579810672,
      "name": "_nohz_idle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9600",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579810672,
      "name": "_nohz_idle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
bool _nohz_idle_balance(struct rq * this_rq, unsigned int flags, enum cpu_idle_type idle)
```

```json
{
  "name": "_nohz_idle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851184,
      "name": "_nohz_idle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:10286",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:nohz_newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851184,
      "name": "_nohz_idle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
bool _nohz_idle_balance(struct rq * this_rq, unsigned int flags, enum cpu_idle_type idle)
```

```json
{
  "name": "_nohz_idle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579843264,
      "name": "_nohz_idle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:10400",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:nohz_newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579843264,
      "name": "_nohz_idle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 602
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_nohz_idle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579853488,
      "name": "_nohz_idle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:10455",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:nohz_run_idle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579853488,
      "name": "_nohz_idle_balance.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_nohz_idle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "_nohz_idle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:10697",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:nohz_run_idle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959408,
      "name": "_nohz_idle_balance.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 690
    },
    {
      "addr": 18446744071592109916,
      "name": "_nohz_idle_balance.constprop.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_nohz_idle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "_nohz_idle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:10803",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:nohz_run_idle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580074144,
      "name": "_nohz_idle_balance.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 919
    },
    {
      "addr": 18446744071593877381,
      "name": "_nohz_idle_balance.constprop.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_nohz_idle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "_nohz_idle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:11331",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:nohz_run_idle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580245216,
      "name": "_nohz_idle_balance.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1020
    },
    {
      "addr": 18446744071595979187,
      "name": "_nohz_idle_balance.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_nohz_idle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "_nohz_idle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:11635",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:nohz_run_idle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311136,
      "name": "_nohz_idle_balance.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 994
    },
    {
      "addr": 18446744071596497375,
      "name": "_nohz_idle_balance.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_nohz_idle_balance",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "_nohz_idle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:12099",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:nohz_run_idle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580363712,
      "name": "_nohz_idle_balance.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 994
    },
    {
      "addr": 18446744071597394519,
      "name": "_nohz_idle_balance.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
bool _nohz_idle_balance(struct rq * this_rq, unsigned int flags, enum cpu_idle_type idle)
```

```json
{
  "name": "_nohz_idle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490991088,
      "name": "_nohz_idle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9600",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490991088,
      "name": "_nohz_idle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
bool _nohz_idle_balance(struct rq * this_rq, unsigned int flags, enum cpu_idle_type idle)
```

```json
{
  "name": "_nohz_idle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225000632,
      "name": "_nohz_idle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9600",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225000632,
      "name": "_nohz_idle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
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
bool _nohz_idle_balance(struct rq * this_rq, unsigned int flags, enum cpu_idle_type idle)
```

```json
{
  "name": "_nohz_idle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283860992,
      "name": "_nohz_idle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9600",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283860992,
      "name": "_nohz_idle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
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
bool _nohz_idle_balance(struct rq * this_rq, unsigned int flags, enum cpu_idle_type idle)
```

```json
{
  "name": "_nohz_idle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271602858,
      "name": "_nohz_idle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9600",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271602858,
      "name": "_nohz_idle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
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
bool _nohz_idle_balance(struct rq * this_rq, unsigned int flags, enum cpu_idle_type idle)
```

```json
{
  "name": "_nohz_idle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579786448,
      "name": "_nohz_idle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9600",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786448,
      "name": "_nohz_idle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
bool _nohz_idle_balance(struct rq * this_rq, unsigned int flags, enum cpu_idle_type idle)
```

```json
{
  "name": "_nohz_idle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579717232,
      "name": "_nohz_idle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9600",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717232,
      "name": "_nohz_idle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
bool _nohz_idle_balance(struct rq * this_rq, unsigned int flags, enum cpu_idle_type idle)
```

```json
{
  "name": "_nohz_idle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579771040,
      "name": "_nohz_idle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9600",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771040,
      "name": "_nohz_idle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
bool _nohz_idle_balance(struct rq * this_rq, unsigned int flags, enum cpu_idle_type idle)
```

```json
{
  "name": "_nohz_idle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579819072,
      "name": "_nohz_idle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:9600",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579819072,
      "name": "_nohz_idle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
bool _nohz_idle_balance(struct rq * this_rq, unsigned int flags, enum cpu_idle_type idle)
```
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool _nohz_idle_balance(struct rq * this_rq, unsigned int flags, enum cpu_idle_type idle)
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
