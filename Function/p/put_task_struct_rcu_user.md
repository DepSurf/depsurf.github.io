# Function: <code>put_task_struct_rcu_user</code>

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
void put_task_struct_rcu_user(struct task_struct * task)
```

```json
{
  "name": "put_task_struct_rcu_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579519680,
      "name": "put_task_struct_rcu_user",
      "external": true,
      "loc": "kernel/exit.c:185",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/sched/core.c:finish_task_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519680,
      "name": "put_task_struct_rcu_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void put_task_struct_rcu_user(struct task_struct * task)
```

```json
{
  "name": "put_task_struct_rcu_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551056,
      "name": "put_task_struct_rcu_user",
      "external": true,
      "loc": "kernel/exit.c:175",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/sched/core.c:finish_task_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551056,
      "name": "put_task_struct_rcu_user",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void put_task_struct_rcu_user(struct task_struct * task)
```

```json
{
  "name": "put_task_struct_rcu_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579532304,
      "name": "put_task_struct_rcu_user",
      "external": true,
      "loc": "kernel/exit.c:176",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532304,
      "name": "put_task_struct_rcu_user",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void put_task_struct_rcu_user(struct task_struct * task)
```

```json
{
  "name": "put_task_struct_rcu_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579536112,
      "name": "put_task_struct_rcu_user",
      "external": true,
      "loc": "kernel/exit.c:176",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536112,
      "name": "put_task_struct_rcu_user",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void put_task_struct_rcu_user(struct task_struct * task)
```

```json
{
  "name": "put_task_struct_rcu_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579608528,
      "name": "put_task_struct_rcu_user",
      "external": true,
      "loc": "kernel/exit.c:176",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579608528,
      "name": "put_task_struct_rcu_user",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_task_struct_rcu_user(struct task_struct * task)
```

```json
{
  "name": "put_task_struct_rcu_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579701568,
      "name": "put_task_struct_rcu_user",
      "external": true,
      "loc": "kernel/exit.c:180",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579701568,
      "name": "put_task_struct_rcu_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void put_task_struct_rcu_user(struct task_struct * task)
```

```json
{
  "name": "put_task_struct_rcu_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579827024,
      "name": "put_task_struct_rcu_user",
      "external": true,
      "loc": "kernel/exit.c:228",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579827024,
      "name": "put_task_struct_rcu_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void put_task_struct_rcu_user(struct task_struct * task)
```

```json
{
  "name": "put_task_struct_rcu_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579876112,
      "name": "put_task_struct_rcu_user",
      "external": true,
      "loc": "kernel/exit.c:229",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task",
        "kernel/bpf/helpers.c:bpf_task_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876112,
      "name": "put_task_struct_rcu_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void put_task_struct_rcu_user(struct task_struct * task)
```

```json
{
  "name": "put_task_struct_rcu_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579914256,
      "name": "put_task_struct_rcu_user",
      "external": true,
      "loc": "kernel/exit.c:232",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task",
        "kernel/bpf/helpers.c:bpf_task_release_dtor",
        "kernel/bpf/helpers.c:bpf_task_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914256,
      "name": "put_task_struct_rcu_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void put_task_struct_rcu_user(struct task_struct * task)
```

```json
{
  "name": "put_task_struct_rcu_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490658040,
      "name": "put_task_struct_rcu_user",
      "external": true,
      "loc": "kernel/exit.c:185",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/sched/core.c:finish_task_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490658040,
      "name": "put_task_struct_rcu_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void put_task_struct_rcu_user(struct task_struct * task)
```

```json
{
  "name": "put_task_struct_rcu_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224733468,
      "name": "put_task_struct_rcu_user",
      "external": true,
      "loc": "kernel/exit.c:185",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/sched/core.c:finish_task_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224733468,
      "name": "put_task_struct_rcu_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void put_task_struct_rcu_user(struct task_struct * task)
```

```json
{
  "name": "put_task_struct_rcu_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283481600,
      "name": "put_task_struct_rcu_user",
      "external": true,
      "loc": "kernel/exit.c:185",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/sched/core.c:finish_task_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283481600,
      "name": "put_task_struct_rcu_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void put_task_struct_rcu_user(struct task_struct * task)
```

```json
{
  "name": "put_task_struct_rcu_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271402944,
      "name": "put_task_struct_rcu_user",
      "external": true,
      "loc": "kernel/exit.c:185",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": [
        "kernel/sched/core.c:finish_task_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271402804,
      "name": "put_task_struct_rcu_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void put_task_struct_rcu_user(struct task_struct * task)
```

```json
{
  "name": "put_task_struct_rcu_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579493344,
      "name": "put_task_struct_rcu_user",
      "external": true,
      "loc": "kernel/exit.c:185",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/sched/core.c:finish_task_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493344,
      "name": "put_task_struct_rcu_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void put_task_struct_rcu_user(struct task_struct * task)
```

```json
{
  "name": "put_task_struct_rcu_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579422192,
      "name": "put_task_struct_rcu_user",
      "external": true,
      "loc": "kernel/exit.c:185",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/sched/core.c:finish_task_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579422192,
      "name": "put_task_struct_rcu_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void put_task_struct_rcu_user(struct task_struct * task)
```

```json
{
  "name": "put_task_struct_rcu_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579493264,
      "name": "put_task_struct_rcu_user",
      "external": true,
      "loc": "kernel/exit.c:185",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/sched/core.c:finish_task_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493264,
      "name": "put_task_struct_rcu_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void put_task_struct_rcu_user(struct task_struct * task)
```

```json
{
  "name": "put_task_struct_rcu_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579525792,
      "name": "put_task_struct_rcu_user",
      "external": true,
      "loc": "kernel/exit.c:185",
      "file": "kernel/exit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task",
        "kernel/sched/core.c:finish_task_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525792,
      "name": "put_task_struct_rcu_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void put_task_struct_rcu_user(struct task_struct * task)
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
