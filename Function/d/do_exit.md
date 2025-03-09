# Function: <code>do_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579384000,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:653",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/dumpstack.c:oops_end",
        "kernel/exit.c:complete_and_exit",
        "kernel/exit.c:SyS_exit",
        "kernel/exit.c:do_group_exit",
        "kernel/kmod.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:seccomp_phase2",
        "fs/buffer.c:SyS_bdflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384000,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2779
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
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579396576,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:728",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:SyS_exit",
        "kernel/exit.c:complete_and_exit",
        "kernel/kmod.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/buffer.c:SyS_bdflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396576,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2838
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
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579416912,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:737",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:SyS_exit",
        "kernel/exit.c:complete_and_exit",
        "kernel/kmod.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/buffer.c:SyS_bdflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416912,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2825
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
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579405024,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:763",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:SyS_exit",
        "kernel/exit.c:complete_and_exit",
        "kernel/kmod.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/buffer.c:SyS_bdflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579405024,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2789
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
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579432976,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:763",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:SyS_exit",
        "kernel/exit.c:complete_and_exit",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/buffer.c:SyS_bdflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432976,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2878
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:763",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:__ia32_sys_exit",
        "kernel/exit.c:__x64_sys_exit",
        "kernel/exit.c:complete_and_exit",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/buffer.c:__ia32_sys_bdflush",
        "fs/buffer.c:__x64_sys_bdflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452043,
      "name": "do_exit.cold.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071579448192,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2670
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:773",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:__ia32_sys_exit",
        "kernel/exit.c:__x64_sys_exit",
        "kernel/exit.c:complete_and_exit",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/buffer.c:__ia32_sys_bdflush",
        "fs/buffer.c:__x64_sys_bdflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579485739,
      "name": "do_exit.cold.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071579481664,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2859
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
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:777",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:__ia32_sys_exit",
        "kernel/exit.c:__x64_sys_exit",
        "kernel/exit.c:complete_and_exit",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/buffer.c:__ia32_sys_bdflush",
        "fs/buffer.c:__x64_sys_bdflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503691,
      "name": "do_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071579499680,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2798
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:711",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:__ia32_sys_exit",
        "kernel/exit.c:__x64_sys_exit",
        "kernel/exit.c:complete_and_exit",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/buffer.c:__ia32_sys_bdflush",
        "fs/buffer.c:__x64_sys_bdflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529771,
      "name": "do_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071579525808,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2742
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:708",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:__ia32_sys_exit",
        "kernel/exit.c:__x64_sys_exit",
        "kernel/exit.c:complete_and_exit",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/buffer.c:__ia32_sys_bdflush",
        "fs/buffer.c:__x64_sys_bdflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579560315,
      "name": "do_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071579558016,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1077
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:727",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:__ia32_sys_exit",
        "kernel/exit.c:__x64_sys_exit",
        "kernel/exit.c:complete_and_exit",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch",
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/buffer.c:__ia32_sys_bdflush",
        "fs/buffer.c:__x64_sys_bdflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591278398,
      "name": "do_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071579539248,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 992
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:727",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:__ia32_sys_exit",
        "kernel/exit.c:__x64_sys_exit",
        "kernel/exit.c:complete_and_exit",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch",
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/buffer.c:__ia32_sys_bdflush",
        "fs/buffer.c:__x64_sys_bdflush",
        "fs/io_uring.c:io_sq_thread",
        "fs/io-wq.c:io_wqe_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591221296,
      "name": "do_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071579543408,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 971
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
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:727",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:__ia32_sys_exit",
        "kernel/exit.c:__x64_sys_exit",
        "kernel/exit.c:complete_and_exit",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/io_uring.c:io_sq_thread",
        "fs/io-wq.c:io_wqe_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592100230,
      "name": "do_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071579615904,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 959
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
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:736",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:__ia32_sys_exit",
        "kernel/exit.c:__x64_sys_exit",
        "kernel/exit.c:make_task_dead",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread_exit",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "io_uring/io_uring.c:io_sq_thread",
        "io_uring/io-wq.c:io_wqe_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593867810,
      "name": "do_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579708704,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1694
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
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579834432,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:805",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:__ia32_sys_exit",
        "kernel/exit.c:__x64_sys_exit",
        "kernel/exit.c:make_task_dead",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread_exit",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "io_uring/sqpoll.c:io_sq_thread",
        "io_uring/io-wq.c:io_wqe_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834432,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1720
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
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579883408,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:809",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:__ia32_sys_exit",
        "kernel/exit.c:__x64_sys_exit",
        "kernel/exit.c:make_task_dead",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread_exit",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/vhost_task.c:vhost_task_fn",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "io_uring/sqpoll.c:io_sq_thread",
        "io_uring/io-wq.c:io_wq_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579883408,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1764
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
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579919872,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:811",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:__ia32_sys_exit",
        "kernel/exit.c:__x64_sys_exit",
        "kernel/exit.c:make_task_dead",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread_exit",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/vhost_task.c:vhost_task_fn",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "io_uring/sqpoll.c:io_sq_thread",
        "io_uring/io-wq.c:io_wq_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579919872,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1314
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
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490668640,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:711",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/traps.c:die",
        "arch/arm64/mm/fault.c:die_kernel_fault",
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:__arm64_sys_exit",
        "kernel/exit.c:complete_and_exit",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/buffer.c:__arm64_sys_bdflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490668640,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2564
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
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224740620,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:711",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/traps.c:die",
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:__se_sys_exit",
        "kernel/exit.c:complete_and_exit",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/buffer.c:__se_sys_bdflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224740620,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2996
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
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283490912,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:711",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/signal_32.c:__do_compat_sys_swapcontext",
        "arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext",
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:__se_sys_exit",
        "kernel/exit.c:complete_and_exit",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/buffer.c:__se_sys_bdflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283490912,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3272
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
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271407892,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:711",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/traps.c:die",
        "arch/riscv/mm/fault.c:do_page_fault",
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:__se_sys_exit",
        "kernel/exit.c:complete_and_exit",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/buffer.c:__se_sys_bdflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271407892,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2262
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:711",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:__ia32_sys_exit",
        "kernel/exit.c:__x64_sys_exit",
        "kernel/exit.c:complete_and_exit",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/buffer.c:__ia32_sys_bdflush",
        "fs/buffer.c:__x64_sys_bdflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503435,
      "name": "do_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071579499472,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2742
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:711",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:__ia32_sys_exit",
        "kernel/exit.c:__x64_sys_exit",
        "kernel/exit.c:complete_and_exit",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/buffer.c:__ia32_sys_bdflush",
        "fs/buffer.c:__x64_sys_bdflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432299,
      "name": "do_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071579428352,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2726
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:711",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:__ia32_sys_exit",
        "kernel/exit.c:__x64_sys_exit",
        "kernel/exit.c:complete_and_exit",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/buffer.c:__ia32_sys_bdflush",
        "fs/buffer.c:__x64_sys_bdflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503355,
      "name": "do_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071579499392,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2742
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void do_exit(long int code)
```

```json
{
  "name": "do_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_exit",
      "external": true,
      "loc": "kernel/exit.c:711",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "kernel/exit.c:do_group_exit",
        "kernel/exit.c:__ia32_sys_exit",
        "kernel/exit.c:__x64_sys_exit",
        "kernel/exit.c:complete_and_exit",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/kthread.c:kthread",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__module_put_and_exit",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/seccomp.c:__secure_computing",
        "kernel/seccomp.c:__seccomp_filter",
        "fs/buffer.c:__ia32_sys_bdflush",
        "fs/buffer.c:__x64_sys_bdflush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535995,
      "name": "do_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071579532016,
      "name": "do_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2769
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
