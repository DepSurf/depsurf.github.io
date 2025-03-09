# Function: <code>SyS_epoll_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int SyS_epoll_wait(long int epfd, long int events, long int maxevents, long int timeout)
```

```json
{
  "name": "SyS_epoll_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581296800,
      "name": "SyS_epoll_wait",
      "external": true,
      "loc": "fs/eventpoll.c:1961",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:SyS_epoll_pwait",
        "fs/eventpoll.c:compat_SyS_epoll_pwait"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296800,
      "name": "SyS_epoll_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
long int SyS_epoll_wait(long int epfd, long int events, long int maxevents, long int timeout)
```

```json
{
  "name": "SyS_epoll_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581463911,
      "name": "SyS_epoll_wait",
      "external": true,
      "loc": "fs/eventpoll.c:2005",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:compat_SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_pwait"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581462992,
      "name": "SyS_epoll_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
long int SyS_epoll_wait(long int epfd, long int events, long int maxevents, long int timeout)
```

```json
{
  "name": "SyS_epoll_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581544679,
      "name": "SyS_epoll_wait",
      "external": true,
      "loc": "fs/eventpoll.c:2005",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:compat_SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_pwait"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581543776,
      "name": "SyS_epoll_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
long int SyS_epoll_wait(long int epfd, long int events, long int maxevents, long int timeout)
```

```json
{
  "name": "SyS_epoll_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581598551,
      "name": "SyS_epoll_wait",
      "external": true,
      "loc": "fs/eventpoll.c:2166",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:compat_SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_pwait"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581597616,
      "name": "SyS_epoll_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
long int SyS_epoll_wait(long int epfd, long int events, long int maxevents, long int timeout)
```

```json
{
  "name": "SyS_epoll_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581742900,
      "name": "SyS_epoll_wait",
      "external": true,
      "loc": "fs/eventpoll.c:2148",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:compat_SyS_epoll_pwait",
        "fs/eventpoll.c:SyS_epoll_pwait"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742000,
      "name": "SyS_epoll_wait",
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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
long int SyS_epoll_wait(long int epfd, long int events, long int maxevents, long int timeout)
```
</details>
</li>
</ul>
