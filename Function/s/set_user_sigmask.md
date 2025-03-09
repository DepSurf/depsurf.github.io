# Function: <code>set_user_sigmask</code>

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
int set_user_sigmask(const sigset_t * usigmask, sigset_t * set, sigset_t * oldset, size_t sigsetsize)
```

```json
{
  "name": "set_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579538608,
      "name": "set_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2802",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538608,
      "name": "set_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int set_user_sigmask(const sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551744,
      "name": "set_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2964",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__do_sys_pselect6",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551744,
      "name": "set_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int set_user_sigmask(const sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579577872,
      "name": "set_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2969",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577872,
      "name": "set_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int set_user_sigmask(const sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579613344,
      "name": "set_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2987",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579613344,
      "name": "set_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int set_user_sigmask(const sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579593568,
      "name": "set_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:3007",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__do_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579593568,
      "name": "set_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int set_user_sigmask(const sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579599008,
      "name": "set_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:3029",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__do_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599008,
      "name": "set_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int set_user_sigmask(const sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579673904,
      "name": "set_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:3114",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673904,
      "name": "set_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int set_user_sigmask(const sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579770512,
      "name": "set_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:3094",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "io_uring/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579770512,
      "name": "set_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int set_user_sigmask(const sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579902464,
      "name": "set_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:3096",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "io_uring/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902464,
      "name": "set_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int set_user_sigmask(const sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952192,
      "name": "set_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:3120",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "io_uring/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952192,
      "name": "set_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int set_user_sigmask(const sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579991488,
      "name": "set_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:3131",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "io_uring/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991488,
      "name": "set_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int set_user_sigmask(const sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490740552,
      "name": "set_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2969",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__arm64_sys_ppoll",
        "fs/select.c:__arm64_sys_pselect6",
        "fs/eventpoll.c:__arm64_sys_epoll_pwait",
        "fs/aio.c:__arm64_sys_io_pgetevents",
        "fs/io_uring.c:__arm64_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490740552,
      "name": "set_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int set_user_sigmask(const sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224790808,
      "name": "set_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2969",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__se_sys_ppoll_time32",
        "fs/select.c:__se_sys_ppoll",
        "fs/select.c:do_pselect",
        "fs/eventpoll.c:__se_sys_epoll_pwait",
        "fs/aio.c:__se_sys_io_pgetevents_time32",
        "fs/aio.c:__se_sys_io_pgetevents",
        "fs/io_uring.c:__se_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224790808,
      "name": "set_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int set_user_sigmask(const sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283564304,
      "name": "set_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2969",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__se_sys_ppoll",
        "fs/select.c:__se_sys_pselect6",
        "fs/eventpoll.c:__se_sys_epoll_pwait",
        "fs/aio.c:__se_sys_io_pgetevents",
        "fs/io_uring.c:__se_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283564304,
      "name": "set_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int set_user_sigmask(const sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271446564,
      "name": "set_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2969",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__se_sys_ppoll",
        "fs/select.c:__se_sys_pselect6",
        "fs/eventpoll.c:__se_sys_epoll_pwait",
        "fs/aio.c:__se_sys_io_pgetevents",
        "fs/io_uring.c:__se_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271446564,
      "name": "set_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int set_user_sigmask(const sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579554176,
      "name": "set_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2969",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554176,
      "name": "set_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int set_user_sigmask(const sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579482880,
      "name": "set_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2969",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579482880,
      "name": "set_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int set_user_sigmask(const sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551456,
      "name": "set_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2969",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551456,
      "name": "set_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int set_user_sigmask(const sigset_t * umask, size_t sigsetsize)
```

```json
{
  "name": "set_user_sigmask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579584592,
      "name": "set_user_sigmask",
      "external": true,
      "loc": "kernel/signal.c:2969",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/aio.c:__ia32_sys_io_pgetevents",
        "fs/aio.c:__x64_sys_io_pgetevents",
        "fs/io_uring.c:io_cqring_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579584592,
      "name": "set_user_sigmask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int set_user_sigmask(const sigset_t * usigmask, sigset_t * set, sigset_t * oldset, size_t sigsetsize)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const sigset_t * umask</code>
</li>
<li>
<b>Param removed. </b>
<code>const sigset_t * usigmask</code>
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
