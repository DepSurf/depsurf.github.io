# Function: <code>__task_rq_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579548573,
      "name": "__task_rq_lock",
      "external": false,
      "loc": "kernel/sched/sched.h:1431",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:rt_mutex_setprio"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579549648,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:177",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549648,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579574448,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:177",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579574448,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558000,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:92",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558000,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579587072,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:94",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587072,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579618304,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:72",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579618304,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579655712,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:66",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655712,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579679296,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:78",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579679296,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579716880,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:78",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716880,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579760256,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:81",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_invoke_on_locked_down_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579760256,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579748592,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:180",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_invoke_on_locked_down_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748592,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579755712,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:190",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_invoke_on_locked_down_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/deadline.c:dl_add_task_root_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579755712,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:543",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_invoke_on_locked_down_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/deadline.c:dl_add_task_root_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592107198,
      "name": "__task_rq_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579841184,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:613",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:task_call_func",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/build_policy.c:dl_add_task_root_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593874913,
      "name": "__task_rq_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579955856,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:606",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:task_call_func",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/build_policy.c:dl_add_task_root_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595977258,
      "name": "__task_rq_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580115152,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:627",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:task_call_func",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/build_policy.c:dl_add_task_root_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596495098,
      "name": "__task_rq_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580176592,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:628",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:task_call_func",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/build_policy.c:dl_add_task_root_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597391901,
      "name": "__task_rq_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580222960,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490899512,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:78",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490899512,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224913832,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:78",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224913832,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283737952,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:78",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283737952,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271544732,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:78",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271544732,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579693056,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:78",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579693056,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579621584,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:78",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579621584,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579690032,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:78",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579690032,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
```

```json
{
  "name": "__task_rq_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579724688,
      "name": "__task_rq_lock",
      "external": true,
      "loc": "kernel/sched/core.c:78",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:rt_mutex_setprio",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:try_to_wake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724688,
      "name": "__task_rq_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct rq * __task_rq_lock(struct task_struct * p, struct rq_flags * rf)
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
