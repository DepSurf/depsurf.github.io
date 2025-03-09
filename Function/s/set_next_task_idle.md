# Function: <code>set_next_task_idle</code>

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
void set_next_task_idle(struct rq * rq, struct task_struct * next, bool first)
```

```json
{
  "name": "set_next_task_idle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579761888,
      "name": "set_next_task_idle",
      "external": false,
      "loc": "kernel/sched/idle.c:388",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579761888,
      "name": "set_next_task_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void set_next_task_idle(struct rq * rq, struct task_struct * next, bool first)
```

```json
{
  "name": "set_next_task_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579795650,
      "name": "set_next_task_idle",
      "external": false,
      "loc": "kernel/sched/idle.c:405",
      "file": "kernel/sched/idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579795472,
      "name": "set_next_task_idle",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_next_task_idle(struct rq * rq, struct task_struct * next, bool first)
```

```json
{
  "name": "set_next_task_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579786466,
      "name": "set_next_task_idle",
      "external": false,
      "loc": "kernel/sched/idle.c:430",
      "file": "kernel/sched/idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786288,
      "name": "set_next_task_idle",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_next_task_idle(struct rq * rq, struct task_struct * next, bool first)
```

```json
{
  "name": "set_next_task_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579794594,
      "name": "set_next_task_idle",
      "external": false,
      "loc": "kernel/sched/idle.c:436",
      "file": "kernel/sched/idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579794416,
      "name": "set_next_task_idle",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void set_next_task_idle(struct rq * rq, struct task_struct * next, bool first)
```

```json
{
  "name": "set_next_task_idle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579890336,
      "name": "set_next_task_idle",
      "external": false,
      "loc": "kernel/sched/idle.c:436",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890336,
      "name": "set_next_task_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_next_task_idle(struct rq * rq, struct task_struct * next, bool first)
```

```json
{
  "name": "set_next_task_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580087522,
      "name": "set_next_task_idle",
      "external": false,
      "loc": "kernel/sched/idle.c:433",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:pick_next_task_idle",
        "kernel/sched/build_policy.c:pick_next_task_idle"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084048,
      "name": "set_next_task_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_next_task_idle(struct rq * rq, struct task_struct * next, bool first)
```

```json
{
  "name": "set_next_task_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580258978,
      "name": "set_next_task_idle",
      "external": false,
      "loc": "kernel/sched/idle.c:433",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:pick_next_task_idle",
        "kernel/sched/build_policy.c:pick_next_task_idle"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580256000,
      "name": "set_next_task_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_next_task_idle(struct rq * rq, struct task_struct * next, bool first)
```

```json
{
  "name": "set_next_task_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580325218,
      "name": "set_next_task_idle",
      "external": false,
      "loc": "kernel/sched/idle.c:412",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:pick_next_task_idle",
        "kernel/sched/build_policy.c:pick_next_task_idle"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580321936,
      "name": "set_next_task_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_next_task_idle(struct rq * rq, struct task_struct * next, bool first)
```

```json
{
  "name": "set_next_task_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580378914,
      "name": "set_next_task_idle",
      "external": false,
      "loc": "kernel/sched/idle.c:443",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:pick_next_task_idle",
        "kernel/sched/build_policy.c:pick_next_task_idle"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375328,
      "name": "set_next_task_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void set_next_task_idle(struct rq * rq, struct task_struct * next, bool first)
```

```json
{
  "name": "set_next_task_idle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490940536,
      "name": "set_next_task_idle",
      "external": false,
      "loc": "kernel/sched/idle.c:388",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490940536,
      "name": "set_next_task_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void set_next_task_idle(struct rq * rq, struct task_struct * next, bool first)
```

```json
{
  "name": "set_next_task_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224959012,
      "name": "set_next_task_idle",
      "external": false,
      "loc": "kernel/sched/idle.c:388",
      "file": "kernel/sched/idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224958892,
      "name": "set_next_task_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void set_next_task_idle(struct rq * rq, struct task_struct * next, bool first)
```

```json
{
  "name": "set_next_task_idle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283796320,
      "name": "set_next_task_idle",
      "external": false,
      "loc": "kernel/sched/idle.c:388",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283796320,
      "name": "set_next_task_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void set_next_task_idle(struct rq * rq, struct task_struct * next, bool first)
```

```json
{
  "name": "set_next_task_idle",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271572288,
      "name": "set_next_task_idle",
      "external": false,
      "loc": "kernel/sched/idle.c:388",
      "file": "kernel/sched/idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271572164,
      "name": "set_next_task_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void set_next_task_idle(struct rq * rq, struct task_struct * next, bool first)
```

```json
{
  "name": "set_next_task_idle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579737808,
      "name": "set_next_task_idle",
      "external": false,
      "loc": "kernel/sched/idle.c:388",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737808,
      "name": "set_next_task_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void set_next_task_idle(struct rq * rq, struct task_struct * next, bool first)
```

```json
{
  "name": "set_next_task_idle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579668160,
      "name": "set_next_task_idle",
      "external": false,
      "loc": "kernel/sched/idle.c:388",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579668160,
      "name": "set_next_task_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void set_next_task_idle(struct rq * rq, struct task_struct * next, bool first)
```

```json
{
  "name": "set_next_task_idle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579722256,
      "name": "set_next_task_idle",
      "external": false,
      "loc": "kernel/sched/idle.c:388",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579722256,
      "name": "set_next_task_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void set_next_task_idle(struct rq * rq, struct task_struct * next, bool first)
```

```json
{
  "name": "set_next_task_idle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579769632,
      "name": "set_next_task_idle",
      "external": false,
      "loc": "kernel/sched/idle.c:388",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:pick_next_task_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579769632,
      "name": "set_next_task_idle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void set_next_task_idle(struct rq * rq, struct task_struct * next, bool first)
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
