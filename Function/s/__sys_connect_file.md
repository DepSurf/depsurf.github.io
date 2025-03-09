# Function: <code>__sys_connect_file</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __sys_connect_file(struct file * file, struct __kernel_sockaddr_storage * address, int addrlen, int file_flags)
```

```json
{
  "name": "__sys_connect_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589204832,
      "name": "__sys_connect_file",
      "external": true,
      "loc": "net/socket.c:1839",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_connect",
        "fs/io_uring.c:io_connect",
        "net/socket.c:__sys_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589204832,
      "name": "__sys_connect_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int __sys_connect_file(struct file * file, struct __kernel_sockaddr_storage * address, int addrlen, int file_flags)
```

```json
{
  "name": "__sys_connect_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589202864,
      "name": "__sys_connect_file",
      "external": true,
      "loc": "net/socket.c:1818",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_connect",
        "fs/io_uring.c:io_connect",
        "net/socket.c:__sys_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589202864,
      "name": "__sys_connect_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int __sys_connect_file(struct file * file, struct __kernel_sockaddr_storage * address, int addrlen, int file_flags)
```

```json
{
  "name": "__sys_connect_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589096432,
      "name": "__sys_connect_file",
      "external": true,
      "loc": "net/socket.c:1809",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_connect",
        "fs/io_uring.c:io_connect",
        "net/socket.c:__sys_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589096432,
      "name": "__sys_connect_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int __sys_connect_file(struct file * file, struct __kernel_sockaddr_storage * address, int addrlen, int file_flags)
```

```json
{
  "name": "__sys_connect_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589814080,
      "name": "__sys_connect_file",
      "external": true,
      "loc": "net/socket.c:1882",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_connect",
        "fs/io_uring.c:io_connect",
        "net/socket.c:__sys_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589814080,
      "name": "__sys_connect_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int __sys_connect_file(struct file * file, struct __kernel_sockaddr_storage * address, int addrlen, int file_flags)
```

```json
{
  "name": "__sys_connect_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591333840,
      "name": "__sys_connect_file",
      "external": true,
      "loc": "net/socket.c:1962",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_connect",
        "net/socket.c:__sys_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591333840,
      "name": "__sys_connect_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int __sys_connect_file(struct file * file, struct __kernel_sockaddr_storage * address, int addrlen, int file_flags)
```

```json
{
  "name": "__sys_connect_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593088832,
      "name": "__sys_connect_file",
      "external": true,
      "loc": "net/socket.c:1959",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_connect",
        "net/socket.c:__sys_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593088832,
      "name": "__sys_connect_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int __sys_connect_file(struct file * file, struct __kernel_sockaddr_storage * address, int addrlen, int file_flags)
```

```json
{
  "name": "__sys_connect_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593540976,
      "name": "__sys_connect_file",
      "external": true,
      "loc": "net/socket.c:1989",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_connect",
        "net/socket.c:__sys_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593540976,
      "name": "__sys_connect_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int __sys_connect_file(struct file * file, struct __kernel_sockaddr_storage * address, int addrlen, int file_flags)
```

```json
{
  "name": "__sys_connect_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594313632,
      "name": "__sys_connect_file",
      "external": true,
      "loc": "net/socket.c:2031",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_connect",
        "net/socket.c:__sys_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594313632,
      "name": "__sys_connect_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int __sys_connect_file(struct file * file, struct __kernel_sockaddr_storage * address, int addrlen, int file_flags)
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
