# Function: <code>ttwu_do_wakeup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579545168,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:1717",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545168,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct pin_cookie cookie)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556496,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:1682",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556496,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct pin_cookie cookie)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579581328,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:1692",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579581328,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579564784,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:1654",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564784,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579594432,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:1673",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579594432,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579626016,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:1669",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579626016,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579663552,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:1667",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663552,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579693104,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:2097",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579693104,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579733488,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:2217",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579733488,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579772112,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:2281",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579772112,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579760784,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:2936",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579760784,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579768448,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:2957",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768448,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:3521",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858864,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 18446744071592107361,
      "name": "ttwu_do_wakeup.cold",
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
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:3620",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579974096,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071593875102,
      "name": "ttwu_do_wakeup.cold",
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
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:3680",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134304,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071595977488,
      "name": "ttwu_do_wakeup.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580225570,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:3749",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
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
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580274210,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:3768",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490913928,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:2217",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490913928,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224929260,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:2217",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224929260,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283758944,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:2217",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283758944,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271551996,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:2217",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271551996,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579710144,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:2217",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579710144,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579638000,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:2217",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579638000,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579699616,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:2217",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579699616,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579740736,
      "name": "ttwu_do_wakeup",
      "external": false,
      "loc": "kernel/sched/core.c:2217",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:ttwu_do_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579740736,
      "name": "ttwu_do_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void ttwu_do_wakeup(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
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
