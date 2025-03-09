# Function: <code>poll_select_set_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int poll_select_set_timeout(struct timespec * to, long int sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581077424,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:272",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:SyS_select",
        "fs/select.c:SyS_pselect6",
        "fs/select.c:SyS_poll",
        "fs/select.c:SyS_ppoll",
        "fs/compat.c:compat_SyS_old_select",
        "fs/compat.c:compat_SyS_pselect6",
        "fs/compat.c:compat_SyS_ppoll",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077424,
      "name": "poll_select_set_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int poll_select_set_timeout(struct timespec * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581240368,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:272",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_poll",
        "fs/select.c:SyS_pselect6",
        "fs/select.c:SyS_select",
        "fs/compat.c:compat_SyS_ppoll",
        "fs/compat.c:compat_SyS_pselect6",
        "fs/compat.c:compat_SyS_old_select",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581240368,
      "name": "poll_select_set_timeout",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int poll_select_set_timeout(struct timespec * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581318240,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:273",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_poll",
        "fs/select.c:SyS_pselect6",
        "fs/select.c:SyS_select",
        "fs/compat.c:compat_SyS_ppoll",
        "fs/compat.c:compat_SyS_pselect6",
        "fs/compat.c:compat_SyS_old_select",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581318240,
      "name": "poll_select_set_timeout",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int poll_select_set_timeout(struct timespec * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581375680,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:273",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_SyS_ppoll",
        "fs/select.c:compat_SyS_pselect6",
        "fs/select.c:compat_SyS_old_select",
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_poll",
        "fs/select.c:SyS_pselect6",
        "fs/select.c:SyS_select",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581375680,
      "name": "poll_select_set_timeout",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int poll_select_set_timeout(struct timespec * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581517152,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:274",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_SyS_ppoll",
        "fs/select.c:compat_SyS_pselect6",
        "fs/select.c:compat_SyS_old_select",
        "fs/select.c:SyS_ppoll",
        "fs/select.c:SyS_poll",
        "fs/select.c:SyS_pselect6",
        "fs/select.c:SyS_select",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517152,
      "name": "poll_select_set_timeout",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int poll_select_set_timeout(struct timespec64 * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581674736,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:273",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll",
        "fs/select.c:__ia32_compat_sys_ppoll",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:do_pselect",
        "fs/select.c:kern_select",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581674736,
      "name": "poll_select_set_timeout",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int poll_select_set_timeout(struct timespec64 * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581761040,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:273",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll",
        "fs/select.c:__ia32_compat_sys_ppoll",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6",
        "fs/select.c:kern_select",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581761040,
      "name": "poll_select_set_timeout",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int poll_select_set_timeout(struct timespec64 * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581878704,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:273",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:__do_sys_pselect6",
        "fs/select.c:kern_select",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581878704,
      "name": "poll_select_set_timeout",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int poll_select_set_timeout(struct timespec64 * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581950928,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:273",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:kern_select",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581950928,
      "name": "poll_select_set_timeout",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int poll_select_set_timeout(struct timespec64 * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582185346,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:273",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select",
        "fs/select.c:kern_select"
      ],
      "caller_func": [
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582185920,
      "name": "poll_select_set_timeout",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int poll_select_set_timeout(struct timespec64 * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582232754,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:273",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select",
        "fs/select.c:kern_select"
      ],
      "caller_func": [
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582233328,
      "name": "poll_select_set_timeout",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int poll_select_set_timeout(struct timespec64 * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582258562,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:273",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select",
        "fs/select.c:kern_select"
      ],
      "caller_func": [
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582259136,
      "name": "poll_select_set_timeout",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int poll_select_set_timeout(struct timespec64 * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582576786,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:273",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:__x64_compat_sys_ppoll_time64",
        "fs/select.c:__x64_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x64_compat_sys_ppoll_time32",
        "fs/select.c:__x64_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select",
        "fs/select.c:kern_select"
      ],
      "caller_func": [
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/eventpoll.c:__x64_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582577024,
      "name": "poll_select_set_timeout",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int poll_select_set_timeout(struct timespec64 * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583105109,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:274",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select",
        "fs/select.c:kern_select"
      ],
      "caller_func": [
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583105712,
      "name": "poll_select_set_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int poll_select_set_timeout(struct timespec64 * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583673557,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:274",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select",
        "fs/select.c:kern_select"
      ],
      "caller_func": [
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583674192,
      "name": "poll_select_set_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int poll_select_set_timeout(struct timespec64 * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583890821,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:274",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select",
        "fs/select.c:kern_select"
      ],
      "caller_func": [
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583891456,
      "name": "poll_select_set_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int poll_select_set_timeout(struct timespec64 * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584097989,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:274",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:kern_select",
        "fs/select.c:kern_select"
      ],
      "caller_func": [
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait2",
        "fs/eventpoll.c:__x64_sys_epoll_pwait2",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584098624,
      "name": "poll_select_set_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int poll_select_set_timeout(struct timespec64 * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493446808,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:273",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__arm64_compat_sys_ppoll_time64",
        "fs/select.c:__arm64_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__arm64_sys_ppoll",
        "fs/select.c:__arm64_sys_poll",
        "fs/select.c:__arm64_sys_pselect6",
        "fs/select.c:__arm64_sys_select",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493446808,
      "name": "poll_select_set_timeout",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int poll_select_set_timeout(struct timespec64 * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227016792,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:273",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__se_sys_ppoll_time32",
        "fs/select.c:__se_sys_ppoll",
        "fs/select.c:__se_sys_poll",
        "fs/select.c:do_pselect",
        "fs/select.c:kern_select",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227016792,
      "name": "poll_select_set_timeout",
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int poll_select_set_timeout(struct timespec64 * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287002144,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:273",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__se_compat_sys_ppoll_time64",
        "fs/select.c:__se_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__se_sys_ppoll",
        "fs/select.c:__se_sys_poll",
        "fs/select.c:__se_sys_pselect6",
        "fs/select.c:__se_sys_select",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287002144,
      "name": "poll_select_set_timeout",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int poll_select_set_timeout(struct timespec64 * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273134700,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:273",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__se_sys_ppoll",
        "fs/select.c:__se_sys_poll",
        "fs/select.c:__se_sys_pselect6",
        "fs/select.c:__se_sys_select",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273134700,
      "name": "poll_select_set_timeout",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int poll_select_set_timeout(struct timespec64 * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581919664,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:273",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:kern_select",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581919664,
      "name": "poll_select_set_timeout",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int poll_select_set_timeout(struct timespec64 * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581857248,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:273",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:kern_select",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581857248,
      "name": "poll_select_set_timeout",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int poll_select_set_timeout(struct timespec64 * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581910976,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:273",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:kern_select",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581910976,
      "name": "poll_select_set_timeout",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int poll_select_set_timeout(struct timespec64 * to, time64_t sec, long int nsec)
```

```json
{
  "name": "poll_select_set_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581980608,
      "name": "poll_select_set_timeout",
      "external": true,
      "loc": "fs/select.c:273",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll_time64",
        "fs/select.c:__ia32_compat_sys_ppoll_time64",
        "fs/select.c:__x32_compat_sys_ppoll_time32",
        "fs/select.c:__ia32_compat_sys_ppoll_time32",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select",
        "fs/select.c:__ia32_sys_ppoll",
        "fs/select.c:__x64_sys_ppoll",
        "fs/select.c:__ia32_sys_poll",
        "fs/select.c:__x64_sys_poll",
        "fs/select.c:kern_select",
        "net/socket.c:do_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581980608,
      "name": "poll_select_set_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long int sec</code> ➡️ <code>time64_t sec</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec * to</code> ➡️ <code>struct timespec64 * to</code>
</li>
</ul>
</details>
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
