# Function: <code>__get_unused_fd_flags</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __get_unused_fd_flags(unsigned int flags, long unsigned int nofile)
```

```json
{
  "name": "__get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582227389,
      "name": "__get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:543",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:ksys_dup"
      ],
      "caller_func": [
        "fs/io_uring.c:io_openat2",
        "net/socket.c:__sys_accept4_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226176,
      "name": "__get_unused_fd_flags",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __get_unused_fd_flags(unsigned int flags, long unsigned int nofile)
```

```json
{
  "name": "__get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582272733,
      "name": "__get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:528",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:__receive_fd"
      ],
      "caller_func": [
        "fs/io_uring.c:io_openat2",
        "net/socket.c:__sys_accept4_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582273904,
      "name": "__get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int __get_unused_fd_flags(unsigned int flags, long unsigned int nofile)
```

```json
{
  "name": "__get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582297760,
      "name": "__get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:528",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:__receive_fd"
      ],
      "caller_func": [
        "fs/io_uring.c:io_openat2",
        "net/socket.c:__sys_accept4_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582299376,
      "name": "__get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int __get_unused_fd_flags(unsigned int flags, long unsigned int nofile)
```

```json
{
  "name": "__get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582616576,
      "name": "__get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:528",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:receive_fd"
      ],
      "caller_func": [
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_openat2",
        "net/socket.c:__sys_accept4_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582618448,
      "name": "__get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int __get_unused_fd_flags(unsigned int flags, long unsigned int nofile)
```

```json
{
  "name": "__get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583151182,
      "name": "__get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:557",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:receive_fd"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_socket",
        "io_uring/io_uring.c:io_accept",
        "io_uring/io_uring.c:io_openat2",
        "net/socket.c:__sys_accept4_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583153344,
      "name": "__get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int __get_unused_fd_flags(unsigned int flags, long unsigned int nofile)
```

```json
{
  "name": "__get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583724814,
      "name": "__get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:557",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:receive_fd"
      ],
      "caller_func": [
        "io_uring/openclose.c:io_openat2",
        "io_uring/net.c:io_socket",
        "io_uring/net.c:io_accept"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583727152,
      "name": "__get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int __get_unused_fd_flags(unsigned int flags, long unsigned int nofile)
```

```json
{
  "name": "__get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583941870,
      "name": "__get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:557",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup",
        "fs/file.c:receive_fd"
      ],
      "caller_func": [
        "io_uring/openclose.c:io_openat2",
        "io_uring/net.c:io_socket",
        "io_uring/net.c:io_accept"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583944208,
      "name": "__get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int __get_unused_fd_flags(unsigned int flags, long unsigned int nofile)
```

```json
{
  "name": "__get_unused_fd_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584149030,
      "name": "__get_unused_fd_flags",
      "external": true,
      "loc": "fs/file.c:557",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:__ia32_sys_dup",
        "fs/file.c:__x64_sys_dup"
      ],
      "caller_func": [
        "io_uring/openclose.c:io_openat2",
        "io_uring/net.c:io_socket",
        "io_uring/net.c:io_accept"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584150992,
      "name": "__get_unused_fd_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __get_unused_fd_flags(unsigned int flags, long unsigned int nofile)
```
</details>
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
