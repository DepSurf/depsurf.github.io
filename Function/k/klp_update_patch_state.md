# Function: <code>klp_update_patch_state</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void klp_update_patch_state(struct task_struct * task)
```

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579864576,
      "name": "klp_update_patch_state",
      "external": true,
      "loc": "kernel/livepatch/transition.c:159",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:exit_to_usermode_loop",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579864576,
      "name": "klp_update_patch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void klp_update_patch_state(struct task_struct * task)
```

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908128,
      "name": "klp_update_patch_state",
      "external": true,
      "loc": "kernel/livepatch/transition.c:184",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:exit_to_usermode_loop",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908128,
      "name": "klp_update_patch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void klp_update_patch_state(struct task_struct * task)
```

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579944280,
      "name": "klp_update_patch_state",
      "external": true,
      "loc": "kernel/livepatch/transition.c:175",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition"
      ],
      "caller_func": [
        "arch/x86/entry/common.c:exit_to_usermode_loop",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942336,
      "name": "klp_update_patch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void klp_update_patch_state(struct task_struct * task)
```

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579991368,
      "name": "klp_update_patch_state",
      "external": true,
      "loc": "kernel/livepatch/transition.c:175",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition"
      ],
      "caller_func": [
        "arch/x86/entry/common.c:exit_to_usermode_loop",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579989424,
      "name": "klp_update_patch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void klp_update_patch_state(struct task_struct * task)
```

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580033161,
      "name": "klp_update_patch_state",
      "external": true,
      "loc": "kernel/livepatch/transition.c:163",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition"
      ],
      "caller_func": [
        "arch/x86/entry/common.c:exit_to_usermode_loop",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580031056,
      "name": "klp_update_patch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void klp_update_patch_state(struct task_struct * task)
```

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580083881,
      "name": "klp_update_patch_state",
      "external": true,
      "loc": "kernel/livepatch/transition.c:163",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition"
      ],
      "caller_func": [
        "arch/x86/entry/common.c:exit_to_usermode_loop",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081776,
      "name": "klp_update_patch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void klp_update_patch_state(struct task_struct * task)
```

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580141648,
      "name": "klp_update_patch_state",
      "external": true,
      "loc": "kernel/livepatch/transition.c:163",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:exit_to_usermode_loop",
        "kernel/sched/idle.c:do_idle",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580141648,
      "name": "klp_update_patch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void klp_update_patch_state(struct task_struct * task)
```

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580118880,
      "name": "klp_update_patch_state",
      "external": true,
      "loc": "kernel/livepatch/transition.c:163",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/entry/common.c:exit_to_user_mode_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580118880,
      "name": "klp_update_patch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void klp_update_patch_state(struct task_struct * task)
```

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122160,
      "name": "klp_update_patch_state",
      "external": true,
      "loc": "kernel/livepatch/transition.c:164",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/entry/common.c:exit_to_user_mode_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122160,
      "name": "klp_update_patch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void klp_update_patch_state(struct task_struct * task)
```

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580264832,
      "name": "klp_update_patch_state",
      "external": true,
      "loc": "kernel/livepatch/transition.c:164",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/idle.c:do_idle",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/entry/common.c:exit_to_user_mode_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580264832,
      "name": "klp_update_patch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void klp_update_patch_state(struct task_struct * task)
```

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580434992,
      "name": "klp_update_patch_state",
      "external": true,
      "loc": "kernel/livepatch/transition.c:162",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:do_idle",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/entry/common.c:exit_to_user_mode_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580434992,
      "name": "klp_update_patch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void klp_update_patch_state(struct task_struct * task)
```

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580677312,
      "name": "klp_update_patch_state",
      "external": true,
      "loc": "kernel/livepatch/transition.c:162",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:do_idle",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/entry/common.c:exit_to_user_mode_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580677312,
      "name": "klp_update_patch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void klp_update_patch_state(struct task_struct * task)
```

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580753824,
      "name": "klp_update_patch_state",
      "external": true,
      "loc": "kernel/livepatch/transition.c:184",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:do_idle",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/entry/common.c:exit_to_user_mode_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580753824,
      "name": "klp_update_patch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void klp_update_patch_state(struct task_struct * task)
```

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580838944,
      "name": "klp_update_patch_state",
      "external": true,
      "loc": "kernel/livepatch/transition.c:184",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:do_idle",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/entry/common.c:irqentry_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580838944,
      "name": "klp_update_patch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_update_patch_state",
      "external": false,
      "loc": "include/linux/livepatch.h:225",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_update_patch_state",
      "external": false,
      "loc": "include/linux/livepatch.h:225",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void klp_update_patch_state(struct task_struct * task)
```

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284210272,
      "name": "klp_update_patch_state",
      "external": true,
      "loc": "kernel/livepatch/transition.c:163",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition"
      ],
      "caller_func": [
        "arch/powerpc/kernel/signal.c:do_notify_resume",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284207168,
      "name": "klp_update_patch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_update_patch_state",
      "external": false,
      "loc": "include/linux/livepatch.h:225",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
void klp_update_patch_state(struct task_struct * task)
```

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580052617,
      "name": "klp_update_patch_state",
      "external": true,
      "loc": "kernel/livepatch/transition.c:163",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition"
      ],
      "caller_func": [
        "arch/x86/entry/common.c:exit_to_usermode_loop",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050512,
      "name": "klp_update_patch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void klp_update_patch_state(struct task_struct * task)
```

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579997929,
      "name": "klp_update_patch_state",
      "external": true,
      "loc": "kernel/livepatch/transition.c:163",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition"
      ],
      "caller_func": [
        "arch/x86/entry/common.c:exit_to_usermode_loop",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995824,
      "name": "klp_update_patch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void klp_update_patch_state(struct task_struct * task)
```

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580044153,
      "name": "klp_update_patch_state",
      "external": true,
      "loc": "kernel/livepatch/transition.c:163",
      "file": "kernel/livepatch/transition.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition"
      ],
      "caller_func": [
        "arch/x86/entry/common.c:exit_to_usermode_loop",
        "kernel/sched/idle.c:do_idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580042048,
      "name": "klp_update_patch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void klp_update_patch_state(struct task_struct * task)
```

```json
{
  "name": "klp_update_patch_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580092800,
      "name": "klp_update_patch_state",
      "external": true,
      "loc": "kernel/livepatch/transition.c:163",
      "file": "kernel/livepatch/transition.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:exit_to_usermode_loop",
        "kernel/sched/idle.c:do_idle",
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_force_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580092800,
      "name": "klp_update_patch_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void klp_update_patch_state(struct task_struct * task)
```
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void klp_update_patch_state(struct task_struct * task)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void klp_update_patch_state(struct task_struct * task)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void klp_update_patch_state(struct task_struct * task)
```
</details>
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
