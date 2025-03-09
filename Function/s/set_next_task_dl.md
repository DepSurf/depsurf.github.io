# Function: <code>set_next_task_dl</code>

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
void set_next_task_dl(struct rq * rq, struct task_struct * p, bool first)
```

```json
{
  "name": "set_next_task_dl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579834048,
      "name": "set_next_task_dl",
      "external": false,
      "loc": "kernel/sched/deadline.c:1746",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834048,
      "name": "set_next_task_dl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void set_next_task_dl(struct rq * rq, struct task_struct * p, bool first)
```

```json
{
  "name": "set_next_task_dl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579871536,
      "name": "set_next_task_dl",
      "external": false,
      "loc": "kernel/sched/deadline.c:1748",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871536,
      "name": "set_next_task_dl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void set_next_task_dl(struct rq * rq, struct task_struct * p, bool first)
```

```json
{
  "name": "set_next_task_dl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579864544,
      "name": "set_next_task_dl",
      "external": false,
      "loc": "kernel/sched/deadline.c:1846",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579864544,
      "name": "set_next_task_dl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
void set_next_task_dl(struct rq * rq, struct task_struct * p, bool first)
```

```json
{
  "name": "set_next_task_dl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579872528,
      "name": "set_next_task_dl",
      "external": false,
      "loc": "kernel/sched/deadline.c:1825",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872528,
      "name": "set_next_task_dl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
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
void set_next_task_dl(struct rq * rq, struct task_struct * p, bool first)
```

```json
{
  "name": "set_next_task_dl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579986349,
      "name": "set_next_task_dl",
      "external": false,
      "loc": "kernel/sched/deadline.c:1826",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:pick_next_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579986160,
      "name": "set_next_task_dl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 561
    },
    {
      "addr": 18446744071592110530,
      "name": "set_next_task_dl.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_next_task_dl(struct rq * rq, struct task_struct * p, bool first)
```

```json
{
  "name": "set_next_task_dl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580127252,
      "name": "set_next_task_dl",
      "external": false,
      "loc": "kernel/sched/deadline.c:1974",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:pick_next_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580127024,
      "name": "set_next_task_dl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
    },
    {
      "addr": 18446744071593879642,
      "name": "set_next_task_dl.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_next_task_dl(struct rq * rq, struct task_struct * p, bool first)
```

```json
{
  "name": "set_next_task_dl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580301033,
      "name": "set_next_task_dl",
      "external": false,
      "loc": "kernel/sched/deadline.c:1981",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:pick_next_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580300784,
      "name": "set_next_task_dl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
    },
    {
      "addr": 18446744071595981434,
      "name": "set_next_task_dl.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_next_task_dl(struct rq * rq, struct task_struct * p, bool first)
```

```json
{
  "name": "set_next_task_dl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580368584,
      "name": "set_next_task_dl",
      "external": false,
      "loc": "kernel/sched/deadline.c:1972",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:pick_next_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580368336,
      "name": "set_next_task_dl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 637
    },
    {
      "addr": 18446744071596499616,
      "name": "set_next_task_dl.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_next_task_dl(struct rq * rq, struct task_struct * p, bool first)
```

```json
{
  "name": "set_next_task_dl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580424083,
      "name": "set_next_task_dl",
      "external": false,
      "loc": "kernel/sched/deadline.c:2054",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:pick_next_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580423984,
      "name": "set_next_task_dl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
    },
    {
      "addr": 18446744071597397054,
      "name": "set_next_task_dl.cold",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void set_next_task_dl(struct rq * rq, struct task_struct * p, bool first)
```

```json
{
  "name": "set_next_task_dl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491024184,
      "name": "set_next_task_dl",
      "external": false,
      "loc": "kernel/sched/deadline.c:1746",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491024184,
      "name": "set_next_task_dl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
void set_next_task_dl(struct rq * rq, struct task_struct * p, bool first)
```

```json
{
  "name": "set_next_task_dl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225028392,
      "name": "set_next_task_dl",
      "external": false,
      "loc": "kernel/sched/deadline.c:1746",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225028392,
      "name": "set_next_task_dl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
void set_next_task_dl(struct rq * rq, struct task_struct * p, bool first)
```

```json
{
  "name": "set_next_task_dl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283897856,
      "name": "set_next_task_dl",
      "external": false,
      "loc": "kernel/sched/deadline.c:1746",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:pick_next_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283897856,
      "name": "set_next_task_dl",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void set_next_task_dl(struct rq * rq, struct task_struct * p, bool first)
```

```json
{
  "name": "set_next_task_dl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271629026,
      "name": "set_next_task_dl",
      "external": false,
      "loc": "kernel/sched/deadline.c:1746",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271629026,
      "name": "set_next_task_dl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
void set_next_task_dl(struct rq * rq, struct task_struct * p, bool first)
```

```json
{
  "name": "set_next_task_dl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579806400,
      "name": "set_next_task_dl",
      "external": false,
      "loc": "kernel/sched/deadline.c:1746",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579806400,
      "name": "set_next_task_dl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void set_next_task_dl(struct rq * rq, struct task_struct * p, bool first)
```

```json
{
  "name": "set_next_task_dl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579740896,
      "name": "set_next_task_dl",
      "external": false,
      "loc": "kernel/sched/deadline.c:1746",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579740896,
      "name": "set_next_task_dl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void set_next_task_dl(struct rq * rq, struct task_struct * p, bool first)
```

```json
{
  "name": "set_next_task_dl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579794416,
      "name": "set_next_task_dl",
      "external": false,
      "loc": "kernel/sched/deadline.c:1746",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579794416,
      "name": "set_next_task_dl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void set_next_task_dl(struct rq * rq, struct task_struct * p, bool first)
```

```json
{
  "name": "set_next_task_dl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579840096,
      "name": "set_next_task_dl",
      "external": false,
      "loc": "kernel/sched/deadline.c:1746",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579840096,
      "name": "set_next_task_dl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void set_next_task_dl(struct rq * rq, struct task_struct * p, bool first)
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
