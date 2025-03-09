# Function: <code>set_compat_user_sigmask</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int set_compat_user_sigmask(const compat_sigset_t * usigmask, sigset_t * set, sigset_t * oldset, size_t sigsetsize)
```

```json
{
  "name": "set_compat_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579538720,
      "name": "set_compat_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2821",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll",
        "fs/select.c:__ia32_compat_sys_ppoll",
        "fs/select.c:do_compat_pselect",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538720,
      "name": "set_compat_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int set_compat_user_sigmask(const compat_sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_compat_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551904,
      "name": "set_compat_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2983",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551904,
      "name": "set_compat_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int set_compat_user_sigmask(const compat_sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_compat_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579578032,
      "name": "set_compat_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2988",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578032,
      "name": "set_compat_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int set_compat_user_sigmask(const compat_sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_compat_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579613504,
      "name": "set_compat_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:3006",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579613504,
      "name": "set_compat_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int set_compat_user_sigmask(const compat_sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_compat_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579593728,
      "name": "set_compat_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:3026",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/aio.c:__do_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__do_compat_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579593728,
      "name": "set_compat_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int set_compat_user_sigmask(const compat_sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_compat_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579599232,
      "name": "set_compat_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:3048",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/aio.c:__do_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__do_compat_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599232,
      "name": "set_compat_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int set_compat_user_sigmask(const compat_sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_compat_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579674128,
      "name": "set_compat_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:3133",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x64_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x64_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/eventpoll.c:__x64_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/aio.c:__x64_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x64_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674128,
      "name": "set_compat_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int set_compat_user_sigmask(const compat_sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_compat_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579770736,
      "name": "set_compat_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:3113",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "io_uring/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579770736,
      "name": "set_compat_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
int set_compat_user_sigmask(const compat_sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_compat_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579902704,
      "name": "set_compat_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:3115",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "io_uring/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902704,
      "name": "set_compat_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
int set_compat_user_sigmask(const compat_sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_compat_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952432,
      "name": "set_compat_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:3139",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "io_uring/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952432,
      "name": "set_compat_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
int set_compat_user_sigmask(const compat_sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_compat_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579991728,
      "name": "set_compat_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:3150",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "io_uring/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991728,
      "name": "set_compat_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
int set_compat_user_sigmask(const compat_sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_compat_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490740872,
      "name": "set_compat_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2988",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__arm64_compat_sys_ppoll_time64",
        "fs/select.c:__arm64_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/eventpoll.c:__arm64_compat_sys_epoll_pwait",
        "fs/aio.c:__arm64_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__arm64_compat_sys_io_pgetevents",
        "fs/io_uring.c:__arm64_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490740872,
      "name": "set_compat_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int set_compat_user_sigmask(const compat_sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_compat_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283564544,
      "name": "set_compat_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2988",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__se_compat_sys_ppoll_time64",
        "fs/select.c:__se_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/eventpoll.c:__se_compat_sys_epoll_pwait",
        "fs/aio.c:__se_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__se_compat_sys_io_pgetevents",
        "fs/io_uring.c:__se_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283564544,
      "name": "set_compat_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int set_compat_user_sigmask(const compat_sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_compat_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579554336,
      "name": "set_compat_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2988",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554336,
      "name": "set_compat_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int set_compat_user_sigmask(const compat_sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_compat_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579483040,
      "name": "set_compat_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2988",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483040,
      "name": "set_compat_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int set_compat_user_sigmask(const compat_sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_compat_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551616,
      "name": "set_compat_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2988",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551616,
      "name": "set_compat_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int set_compat_user_sigmask(const compat_sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_compat_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579584752,
      "name": "set_compat_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2988",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/aio.c:__x32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents_time64",
        "fs/aio.c:__x32_compat_sys_io_pgetevents",
        "fs/aio.c:__ia32_compat_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579584752,
      "name": "set_compat_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int set_compat_user_sigmask(const compat_sigset_t * usigmask, sigset_t * set, sigset_t * oldset, size_t sigsetsize)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const compat_sigset_t * umask</code>
</li>
<li>
<b>Param removed. </b>
<code>const compat_sigset_t * usigmask</code>
</li>
<li>
<b>Param removed. </b>
<code>sigset_t * set</code>
</li>
<li>
<b>Param removed. </b>
<code>sigset_t * oldset</code>
</li>
<li>
<b>Param reordered. </b>
<code>usigmask, set, oldset, sigsetsize</code> ➡️ <code>umask, sigsetsize</code>
</li>
</ul>
</details>
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
int set_compat_user_sigmask(const compat_sigset_t * umask, size_t sigsetsize)
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
int set_compat_user_sigmask(const compat_sigset_t * umask, size_t sigsetsize)
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
