# Function: <code>__sys_shutdown_sock</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __sys_shutdown_sock(struct socket * sock, int how)
```

```json
{
  "name": "__sys_shutdown_sock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589206253,
      "name": "__sys_shutdown_sock",
      "external": true,
      "loc": "net/socket.c:2178",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_shutdown"
      ],
      "caller_func": [
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589206128,
      "name": "__sys_shutdown_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int __sys_shutdown_sock(struct socket * sock, int how)
```

```json
{
  "name": "__sys_shutdown_sock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589099917,
      "name": "__sys_shutdown_sock",
      "external": true,
      "loc": "net/socket.c:2172",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_shutdown"
      ],
      "caller_func": [
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589099792,
      "name": "__sys_shutdown_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int __sys_shutdown_sock(struct socket * sock, int how)
```

```json
{
  "name": "__sys_shutdown_sock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589817565,
      "name": "__sys_shutdown_sock",
      "external": true,
      "loc": "net/socket.c:2245",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_shutdown"
      ],
      "caller_func": [
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589817440,
      "name": "__sys_shutdown_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int __sys_shutdown_sock(struct socket * sock, int how)
```

```json
{
  "name": "__sys_shutdown_sock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591337700,
      "name": "__sys_shutdown_sock",
      "external": true,
      "loc": "net/socket.c:2320",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_shutdown"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591337568,
      "name": "__sys_shutdown_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int __sys_shutdown_sock(struct socket * sock, int how)
```

```json
{
  "name": "__sys_shutdown_sock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593093092,
      "name": "__sys_shutdown_sock",
      "external": true,
      "loc": "net/socket.c:2312",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_shutdown"
      ],
      "caller_func": [
        "io_uring/net.c:io_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593092944,
      "name": "__sys_shutdown_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int __sys_shutdown_sock(struct socket * sock, int how)
```

```json
{
  "name": "__sys_shutdown_sock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593545268,
      "name": "__sys_shutdown_sock",
      "external": true,
      "loc": "net/socket.c:2349",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_shutdown"
      ],
      "caller_func": [
        "io_uring/net.c:io_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593545120,
      "name": "__sys_shutdown_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int __sys_shutdown_sock(struct socket * sock, int how)
```

```json
{
  "name": "__sys_shutdown_sock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594317556,
      "name": "__sys_shutdown_sock",
      "external": true,
      "loc": "net/socket.c:2419",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_shutdown",
        "net/socket.c:__sys_shutdown"
      ],
      "caller_func": [
        "io_uring/net.c:io_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594317408,
      "name": "__sys_shutdown_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int __sys_shutdown_sock(struct socket * sock, int how)
```
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
