# Function: <code>set_current_blocked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579437632,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2478",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:SyS_sigprocmask",
        "kernel/signal.c:SyS_ssetmask"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys_rt_sigreturn",
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn",
        "kernel/compat.c:compat_SyS_sigprocmask",
        "kernel/compat.c:compat_SyS_sigprocmask",
        "fs/eventpoll.c:SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_pwait",
        "fs/eventpoll.c:compat_SyS_epoll_pwait",
        "fs/eventpoll.c:compat_SyS_epoll_pwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579437632,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579450321,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2478",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:SyS_ssetmask",
        "kernel/signal.c:SyS_sigprocmask",
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_sigreturn",
        "kernel/compat.c:compat_SyS_sigprocmask",
        "kernel/compat.c:compat_SyS_sigprocmask",
        "fs/eventpoll.c:compat_SyS_epoll_pwait",
        "fs/eventpoll.c:compat_SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_pwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579450080,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579470801,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2484",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:SyS_ssetmask",
        "kernel/signal.c:SyS_sigprocmask",
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_sigreturn",
        "kernel/compat.c:compat_SyS_sigprocmask",
        "kernel/compat.c:compat_SyS_sigprocmask",
        "fs/eventpoll.c:compat_SyS_epoll_pwait",
        "fs/eventpoll.c:compat_SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_pwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579470560,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579459169,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2505",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:SyS_ssetmask",
        "kernel/signal.c:SyS_sigprocmask",
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_sigreturn",
        "kernel/compat.c:compat_SyS_sigprocmask",
        "fs/eventpoll.c:compat_SyS_epoll_pwait",
        "fs/eventpoll.c:compat_SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_pwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579458928,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579487409,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2506",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:SyS_ssetmask",
        "kernel/signal.c:SyS_sigprocmask",
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_sigreturn",
        "kernel/compat.c:compat_SyS_sigprocmask",
        "fs/eventpoll.c:compat_SyS_epoll_pwait",
        "fs/eventpoll.c:compat_SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_pwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487168,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579505265,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2639",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__ia32_sys_ssetmask",
        "kernel/signal.c:__x64_sys_ssetmask",
        "kernel/signal.c:__ia32_sys_sigprocmask",
        "kernel/signal.c:__x64_sys_sigprocmask",
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_sigreturn",
        "kernel/compat.c:__x32_compat_sys_sigprocmask",
        "kernel/compat.c:__ia32_compat_sys_sigprocmask",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579504544,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579539441,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2738",
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
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_sigreturn",
        "kernel/compat.c:__x32_compat_sys_sigprocmask",
        "kernel/compat.c:__ia32_compat_sys_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538400,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579549825,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2897",
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
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:sys32_sigreturn",
        "kernel/compat.c:__x32_compat_sys_sigprocmask",
        "kernel/compat.c:__ia32_compat_sys_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549280,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579575953,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2902",
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
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn",
        "kernel/compat.c:__x32_compat_sys_sigprocmask",
        "kernel/compat.c:__ia32_compat_sys_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579575408,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579611409,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2920",
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
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__do_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn",
        "kernel/compat.c:__x32_compat_sys_sigprocmask",
        "kernel/compat.c:__ia32_compat_sys_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579610928,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579591617,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2940",
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
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__do_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn",
        "kernel/compat.c:__x32_compat_sys_sigprocmask",
        "kernel/compat.c:__ia32_compat_sys_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579591136,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579588195,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2962",
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
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__do_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn",
        "kernel/compat.c:__x32_compat_sys_sigprocmask",
        "kernel/compat.c:__ia32_compat_sys_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579598304,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579663459,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:3047",
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
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__do_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn",
        "kernel/compat.c:__x64_compat_sys_sigprocmask",
        "kernel/compat.c:__ia32_compat_sys_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673200,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579758403,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:3027",
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
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:__do_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn",
        "kernel/compat.c:__ia32_compat_sys_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579770304,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579892963,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:3029",
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
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn",
        "arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn",
        "arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn",
        "kernel/compat.c:__ia32_compat_sys_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902224,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579942259,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:3053",
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
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn",
        "arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn",
        "arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn",
        "kernel/compat.c:__ia32_compat_sys_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951952,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579981603,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:3064",
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
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn",
        "arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn",
        "arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn",
        "kernel/compat.c:__ia32_compat_sys_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991248,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490738876,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2902",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__arm64_sys_ssetmask",
        "kernel/signal.c:__arm64_sys_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/arm64/kernel/signal.c:restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe",
        "kernel/compat.c:__arm64_compat_sys_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490738176,
      "name": "set_current_blocked",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224790444,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2902",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__se_sys_ssetmask",
        "kernel/signal.c:__se_sys_sigprocmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/arm/kernel/signal.c:restore_sigframe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224790336,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283562756,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2902",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:__se_sys_ssetmask",
        "kernel/signal.c:__se_sys_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/powerpc/kernel/signal_32.c:compat_sys_sigreturn",
        "arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn",
        "arch/powerpc/kernel/signal_32.c:do_setcontext",
        "arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn",
        "arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext",
        "kernel/compat.c:__se_compat_sys_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283562128,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271458010,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2902",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_rt_sigsuspend",
        "kernel/signal.c:__se_sys_ssetmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/riscv/kernel/signal.c:sys_rt_sigreturn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271446362,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579552257,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2902",
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
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn",
        "kernel/compat.c:__x32_compat_sys_sigprocmask",
        "kernel/compat.c:__ia32_compat_sys_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551712,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579480961,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2902",
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
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn",
        "kernel/compat.c:__x32_compat_sys_sigprocmask",
        "kernel/compat.c:__ia32_compat_sys_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480416,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579549537,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2902",
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
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn",
        "kernel/compat.c:__x32_compat_sys_sigprocmask",
        "kernel/compat.c:__ia32_compat_sys_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579548992,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void set_current_blocked(sigset_t * newset)
```

```json
{
  "name": "set_current_blocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579582673,
      "name": "set_current_blocked",
      "external": true,
      "loc": "kernel/signal.c:2902",
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
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn",
        "arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn",
        "arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn",
        "kernel/compat.c:__x32_compat_sys_sigprocmask",
        "kernel/compat.c:__ia32_compat_sys_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579582128,
      "name": "set_current_blocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
