# Function: <code>newidle_balance</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int newidle_balance(struct rq * this_rq, struct rq_flags * rf)
```

```json
{
  "name": "newidle_balance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579811888,
      "name": "newidle_balance",
      "external": true,
      "loc": "kernel/sched/fair.c:9775",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811888,
      "name": "newidle_balance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 977
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
int newidle_balance(struct rq * this_rq, struct rq_flags * rf)
```

```json
{
  "name": "newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579852000,
      "name": "newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:10460",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852000,
      "name": "newidle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 834
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
int newidle_balance(struct rq * this_rq, struct rq_flags * rf)
```

```json
{
  "name": "newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579844144,
      "name": "newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:10574",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579844144,
      "name": "newidle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 844
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
int newidle_balance(struct rq * this_rq, struct rq_flags * rf)
```

```json
{
  "name": "newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579850480,
      "name": "newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:10631",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850480,
      "name": "newidle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 994
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
int newidle_balance(struct rq * this_rq, struct rq_flags * rf)
```

```json
{
  "name": "newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:10873",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956112,
      "name": "newidle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1128
    },
    {
      "addr": 18446744071592109874,
      "name": "newidle_balance.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int newidle_balance(struct rq * this_rq, struct rq_flags * rf)
```

```json
{
  "name": "newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:10989",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070736,
      "name": "newidle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1193
    },
    {
      "addr": 18446744071593877340,
      "name": "newidle_balance.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int newidle_balance(struct rq * this_rq, struct rq_flags * rf)
```

```json
{
  "name": "newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:11516",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580241184,
      "name": "newidle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1193
    },
    {
      "addr": 18446744071595979086,
      "name": "newidle_balance.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int newidle_balance(struct rq * this_rq, struct rq_flags * rf)
```

```json
{
  "name": "newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:11820",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580307152,
      "name": "newidle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1189
    },
    {
      "addr": 18446744071596497274,
      "name": "newidle_balance.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int newidle_balance(struct rq * this_rq, struct rq_flags * rf)
```

```json
{
  "name": "newidle_balance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "newidle_balance",
      "external": false,
      "loc": "kernel/sched/fair.c:12295",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580359712,
      "name": "newidle_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1189
    },
    {
      "addr": 18446744071597394397,
      "name": "newidle_balance.cold",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int newidle_balance(struct rq * this_rq, struct rq_flags * rf)
```

```json
{
  "name": "newidle_balance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490992872,
      "name": "newidle_balance",
      "external": true,
      "loc": "kernel/sched/fair.c:9775",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490992872,
      "name": "newidle_balance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 996
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
int newidle_balance(struct rq * this_rq, struct rq_flags * rf)
```

```json
{
  "name": "newidle_balance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225002172,
      "name": "newidle_balance",
      "external": true,
      "loc": "kernel/sched/fair.c:9775",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225002172,
      "name": "newidle_balance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1272
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
int newidle_balance(struct rq * this_rq, struct rq_flags * rf)
```

```json
{
  "name": "newidle_balance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283863168,
      "name": "newidle_balance",
      "external": true,
      "loc": "kernel/sched/fair.c:9775",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283863168,
      "name": "newidle_balance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1400
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
int newidle_balance(struct rq * this_rq, struct rq_flags * rf)
```

```json
{
  "name": "newidle_balance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271604234,
      "name": "newidle_balance",
      "external": true,
      "loc": "kernel/sched/fair.c:9775",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271604234,
      "name": "newidle_balance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1036
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
int newidle_balance(struct rq * this_rq, struct rq_flags * rf)
```

```json
{
  "name": "newidle_balance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579787664,
      "name": "newidle_balance",
      "external": true,
      "loc": "kernel/sched/fair.c:9775",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787664,
      "name": "newidle_balance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 977
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
int newidle_balance(struct rq * this_rq, struct rq_flags * rf)
```

```json
{
  "name": "newidle_balance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579718448,
      "name": "newidle_balance",
      "external": true,
      "loc": "kernel/sched/fair.c:9775",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718448,
      "name": "newidle_balance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 977
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
int newidle_balance(struct rq * this_rq, struct rq_flags * rf)
```

```json
{
  "name": "newidle_balance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579772256,
      "name": "newidle_balance",
      "external": true,
      "loc": "kernel/sched/fair.c:9775",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579772256,
      "name": "newidle_balance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 977
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
int newidle_balance(struct rq * this_rq, struct rq_flags * rf)
```

```json
{
  "name": "newidle_balance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579820304,
      "name": "newidle_balance",
      "external": true,
      "loc": "kernel/sched/fair.c:9775",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579820304,
      "name": "newidle_balance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1016
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
int newidle_balance(struct rq * this_rq, struct rq_flags * rf)
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
