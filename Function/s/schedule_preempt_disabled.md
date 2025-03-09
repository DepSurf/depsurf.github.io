# Function: <code>schedule_preempt_disabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587366544,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:3239",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/sched/idle.c:cpu_startup_entry",
        "kernel/locking/mutex.c:mutex_optimistic_spin",
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_killable_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587366544,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587867376,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:3457",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/sched/idle.c:cpu_startup_entry",
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_killable_slowpath",
        "kernel/locking/mutex.c:mutex_optimistic_spin",
        "kernel/locking/mutex.c:__mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587867376,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588081920,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:3488",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/sched/idle.c:do_idle",
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__mutex_lock_killable_slowpath",
        "kernel/locking/mutex.c:mutex_optimistic_spin",
        "kernel/locking/mutex.c:__mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588081920,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588308640,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:3446",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588308640,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588874016,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:3490",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588874016,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589252896,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:3600",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589252896,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589495120,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:3584",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589495120,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589955808,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:4003",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589955808,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590183472,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:4206",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590183472,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591201744,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:4438",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:__kthread_parkme"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591201744,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591696816,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:5208",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:__kthread_parkme"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591696816,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591639328,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:5284",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:__kthread_parkme"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591639328,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592813280,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:6435",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:__kthread_parkme"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592813280,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594715552,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:6600",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:__kthread_parkme"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594715552,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596462800,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:6741",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:__kthread_parkme",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596462800,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597004624,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:6842",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:__kthread_parkme",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597004624,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597933968,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:6871",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:__kthread_parkme",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597933968,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503926704,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:4206",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503926704,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236536616,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:4206",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236536616,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297774544,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:4206",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297774544,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279795418,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:4206",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279795418,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589785760,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:4206",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589785760,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589508272,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:4206",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589508272,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590229168,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:4206",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590229168,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void schedule_preempt_disabled()
```

```json
{
  "name": "schedule_preempt_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590279744,
      "name": "schedule_preempt_disabled",
      "external": true,
      "loc": "kernel/sched/core.c:4206",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590279744,
      "name": "schedule_preempt_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
