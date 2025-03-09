# Function: <code>__set_current_blocked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579437536,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2484",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:SyS_sigprocmask",
        "kernel/signal.c:SyS_ssetmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579437536,
      "name": "__set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579449984,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2484",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:SyS_ssetmask",
        "kernel/signal.c:SyS_sigprocmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579449984,
      "name": "__set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579470448,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2490",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:SyS_ssetmask",
        "kernel/signal.c:SyS_sigprocmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579470448,
      "name": "__set_current_blocked",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579458816,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2511",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:SyS_ssetmask",
        "kernel/signal.c:SyS_sigprocmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579458816,
      "name": "__set_current_blocked",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579487056,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2512",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:SyS_ssetmask",
        "kernel/signal.c:SyS_sigprocmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487056,
      "name": "__set_current_blocked",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579504432,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2645",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__ia32_sys_ssetmask",
        "kernel/signal.c:__x64_sys_ssetmask",
        "kernel/signal.c:__ia32_sys_sigprocmask",
        "kernel/signal.c:__x64_sys_sigprocmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579504432,
      "name": "__set_current_blocked",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579538288,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2744",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__ia32_sys_ssetmask",
        "kernel/signal.c:__x64_sys_ssetmask",
        "kernel/signal.c:__ia32_sys_sigprocmask",
        "kernel/signal.c:__x64_sys_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538288,
      "name": "__set_current_blocked",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579549184,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2903",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__ia32_sys_ssetmask",
        "kernel/signal.c:__x64_sys_ssetmask",
        "kernel/signal.c:__ia32_sys_sigprocmask",
        "kernel/signal.c:__x64_sys_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done",
        "fs/select.c:poll_select_finish",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549184,
      "name": "__set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579575312,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2908",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__ia32_sys_ssetmask",
        "kernel/signal.c:__x64_sys_ssetmask",
        "kernel/signal.c:__ia32_sys_sigprocmask",
        "kernel/signal.c:__x64_sys_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done",
        "fs/select.c:poll_select_finish",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579575312,
      "name": "__set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579602237,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2926",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_ssetmask",
        "kernel/signal.c:__x64_sys_ssetmask"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__ia32_sys_sigprocmask",
        "kernel/signal.c:__x64_sys_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done",
        "fs/select.c:poll_select_finish",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611024,
      "name": "__set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579582445,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2946",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_ssetmask",
        "kernel/signal.c:__x64_sys_ssetmask"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:arch_do_signal_or_restart",
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__ia32_sys_sigprocmask",
        "kernel/signal.c:__x64_sys_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done",
        "fs/select.c:poll_select_finish",
        "fs/aio.c:__do_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__do_compat_sys_io_pgetevents",
        "fs/aio.c:__do_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579591232,
      "name": "__set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579588207,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2968",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__ia32_sys_ssetmask",
        "kernel/signal.c:__x64_sys_ssetmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:arch_do_signal_or_restart",
        "kernel/signal.c:__ia32_sys_sigprocmask",
        "kernel/signal.c:__x64_sys_sigprocmask",
        "fs/select.c:poll_select_finish",
        "fs/aio.c:__do_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__do_compat_sys_io_pgetevents",
        "fs/aio.c:__do_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579598400,
      "name": "__set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579663471,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:3053",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__ia32_sys_ssetmask",
        "kernel/signal.c:__x64_sys_ssetmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:sigprocmask"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:arch_do_signal_or_restart",
        "kernel/signal.c:__ia32_sys_sigprocmask",
        "kernel/signal.c:__x64_sys_sigprocmask",
        "kernel/signal.c:signal_setup_done",
        "fs/select.c:poll_select_finish",
        "fs/aio.c:__x64_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x64_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673296,
      "name": "__set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579758415,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:3033",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__ia32_sys_ssetmask",
        "kernel/signal.c:__x64_sys_ssetmask",
        "kernel/signal.c:__ia32_sys_sigprocmask",
        "kernel/signal.c:__x64_sys_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:arch_do_signal_or_restart",
        "fs/select.c:poll_select_finish",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "io_uring/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579770416,
      "name": "__set_current_blocked",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579892975,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:3035",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__ia32_sys_ssetmask",
        "kernel/signal.c:__x64_sys_ssetmask",
        "kernel/signal.c:__ia32_sys_sigprocmask",
        "kernel/signal.c:__x64_sys_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:arch_do_signal_or_restart",
        "fs/select.c:poll_select_finish",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "io_uring/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902352,
      "name": "__set_current_blocked",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579942271,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:3059",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__ia32_sys_ssetmask",
        "kernel/signal.c:__x64_sys_ssetmask",
        "kernel/signal.c:__ia32_sys_sigprocmask",
        "kernel/signal.c:__x64_sys_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:arch_do_signal_or_restart",
        "fs/select.c:poll_select_finish",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "io_uring/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952080,
      "name": "__set_current_blocked",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579981615,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:3070",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__ia32_sys_ssetmask",
        "kernel/signal.c:__x64_sys_ssetmask",
        "kernel/signal.c:__ia32_sys_sigprocmask",
        "kernel/signal.c:__x64_sys_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:arch_do_signal_or_restart",
        "fs/select.c:poll_select_finish",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "io_uring/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991376,
      "name": "__set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490738000,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2908",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/signal.c:do_notify_resume",
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__arm64_sys_ssetmask",
        "kernel/signal.c:__arm64_sys_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done",
        "fs/select.c:poll_select_finish",
        "fs/eventpoll.c:__arm64_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__arm64_sys_epoll_pwait",
        "fs/aio.c:__arm64_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__arm64_compat_sys_io_pgetevents",
        "fs/aio.c:__arm64_sys_io_pgetevents",
        "fs/io_uring.c:__arm64_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490738000,
      "name": "__set_current_blocked",
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
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224790204,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2908",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/signal.c:do_work_pending",
        "arch/arm/kernel/signal.c:do_work_pending",
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__se_sys_ssetmask",
        "kernel/signal.c:__se_sys_sigprocmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done",
        "fs/select.c:poll_select_finish",
        "fs/eventpoll.c:__se_sys_epoll_pwait",
        "fs/aio.c:__se_sys_io_pgetevents_time32",
        "fs/aio.c:__se_sys_io_pgetevents",
        "fs/io_uring.c:__se_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224790204,
      "name": "__set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283561936,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2908",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/signal.c:do_notify_resume",
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__se_sys_ssetmask",
        "kernel/signal.c:__se_sys_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done",
        "fs/select.c:poll_select_finish",
        "fs/eventpoll.c:__se_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__se_sys_epoll_pwait",
        "fs/aio.c:__se_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__se_compat_sys_io_pgetevents",
        "fs/aio.c:__se_sys_io_pgetevents",
        "fs/io_uring.c:__se_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283561936,
      "name": "__set_current_blocked",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271446218,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2908",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/signal.c:do_notify_resume",
        "kernel/signal.c:__se_sys_rt_sigsuspend",
        "kernel/signal.c:__se_sys_ssetmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done",
        "fs/select.c:poll_select_finish",
        "fs/eventpoll.c:__se_sys_epoll_pwait",
        "fs/aio.c:__se_sys_io_pgetevents",
        "fs/io_uring.c:__se_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271446218,
      "name": "__set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551616,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2908",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__ia32_sys_ssetmask",
        "kernel/signal.c:__x64_sys_ssetmask",
        "kernel/signal.c:__ia32_sys_sigprocmask",
        "kernel/signal.c:__x64_sys_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done",
        "fs/select.c:poll_select_finish",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551616,
      "name": "__set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579480336,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2908",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__ia32_sys_ssetmask",
        "kernel/signal.c:__x64_sys_ssetmask",
        "kernel/signal.c:__ia32_sys_sigprocmask",
        "kernel/signal.c:__x64_sys_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done",
        "fs/select.c:poll_select_finish",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480336,
      "name": "__set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579548896,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2908",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__ia32_sys_ssetmask",
        "kernel/signal.c:__x64_sys_ssetmask",
        "kernel/signal.c:__ia32_sys_sigprocmask",
        "kernel/signal.c:__x64_sys_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done",
        "fs/select.c:poll_select_finish",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579548896,
      "name": "__set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __set_current_blocked(const sigset_t * newset)
```

```json
{
  "name": "__set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579582048,
      "name": "__set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2908",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__ia32_sys_ssetmask",
        "kernel/signal.c:__x64_sys_ssetmask",
        "kernel/signal.c:__ia32_sys_sigprocmask",
        "kernel/signal.c:__x64_sys_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:sigprocmask",
        "kernel/signal.c:signal_setup_done",
        "fs/select.c:poll_select_finish",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579582048,
      "name": "__set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
