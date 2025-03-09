# Function: <code>do_accept</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct file * do_accept(struct file * file, unsigned int file_flags, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "do_accept",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589813232,
      "name": "do_accept",
      "external": true,
      "loc": "net/socket.c:1742",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "net/socket.c:__sys_accept4_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589813232,
      "name": "do_accept",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
struct file * do_accept(struct file * file, unsigned int file_flags, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "do_accept",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591332848,
      "name": "do_accept",
      "external": true,
      "loc": "net/socket.c:1822",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_accept",
        "io_uring/io_uring.c:io_accept",
        "net/socket.c:__sys_accept4_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591332848,
      "name": "do_accept",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
struct file * do_accept(struct file * file, unsigned int file_flags, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "do_accept",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593087888,
      "name": "do_accept",
      "external": true,
      "loc": "net/socket.c:1822",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_accept",
        "io_uring/net.c:io_accept",
        "net/socket.c:__sys_accept4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593087888,
      "name": "do_accept",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
struct file * do_accept(struct file * file, unsigned int file_flags, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "do_accept",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593540016,
      "name": "do_accept",
      "external": true,
      "loc": "net/socket.c:1851",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_accept",
        "io_uring/net.c:io_accept",
        "net/socket.c:__sys_accept4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593540016,
      "name": "do_accept",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
struct file * do_accept(struct file * file, unsigned int file_flags, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```

```json
{
  "name": "do_accept",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594312672,
      "name": "do_accept",
      "external": true,
      "loc": "net/socket.c:1893",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_accept",
        "io_uring/net.c:io_accept",
        "net/socket.c:__sys_accept4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594312672,
      "name": "do_accept",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct file * do_accept(struct file * file, unsigned int file_flags, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags)
```
</details>
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
