# Function: <code>kthread_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579503552,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:135",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_waking_up",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503552,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579517616,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:135",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_waking_up",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517616,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540192,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:144",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_waking_up",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540192,
      "name": "kthread_data",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579526976,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:147",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_waking_up",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579526976,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579553456,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:155",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_waking_up",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579553456,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579581472,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:154",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_waking_up",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579581472,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579618672,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:154",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_last_func",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_waking_up",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579618672,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:163",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_last_func",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_running",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644834,
      "name": "kthread_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579642944,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579669008,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:163",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_last_func",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_running",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579669008,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579698848,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:184",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_last_func",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_running",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor",
        "fs/io-wq.c:io_wq_worker_sleeping",
        "fs/io-wq.c:io_wq_worker_running"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698848,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579676864,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:185",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_last_func",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_running",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor",
        "fs/io-wq.c:io_wq_worker_sleeping",
        "fs/io-wq.c:io_wq_worker_running"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676864,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579683376,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:211",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_last_func",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_running",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683376,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579760256,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:211",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_last_func",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_running",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579760256,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579866848,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:232",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_last_func",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_running",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866848,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580009328,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:232",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_last_func",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_running",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009328,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580063168,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:243",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_last_func",
        "kernel/workqueue.c:wq_worker_tick",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_running",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580063168,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580105728,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:242",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:delayed_work_timer_fn",
        "kernel/workqueue.c:wq_worker_last_func",
        "kernel/workqueue.c:wq_worker_tick",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_running",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580105728,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490847808,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:163",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_last_func",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_running",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490847808,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224876004,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:163",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_last_func",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_running",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224876004,
      "name": "kthread_data",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283684944,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:163",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_last_func",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_running",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283684944,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271514984,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:163",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_last_func",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_running",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271514984,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579645328,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:163",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_last_func",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_running",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645328,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579573696,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:163",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_last_func",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_running",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579573696,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579642592,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:163",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_last_func",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_running",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579642592,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void * kthread_data(struct task_struct * task)
```

```json
{
  "name": "kthread_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579676448,
      "name": "kthread_data",
      "external": true,
      "loc": "kernel/kthread.c:163",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_worker_comm",
        "kernel/workqueue.c:set_worker_desc",
        "kernel/workqueue.c:current_is_workqueue_rescuer",
        "kernel/workqueue.c:current_work",
        "kernel/workqueue.c:check_flush_dependency",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:wq_worker_last_func",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_running",
        "kernel/async.c:current_is_async",
        "kernel/irq/manage.c:irq_thread_dtor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676448,
      "name": "kthread_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
