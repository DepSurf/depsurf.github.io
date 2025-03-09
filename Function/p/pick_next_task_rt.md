# Function: <code>pick_next_task_rt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * pick_next_task_rt(struct rq * rq, struct task_struct * prev)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579631552,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1465",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631552,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * pick_next_task_rt(struct rq * rq, struct task_struct * prev, struct pin_cookie cookie)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579646432,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1527",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579646432,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
struct task_struct * pick_next_task_rt(struct rq * rq, struct task_struct * prev, struct pin_cookie cookie)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579671120,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1526",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671120,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
struct task_struct * pick_next_task_rt(struct rq * rq, struct task_struct * prev, struct rq_flags * rf)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579650944,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1538",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650944,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
struct task_struct * pick_next_task_rt(struct rq * rq, struct task_struct * prev, struct rq_flags * rf)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579681328,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1528",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579681328,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
struct task_struct * pick_next_task_rt(struct rq * rq, struct task_struct * prev, struct rq_flags * rf)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579713376,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1537",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713376,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
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
struct task_struct * pick_next_task_rt(struct rq * rq, struct task_struct * prev, struct rq_flags * rf)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579753472,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1541",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579753472,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
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
struct task_struct * pick_next_task_rt(struct rq * rq, struct task_struct * prev, struct rq_flags * rf)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579782144,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1541",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782144,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
struct task_struct * pick_next_task_rt(struct rq * rq, struct task_struct * prev, struct rq_flags * rf)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579820304,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1571",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579820304,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
struct task_struct * pick_next_task_rt(struct rq * rq)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579859680,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1627",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859680,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
struct task_struct * pick_next_task_rt(struct rq * rq)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579852000,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1629",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852000,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
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
struct task_struct * pick_next_task_rt(struct rq * rq)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579861056,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1629",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579861056,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
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
struct task_struct * pick_next_task_rt(struct rq * rq)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1656",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973280,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
    },
    {
      "addr": 18446744071592110215,
      "name": "pick_next_task_rt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
struct task_struct * pick_next_task_rt(struct rq * rq)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1815",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580124128,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 605
    },
    {
      "addr": 18446744071593879539,
      "name": "pick_next_task_rt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
struct task_struct * pick_next_task_rt(struct rq * rq)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1814",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580297936,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    },
    {
      "addr": 18446744071595981331,
      "name": "pick_next_task_rt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
struct task_struct * pick_next_task_rt(struct rq * rq)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1814",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580365392,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    },
    {
      "addr": 18446744071596499513,
      "name": "pick_next_task_rt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
struct task_struct * pick_next_task_rt(struct rq * rq)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1759",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580420912,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
    },
    {
      "addr": 18446744071597396951,
      "name": "pick_next_task_rt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
struct task_struct * pick_next_task_rt(struct rq * rq, struct task_struct * prev, struct rq_flags * rf)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491003336,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1571",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491003336,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
struct task_struct * pick_next_task_rt(struct rq * rq, struct task_struct * prev, struct rq_flags * rf)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225014812,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1571",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225014812,
      "name": "pick_next_task_rt",
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
struct task_struct * pick_next_task_rt(struct rq * rq, struct task_struct * prev, struct rq_flags * rf)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283880320,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1571",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283880320,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
struct task_struct * pick_next_task_rt(struct rq * rq, struct task_struct * prev, struct rq_flags * rf)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271613042,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1571",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271613042,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
struct task_struct * pick_next_task_rt(struct rq * rq, struct task_struct * prev, struct rq_flags * rf)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579794960,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1571",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579794960,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
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
struct task_struct * pick_next_task_rt(struct rq * rq, struct task_struct * prev, struct rq_flags * rf)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579726944,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1571",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579726944,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
struct task_struct * pick_next_task_rt(struct rq * rq, struct task_struct * prev, struct rq_flags * rf)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579780672,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1571",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579780672,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
struct task_struct * pick_next_task_rt(struct rq * rq, struct task_struct * prev, struct rq_flags * rf)
```

```json
{
  "name": "pick_next_task_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579830992,
      "name": "pick_next_task_rt",
      "external": false,
      "loc": "kernel/sched/rt.c:1571",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579830992,
      "name": "pick_next_task_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pin_cookie cookie</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rq_flags * rf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pin_cookie cookie</code>
</li>
</ul>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct * prev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rq_flags * rf</code>
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
