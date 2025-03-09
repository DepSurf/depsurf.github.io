# Function: <code>get_compat_sigset</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```

```json
{
  "name": "get_compat_sigset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580072736,
      "name": "get_compat_sigset",
      "external": true,
      "loc": "kernel/compat.c:471",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_SyS_rt_sigsuspend",
        "kernel/signal.c:compat_SyS_rt_sigaction",
        "kernel/signal.c:C_SYSC_rt_sigtimedwait",
        "kernel/signal.c:compat_SyS_rt_sigprocmask",
        "fs/select.c:compat_SyS_ppoll",
        "fs/select.c:compat_SyS_pselect6",
        "fs/eventpoll.c:compat_SyS_epoll_pwait",
        "fs/signalfd.c:compat_SyS_signalfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072736,
      "name": "get_compat_sigset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```

```json
{
  "name": "get_compat_sigset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580132176,
      "name": "get_compat_sigset",
      "external": true,
      "loc": "kernel/compat.c:436",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__do_compat_sys_rt_sigtimedwait",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "fs/select.c:__x32_compat_sys_ppoll",
        "fs/select.c:__ia32_compat_sys_ppoll",
        "fs/select.c:do_compat_pselect",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/signalfd.c:do_compat_signalfd4",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132176,
      "name": "get_compat_sigset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```

```json
{
  "name": "get_compat_sigset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580179488,
      "name": "get_compat_sigset",
      "external": true,
      "loc": "kernel/compat.c:405",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "fs/signalfd.c:do_compat_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580179488,
      "name": "get_compat_sigset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```

```json
{
  "name": "get_compat_sigset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580225504,
      "name": "get_compat_sigset",
      "external": true,
      "loc": "kernel/compat.c:338",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "fs/signalfd.c:do_compat_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580225504,
      "name": "get_compat_sigset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```

```json
{
  "name": "get_compat_sigset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580273744,
      "name": "get_compat_sigset",
      "external": true,
      "loc": "kernel/compat.c:338",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "fs/signalfd.c:do_compat_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580273744,
      "name": "get_compat_sigset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```

```json
{
  "name": "get_compat_sigset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580342864,
      "name": "get_compat_sigset",
      "external": true,
      "loc": "kernel/compat.c:250",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "fs/signalfd.c:__x32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__x32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580342864,
      "name": "get_compat_sigset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```

```json
{
  "name": "get_compat_sigset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580327984,
      "name": "get_compat_sigset",
      "external": true,
      "loc": "kernel/compat.c:250",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "fs/signalfd.c:__x32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__x32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580327984,
      "name": "get_compat_sigset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```

```json
{
  "name": "get_compat_sigset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580331280,
      "name": "get_compat_sigset",
      "external": true,
      "loc": "kernel/compat.c:250",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "fs/signalfd.c:__x32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__x32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580331280,
      "name": "get_compat_sigset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```

```json
{
  "name": "get_compat_sigset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580486000,
      "name": "get_compat_sigset",
      "external": true,
      "loc": "kernel/compat.c:250",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x64_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__x64_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x64_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__x64_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "fs/signalfd.c:__x64_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__x64_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486000,
      "name": "get_compat_sigset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```

```json
{
  "name": "get_compat_sigset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580680800,
      "name": "get_compat_sigset",
      "external": true,
      "loc": "kernel/compat.c:250",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580680800,
      "name": "get_compat_sigset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```

```json
{
  "name": "get_compat_sigset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580951808,
      "name": "get_compat_sigset",
      "external": true,
      "loc": "kernel/compat.c:250",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580951808,
      "name": "get_compat_sigset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```

```json
{
  "name": "get_compat_sigset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581038816,
      "name": "get_compat_sigset",
      "external": true,
      "loc": "kernel/compat.c:250",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038816,
      "name": "get_compat_sigset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```

```json
{
  "name": "get_compat_sigset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136032,
      "name": "get_compat_sigset",
      "external": true,
      "loc": "kernel/compat.c:250",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136032,
      "name": "get_compat_sigset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```

```json
{
  "name": "get_compat_sigset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491516936,
      "name": "get_compat_sigset",
      "external": true,
      "loc": "kernel/compat.c:338",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__arm64_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__arm64_compat_sys_rt_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "fs/signalfd.c:__arm64_compat_sys_signalfd",
        "fs/signalfd.c:__arm64_compat_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491516936,
      "name": "get_compat_sigset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```

```json
{
  "name": "get_compat_sigset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284483536,
      "name": "get_compat_sigset",
      "external": true,
      "loc": "kernel/compat.c:338",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn",
        "arch/powerpc/kernel/signal_32.c:do_setcontext",
        "kernel/signal.c:__se_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__se_compat_sys_rt_sigaction",
        "kernel/signal.c:__se_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__se_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__se_compat_sys_rt_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "fs/signalfd.c:__se_compat_sys_signalfd",
        "fs/signalfd.c:__se_compat_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284483536,
      "name": "get_compat_sigset",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```

```json
{
  "name": "get_compat_sigset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580242544,
      "name": "get_compat_sigset",
      "external": true,
      "loc": "kernel/compat.c:338",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "fs/signalfd.c:do_compat_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580242544,
      "name": "get_compat_sigset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```

```json
{
  "name": "get_compat_sigset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580190096,
      "name": "get_compat_sigset",
      "external": true,
      "loc": "kernel/compat.c:338",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "fs/signalfd.c:do_compat_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580190096,
      "name": "get_compat_sigset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```

```json
{
  "name": "get_compat_sigset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580233792,
      "name": "get_compat_sigset",
      "external": true,
      "loc": "kernel/compat.c:338",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "fs/signalfd.c:do_compat_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580233792,
      "name": "get_compat_sigset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```

```json
{
  "name": "get_compat_sigset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580286784,
      "name": "get_compat_sigset",
      "external": true,
      "loc": "kernel/compat.c:338",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:set_compat_user_sigmask",
        "fs/signalfd.c:do_compat_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580286784,
      "name": "get_compat_sigset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int get_compat_sigset(sigset_t * set, const compat_sigset_t * compat)
```
</details>
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
