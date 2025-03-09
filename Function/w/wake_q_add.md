# Function: <code>wake_q_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542160,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:521",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:mark_wake_futex",
        "ipc/mqueue.c:SyS_mq_timedsend",
        "ipc/mqueue.c:SyS_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542160,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579553520,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:428",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__mutex_unlock_slowpath",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock",
        "kernel/locking/rwsem-xadd.c:__rwsem_mark_wake",
        "kernel/locking/rwsem-xadd.c:__rwsem_mark_wake",
        "kernel/futex.c:mark_wake_futex",
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579553520,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579578240,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:428",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock",
        "kernel/futex.c:mark_wake_futex",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:ss_wakeup",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578240,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579561632,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:426",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/futex.c:mark_wake_futex",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:ss_wakeup",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561632,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579590896,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:428",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/futex.c:mark_wake_futex",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque",
        "ipc/msg.c:ss_wakeup",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579590896,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579623248,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:406",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/futex.c:mark_wake_futex",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:cpu_stop_queue_work",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque",
        "ipc/msg.c:ss_wakeup",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579623248,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660800,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:411",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rwsem-xadd.c:__rwsem_mark_wake",
        "kernel/locking/rwsem-xadd.c:__rwsem_mark_wake",
        "kernel/futex.c:mark_wake_futex",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:cpu_stop_queue_work",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque",
        "ipc/msg.c:ss_wakeup",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660800,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686672,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:449",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:cpu_stop_queue_work",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque",
        "ipc/msg.c:ss_wakeup",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686672,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579726400,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:449",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:cpu_stop_queue_work",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque",
        "ipc/msg.c:ss_wakeup",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579726400,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579769952,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:452",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/stop_machine.c:cpu_stop_queue_two_works",
        "kernel/stop_machine.c:cpu_stop_queue_two_works",
        "kernel/stop_machine.c:cpu_stop_queue_work",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:ss_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579769952,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758656,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:541",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/stop_machine.c:cpu_stop_queue_two_works",
        "kernel/stop_machine.c:cpu_stop_queue_two_works",
        "kernel/stop_machine.c:cpu_stop_queue_work",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:ss_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758656,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579765984,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:551",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:cpu_stop_queue_work",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:ss_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579765984,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851808,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:904",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/stop_machine.c:cpu_stop_queue_two_works",
        "kernel/stop_machine.c:cpu_stop_queue_two_works",
        "kernel/stop_machine.c:cpu_stop_queue_work",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:ss_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851808,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579962640,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:974",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/stop_machine.c:cpu_stop_queue_two_works",
        "kernel/stop_machine.c:cpu_stop_queue_two_works",
        "kernel/stop_machine.c:cpu_stop_queue_work",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:ss_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962640,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122272,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:962",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/stop_machine.c:cpu_stop_queue_two_works",
        "kernel/stop_machine.c:cpu_stop_queue_two_works",
        "kernel/stop_machine.c:cpu_stop_queue_work",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:ss_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122272,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580184000,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:984",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/stop_machine.c:cpu_stop_queue_two_works",
        "kernel/stop_machine.c:cpu_stop_queue_two_works",
        "kernel/stop_machine.c:cpu_stop_queue_work",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:ss_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580184000,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580231152,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:984",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/stop_machine.c:cpu_stop_queue_two_works",
        "kernel/stop_machine.c:cpu_stop_queue_two_works",
        "kernel/stop_machine.c:cpu_stop_queue_work",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:ss_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580231152,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490908976,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:449",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:cpu_stop_queue_work",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490908976,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224922012,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:449",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:cpu_stop_queue_work",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224922012,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283749424,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:449",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:cpu_stop_queue_work",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283749424,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271548266,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:449",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:cpu_stop_queue_work",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:__se_sys_mq_timedreceive",
        "ipc/mqueue.c:__se_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271548266,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579703056,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:449",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:cpu_stop_queue_work",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque",
        "ipc/msg.c:ss_wakeup",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579703056,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579630800,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:449",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:cpu_stop_queue_work",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque",
        "ipc/msg.c:ss_wakeup",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630800,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579695312,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:449",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:cpu_stop_queue_work",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque",
        "ipc/msg.c:ss_wakeup",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579695312,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void wake_q_add(struct wake_q_head * head, struct task_struct * task)
```

```json
{
  "name": "wake_q_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579733488,
      "name": "wake_q_add",
      "external": true,
      "loc": "kernel/sched/core.c:449",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:stop_two_cpus",
        "kernel/stop_machine.c:cpu_stop_queue_work",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_down",
        "ipc/msg.c:freeque",
        "ipc/msg.c:ss_wakeup",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:freeary",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:update_queue",
        "ipc/sem.c:wake_const_ops",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579733488,
      "name": "wake_q_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
