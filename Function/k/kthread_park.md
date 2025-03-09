# Function: <code>kthread_park</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579501072,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:457",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park",
        "kernel/watchdog.c:watchdog_park_threads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501072,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579515136,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:457",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park",
        "kernel/watchdog.c:watchdog_park_threads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515136,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579535824,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:485",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park",
        "kernel/watchdog.c:watchdog_park_threads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535824,
      "name": "kthread_park",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579523040,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:489",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park",
        "kernel/watchdog.c:watchdog_park_threads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523040,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579549424,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:496",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549424,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579580848,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:507",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_update_cpumask_percpu_thread",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580848,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579618480,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:506",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579618480,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:515",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_finish_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644539,
      "name": "kthread_park.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071579638992,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579664928,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:515",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park",
        "fs/io_uring.c:io_finish_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664928,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579699408,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:551",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_sq_offload_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579699408,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579677872,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:577",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park",
        "fs/io_uring.c:io_uring_cancel_task_requests",
        "fs/io_uring.c:io_uring_cancel_files",
        "fs/io_uring.c:io_uring_poll",
        "fs/io_uring.c:io_sq_offload_create",
        "fs/io_uring.c:io_sq_thread_stop",
        "fs/io_uring.c:io_sq_thread_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579677872,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579683904,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:604",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683904,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579761120,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:604",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579761120,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579867168,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:664",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/smpboot.c:__smpboot_create_thread",
        "kernel/stop_machine.c:stop_machine_park"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867168,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580009712,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:664",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/smpboot.c:__smpboot_create_thread",
        "kernel/stop_machine.c:stop_machine_park"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009712,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580063552,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:665",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/smpboot.c:__smpboot_create_thread",
        "kernel/stop_machine.c:stop_machine_park"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580063552,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580106112,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:664",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/smpboot.c:__smpboot_create_thread",
        "kernel/stop_machine.c:stop_machine_park"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580106112,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490841824,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:515",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_vm_worker_thread",
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park",
        "fs/io_uring.c:io_finish_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490841824,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224870012,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:515",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park",
        "fs/io_uring.c:io_finish_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224870012,
      "name": "kthread_park",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283677792,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:515",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park",
        "fs/io_uring.c:io_finish_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283677792,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271510452,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:515",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park",
        "fs/io_uring.c:io_finish_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271510452,
      "name": "kthread_park",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579641248,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:515",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park",
        "fs/io_uring.c:io_finish_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641248,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579569648,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:515",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park",
        "fs/io_uring.c:io_finish_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569648,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579638512,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:515",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park",
        "fs/io_uring.c:io_finish_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579638512,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int kthread_park(struct task_struct * k)
```

```json
{
  "name": "kthread_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579672352,
      "name": "kthread_park",
      "external": true,
      "loc": "kernel/kthread.c:515",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:takedown_cpu",
        "kernel/smpboot.c:smpboot_park_threads",
        "kernel/stop_machine.c:stop_machine_park",
        "fs/io_uring.c:io_finish_async"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672352,
      "name": "kthread_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
