# Function: <code>wake_q_add_safe</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686736,
      "name": "wake_q_add_safe",
      "external": true,
      "loc": "kernel/sched/core.c:472",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/futex.c:mark_wake_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686736,
      "name": "wake_q_add_safe",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579726464,
      "name": "wake_q_add_safe",
      "external": true,
      "loc": "kernel/sched/core.c:472",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/futex.c:mark_wake_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579726464,
      "name": "wake_q_add_safe",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579770064,
      "name": "wake_q_add_safe",
      "external": true,
      "loc": "kernel/sched/core.c:475",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/futex.c:mark_wake_futex",
        "ipc/msg.c:expunge_all",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579770064,
      "name": "wake_q_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void wake_q_add_safe(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758768,
      "name": "wake_q_add_safe",
      "external": true,
      "loc": "kernel/sched/core.c:564",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/futex.c:mark_wake_futex",
        "ipc/msg.c:expunge_all",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758768,
      "name": "wake_q_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void wake_q_add_safe(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579766096,
      "name": "wake_q_add_safe",
      "external": true,
      "loc": "kernel/sched/core.c:574",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/futex.c:mark_wake_futex",
        "ipc/msg.c:expunge_all",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579766096,
      "name": "wake_q_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void wake_q_add_safe(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851920,
      "name": "wake_q_add_safe",
      "external": true,
      "loc": "kernel/sched/core.c:927",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/futex.c:mark_wake_futex",
        "ipc/msg.c:expunge_all",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851920,
      "name": "wake_q_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void wake_q_add_safe(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579962800,
      "name": "wake_q_add_safe",
      "external": true,
      "loc": "kernel/sched/core.c:997",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/futex/waitwake.c:futex_wake_mark",
        "ipc/msg.c:expunge_all",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962800,
      "name": "wake_q_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void wake_q_add_safe(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122448,
      "name": "wake_q_add_safe",
      "external": true,
      "loc": "kernel/sched/core.c:985",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/futex/waitwake.c:futex_wake_mark",
        "ipc/msg.c:expunge_all",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122448,
      "name": "wake_q_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void wake_q_add_safe(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580184176,
      "name": "wake_q_add_safe",
      "external": true,
      "loc": "kernel/sched/core.c:1007",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "ipc/msg.c:expunge_all",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580184176,
      "name": "wake_q_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void wake_q_add_safe(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580231328,
      "name": "wake_q_add_safe",
      "external": true,
      "loc": "kernel/sched/core.c:1007",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/futex/waitwake.c:futex_wake_mark",
        "ipc/msg.c:expunge_all",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580231328,
      "name": "wake_q_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void wake_q_add_safe(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490909104,
      "name": "wake_q_add_safe",
      "external": true,
      "loc": "kernel/sched/core.c:472",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/futex.c:mark_wake_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490909104,
      "name": "wake_q_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void wake_q_add_safe(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224922112,
      "name": "wake_q_add_safe",
      "external": true,
      "loc": "kernel/sched/core.c:472",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/futex.c:mark_wake_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224922112,
      "name": "wake_q_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void wake_q_add_safe(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283749520,
      "name": "wake_q_add_safe",
      "external": true,
      "loc": "kernel/sched/core.c:472",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/futex.c:mark_wake_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283749520,
      "name": "wake_q_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void wake_q_add_safe(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271548348,
      "name": "wake_q_add_safe",
      "external": true,
      "loc": "kernel/sched/core.c:472",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/futex.c:mark_wake_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271548348,
      "name": "wake_q_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void wake_q_add_safe(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579703120,
      "name": "wake_q_add_safe",
      "external": true,
      "loc": "kernel/sched/core.c:472",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/futex.c:mark_wake_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579703120,
      "name": "wake_q_add_safe",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579630864,
      "name": "wake_q_add_safe",
      "external": true,
      "loc": "kernel/sched/core.c:472",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/futex.c:mark_wake_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630864,
      "name": "wake_q_add_safe",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579695376,
      "name": "wake_q_add_safe",
      "external": true,
      "loc": "kernel/sched/core.c:472",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/futex.c:mark_wake_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579695376,
      "name": "wake_q_add_safe",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void wake_q_add_safe(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add_safe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579733552,
      "name": "wake_q_add_safe",
      "external": true,
      "loc": "kernel/sched/core.c:472",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/futex.c:mark_wake_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579733552,
      "name": "wake_q_add_safe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void wake_q_add_safe(struct wake_q_head * head, struct task_struct * task)
```
</details>
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
