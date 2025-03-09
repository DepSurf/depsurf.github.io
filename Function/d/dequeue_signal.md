# Function: <code>dequeue_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579424288,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:559",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:do_sigtimedwait",
        "fs/signalfd.c:signalfd_read",
        "fs/signalfd.c:signalfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424288,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579436272,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:559",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_read",
        "fs/signalfd.c:signalfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436272,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579456624,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:561",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_read",
        "fs/signalfd.c:signalfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579456624,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579444976,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:574",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_read",
        "fs/signalfd.c:signalfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579444976,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579473280,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:576",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_read",
        "fs/signalfd.c:signalfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579473280,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579489936,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:579",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_read",
        "fs/signalfd.c:signalfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489936,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, kernel_siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579523328,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:613",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_read",
        "fs/signalfd.c:signalfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523328,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, kernel_siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579543008,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:623",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_read",
        "fs/signalfd.c:signalfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543008,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, kernel_siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579569120,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:628",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_read",
        "fs/signalfd.c:signalfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569120,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, kernel_siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579602624,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:628",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_dequeue",
        "fs/signalfd.c:signalfd_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579602624,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, kernel_siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579582832,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:629",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_dequeue",
        "fs/signalfd.c:signalfd_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579582832,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, kernel_siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579590016,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:628",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_dequeue",
        "fs/signalfd.c:signalfd_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579590016,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, kernel_siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:629",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_dequeue",
        "fs/signalfd.c:signalfd_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592101919,
      "name": "dequeue_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579667456,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, kernel_siginfo_t * info, enum pid_type * type)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:629",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_dequeue",
        "fs/signalfd.c:signalfd_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593869370,
      "name": "dequeue_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579763072,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, kernel_siginfo_t * info, enum pid_type * type)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:629",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_dequeue",
        "fs/signalfd.c:signalfd_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595974899,
      "name": "dequeue_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579895824,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, kernel_siginfo_t * info, enum pid_type * type)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:634",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_dequeue",
        "fs/signalfd.c:signalfd_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596492419,
      "name": "dequeue_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579945232,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 511
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, kernel_siginfo_t * info, enum pid_type * type)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:625",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_dequeue",
        "fs/signalfd.c:signalfd_dequeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597389180,
      "name": "dequeue_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579984624,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 511
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, kernel_siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490727304,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:628",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_read",
        "fs/signalfd.c:signalfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490727304,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, kernel_siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224783264,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:628",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:do_sigtimedwait",
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_read",
        "fs/signalfd.c:signalfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224783264,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, kernel_siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283553152,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:628",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_read",
        "fs/signalfd.c:signalfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283553152,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, kernel_siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271441298,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:628",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_sys_rt_sigtimedwait",
        "kernel/signal.c:__se_sys_rt_sigtimedwait",
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_read",
        "fs/signalfd.c:signalfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271441298,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, kernel_siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579545424,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:628",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_read",
        "fs/signalfd.c:signalfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545424,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, kernel_siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579474160,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:628",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_read",
        "fs/signalfd.c:signalfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579474160,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, kernel_siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542704,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:628",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_read",
        "fs/signalfd.c:signalfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542704,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
int dequeue_signal(struct task_struct * tsk, sigset_t * mask, kernel_siginfo_t * info)
```

```json
{
  "name": "dequeue_signal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579575696,
      "name": "dequeue_signal",
      "external": true,
      "loc": "kernel/signal.c:628",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "fs/signalfd.c:signalfd_read",
        "fs/signalfd.c:signalfd_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579575696,
      "name": "dequeue_signal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>siginfo_t * info</code> ➡️ <code>kernel_siginfo_t * info</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum pid_type * type</code>
</li>
</ul>
</details>
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
