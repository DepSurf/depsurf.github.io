# Function: <code>kthread_unpark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579502528,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:436",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/watchdog.c:watchdog_unpark_threads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579502528,
      "name": "kthread_unpark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579516592,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:436",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpuhp_online_idle",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/watchdog.c:watchdog_unpark_threads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516592,
      "name": "kthread_unpark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579538608,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:450",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpuhp_online_idle",
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/watchdog.c:watchdog_unpark_threads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538608,
      "name": "kthread_unpark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579525536,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:454",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/watchdog.c:watchdog_unpark_threads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525536,
      "name": "kthread_unpark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551552,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:461",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask",
        "kernel/smpboot.c:smpboot_unpark_threads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551552,
      "name": "kthread_unpark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579580208,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:475",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_register_percpu_thread_cpumask",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/stop_machine.c:cpu_stop_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580208,
      "name": "kthread_unpark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579617840,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:475",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_register_percpu_thread",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/stop_machine.c:cpu_stop_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579617840,
      "name": "kthread_unpark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:484",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_register_percpu_thread",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/stop_machine.c:cpu_stop_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644739,
      "name": "kthread_unpark.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579642208,
      "name": "kthread_unpark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579667872,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:484",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_register_percpu_thread",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/stop_machine.c:cpu_stop_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667872,
      "name": "kthread_unpark",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579699216,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:520",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_wait_for_ap",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_register_percpu_thread",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/stop_machine.c:stop_machine_unpark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579699216,
      "name": "kthread_unpark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579677232,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:546",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_wait_for_ap",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_register_percpu_thread",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/stop_machine.c:stop_machine_unpark",
        "fs/io_uring.c:io_uring_cancel_task_requests",
        "fs/io_uring.c:io_uring_cancel_files",
        "fs/io_uring.c:io_uring_poll",
        "fs/io_uring.c:io_sq_offload_create",
        "fs/io_uring.c:io_sq_thread_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579677232,
      "name": "kthread_unpark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579683744,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:573",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_register_percpu_thread",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/stop_machine.c:stop_machine_unpark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683744,
      "name": "kthread_unpark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579761024,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:573",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_register_percpu_thread",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/stop_machine.c:stop_machine_unpark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579761024,
      "name": "kthread_unpark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579868000,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:633",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_register_percpu_thread",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/stop_machine.c:stop_machine_unpark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579868000,
      "name": "kthread_unpark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580010736,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:633",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_register_percpu_thread",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/stop_machine.c:cpu_stop_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010736,
      "name": "kthread_unpark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580064384,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:634",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:cpuhp_bringup_ap",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_register_percpu_thread",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/stop_machine.c:cpu_stop_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064384,
      "name": "kthread_unpark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580106944,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:633",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:cpuhp_bringup_ap",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_register_percpu_thread",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/stop_machine.c:cpu_stop_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580106944,
      "name": "kthread_unpark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490845304,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:484",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_register_percpu_thread",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/stop_machine.c:cpu_stop_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490845304,
      "name": "kthread_unpark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224873400,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:484",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_register_percpu_thread",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/stop_machine.c:cpu_stop_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224873400,
      "name": "kthread_unpark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283683440,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:484",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_register_percpu_thread",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/stop_machine.c:cpu_stop_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283683440,
      "name": "kthread_unpark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271512270,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:484",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_register_percpu_thread",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/stop_machine.c:cpu_stop_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271512270,
      "name": "kthread_unpark",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644192,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:484",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_register_percpu_thread",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/stop_machine.c:cpu_stop_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644192,
      "name": "kthread_unpark",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579572576,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:484",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_register_percpu_thread",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/stop_machine.c:cpu_stop_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579572576,
      "name": "kthread_unpark",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579641456,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:484",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_register_percpu_thread",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/stop_machine.c:cpu_stop_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641456,
      "name": "kthread_unpark",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void kthread_unpark(struct task_struct * k)
```

```json
{
  "name": "kthread_unpark",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579675696,
      "name": "kthread_unpark",
      "external": true,
      "loc": "kernel/kthread.c:484",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/cpu.c:bringup_cpu",
        "kernel/cpu.c:cpuhp_threads_init",
        "kernel/kthread.c:kthread_stop",
        "kernel/smpboot.c:smpboot_register_percpu_thread",
        "kernel/smpboot.c:smpboot_unpark_threads",
        "kernel/stop_machine.c:cpu_stop_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675696,
      "name": "kthread_unpark",
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
