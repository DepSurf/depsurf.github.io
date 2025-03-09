# Function: <code>hrtick_start_fair</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579580960,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:4098",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:hrtick_update",
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580960,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579592384,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:4454",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579592384,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579614800,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:4671",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579614800,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579591792,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:4814",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579591792,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579620992,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:5153",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579620992,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653616,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:5331",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653616,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579689520,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:5037",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579689520,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579723664,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:5186",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579723664,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579766288,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:5117",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579766288,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579800336,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:5377",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579800336,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579791552,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:5420",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791552,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579799040,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:5483",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579799040,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:5517",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895632,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071592108660,
      "name": "hrtick_start_fair.cold",
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:5564",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035120,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071593876720,
      "name": "hrtick_start_fair.cold",
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:5958",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580198272,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071595978577,
      "name": "hrtick_start_fair.cold",
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:6210",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580265456,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071596496586,
      "name": "hrtick_start_fair.cold",
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:6618",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580282320,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071597392903,
      "name": "hrtick_start_fair.cold",
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490945680,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:5117",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490945680,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224964748,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:5117",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224964748,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283803952,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:5117",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283803952,
      "name": "hrtick_start_fair",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271576506,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:5117",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271576506,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579742144,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:5117",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579742144,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579672528,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:5117",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672528,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579726656,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:5117",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579726656,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void hrtick_start_fair(struct rq * rq, struct task_struct * p)
```

```json
{
  "name": "hrtick_start_fair",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774192,
      "name": "hrtick_start_fair",
      "external": false,
      "loc": "kernel/sched/fair.c:5117",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:hrtick_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774192,
      "name": "hrtick_start_fair",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
