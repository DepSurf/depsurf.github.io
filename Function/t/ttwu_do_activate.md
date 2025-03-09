# Function: <code>ttwu_do_activate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579545456,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:1749",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545456,
      "name": "ttwu_do_activate.constprop.89",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct pin_cookie cookie)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556720,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:1715",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556720,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct pin_cookie cookie)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579581552,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:1725",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579581552,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565104,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:1687",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565104,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579594768,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:1706",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579594768,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579626336,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:1702",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579626336,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579663872,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:1700",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663872,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579693440,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:2130",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579693440,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579733824,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:2250",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579733824,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579776392,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:2314",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579761104,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:2969",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579761104,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579768768,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:2990",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768768,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579859216,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:3557",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859216,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579974512,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:3656",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579974512,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580134736,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:3716",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134736,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:3756",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580222960,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 650
    },
    {
      "addr": 18446744071596495743,
      "name": "ttwu_do_activate.cold",
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
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:3775",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580271792,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
    },
    {
      "addr": 18446744071597392631,
      "name": "ttwu_do_activate.cold",
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
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490914280,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:2250",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490914280,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224929716,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:2250",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224929716,
      "name": "ttwu_do_activate",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283759408,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:2250",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283759408,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271552322,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:2250",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271552322,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579710480,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:2250",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579710480,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579638336,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:2250",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579638336,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579699952,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:2250",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579699952,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```

```json
{
  "name": "ttwu_do_activate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579741104,
      "name": "ttwu_do_activate",
      "external": false,
      "loc": "kernel/sched/core.c:2250",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:sched_ttwu_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579741104,
      "name": "ttwu_do_activate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct pin_cookie cookie)
```
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void ttwu_do_activate(struct rq * rq, struct task_struct * p, int wake_flags, struct rq_flags * rf)
```
</details>
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
