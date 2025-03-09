# Function: <code>do_epoll_wait</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, int timeout)
```

```json
{
  "name": "do_epoll_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902944,
      "name": "do_epoll_wait",
      "external": false,
      "loc": "fs/eventpoll.c:2155",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_wait",
        "fs/eventpoll.c:__x64_sys_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902944,
      "name": "do_epoll_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, int timeout)
```

```json
{
  "name": "do_epoll_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581993600,
      "name": "do_epoll_wait",
      "external": false,
      "loc": "fs/eventpoll.c:2181",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_wait",
        "fs/eventpoll.c:__x64_sys_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581993600,
      "name": "do_epoll_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, int timeout)
```

```json
{
  "name": "do_epoll_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582129440,
      "name": "do_epoll_wait",
      "external": false,
      "loc": "fs/eventpoll.c:2259",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_wait",
        "fs/eventpoll.c:__x64_sys_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582129440,
      "name": "do_epoll_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, int timeout)
```

```json
{
  "name": "do_epoll_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582204544,
      "name": "do_epoll_wait",
      "external": false,
      "loc": "fs/eventpoll.c:2259",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_wait",
        "fs/eventpoll.c:__x64_sys_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582204544,
      "name": "do_epoll_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, int timeout)
```

```json
{
  "name": "do_epoll_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582443568,
      "name": "do_epoll_wait",
      "external": false,
      "loc": "fs/eventpoll.c:2288",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_wait",
        "fs/eventpoll.c:__x64_sys_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582443568,
      "name": "do_epoll_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, struct timespec64 * to)
```

```json
{
  "name": "do_epoll_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582497776,
      "name": "do_epoll_wait",
      "external": false,
      "loc": "fs/eventpoll.c:2185",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_wait",
        "fs/eventpoll.c:__x64_sys_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582497776,
      "name": "do_epoll_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, struct timespec64 * to)
```

```json
{
  "name": "do_epoll_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582524272,
      "name": "do_epoll_wait",
      "external": false,
      "loc": "fs/eventpoll.c:2191",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_wait",
        "fs/eventpoll.c:__x64_sys_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582524272,
      "name": "do_epoll_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, struct timespec64 * to)
```

```json
{
  "name": "do_epoll_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582840288,
      "name": "do_epoll_wait",
      "external": false,
      "loc": "fs/eventpoll.c:2192",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_wait",
        "fs/eventpoll.c:__x64_sys_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582840288,
      "name": "do_epoll_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, struct timespec64 * to)
```

```json
{
  "name": "do_epoll_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583400880,
      "name": "do_epoll_wait",
      "external": false,
      "loc": "fs/eventpoll.c:2221",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_wait",
        "fs/eventpoll.c:__x64_sys_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583400880,
      "name": "do_epoll_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, struct timespec64 * to)
```

```json
{
  "name": "do_epoll_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583988976,
      "name": "do_epoll_wait",
      "external": false,
      "loc": "fs/eventpoll.c:2223",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_wait",
        "fs/eventpoll.c:__x64_sys_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583988976,
      "name": "do_epoll_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, struct timespec64 * to)
```

```json
{
  "name": "do_epoll_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584210848,
      "name": "do_epoll_wait",
      "external": false,
      "loc": "fs/eventpoll.c:2291",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_wait",
        "fs/eventpoll.c:__x64_sys_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584210848,
      "name": "do_epoll_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, struct timespec64 * to)
```

```json
{
  "name": "do_epoll_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584425344,
      "name": "do_epoll_wait",
      "external": false,
      "loc": "fs/eventpoll.c:2282",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_wait",
        "fs/eventpoll.c:__x64_sys_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584425344,
      "name": "do_epoll_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, int timeout)
```

```json
{
  "name": "do_epoll_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493771440,
      "name": "do_epoll_wait",
      "external": false,
      "loc": "fs/eventpoll.c:2259",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__arm64_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__arm64_sys_epoll_pwait",
        "fs/eventpoll.c:__arm64_sys_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493771440,
      "name": "do_epoll_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, int timeout)
```

```json
{
  "name": "do_epoll_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227280380,
      "name": "do_epoll_wait",
      "external": false,
      "loc": "fs/eventpoll.c:2259",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__se_sys_epoll_pwait",
        "fs/eventpoll.c:__se_sys_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227280380,
      "name": "do_epoll_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1252
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
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, int timeout)
```

```json
{
  "name": "do_epoll_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287375408,
      "name": "do_epoll_wait",
      "external": false,
      "loc": "fs/eventpoll.c:2259",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__se_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__se_sys_epoll_pwait",
        "fs/eventpoll.c:__se_sys_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287375408,
      "name": "do_epoll_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, int timeout)
```

```json
{
  "name": "do_epoll_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273363452,
      "name": "do_epoll_wait",
      "external": false,
      "loc": "fs/eventpoll.c:2259",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__se_sys_epoll_pwait",
        "fs/eventpoll.c:__se_sys_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273363452,
      "name": "do_epoll_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 804
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
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, int timeout)
```

```json
{
  "name": "do_epoll_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582173280,
      "name": "do_epoll_wait",
      "external": false,
      "loc": "fs/eventpoll.c:2259",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_wait",
        "fs/eventpoll.c:__x64_sys_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582173280,
      "name": "do_epoll_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, int timeout)
```

```json
{
  "name": "do_epoll_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582105904,
      "name": "do_epoll_wait",
      "external": false,
      "loc": "fs/eventpoll.c:2259",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_wait",
        "fs/eventpoll.c:__x64_sys_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582105904,
      "name": "do_epoll_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, int timeout)
```

```json
{
  "name": "do_epoll_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582163760,
      "name": "do_epoll_wait",
      "external": false,
      "loc": "fs/eventpoll.c:2259",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_wait",
        "fs/eventpoll.c:__x64_sys_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582163760,
      "name": "do_epoll_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, int timeout)
```

```json
{
  "name": "do_epoll_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582232064,
      "name": "do_epoll_wait",
      "external": false,
      "loc": "fs/eventpoll.c:2259",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__x32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_compat_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_pwait",
        "fs/eventpoll.c:__x64_sys_epoll_pwait",
        "fs/eventpoll.c:__ia32_sys_epoll_wait",
        "fs/eventpoll.c:__x64_sys_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582232064,
      "name": "do_epoll_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int do_epoll_wait(int epfd, struct epoll_event * events, int maxevents, int timeout)
```
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct timespec64 * to</code>
</li>
<li>
<b>Param removed. </b>
<code>int timeout</code>
</li>
</ul>
</details>
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
