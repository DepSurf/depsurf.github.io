# Function: <code>__sys_accept4_file</code>

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
int __sys_accept4_file(struct file * file, unsigned int file_flags, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags, long unsigned int nofile)
```

```json
{
  "name": "__sys_accept4_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589204016,
      "name": "__sys_accept4_file",
      "external": true,
      "loc": "net/socket.c:1703",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "net/socket.c:__sys_accept4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589204016,
      "name": "__sys_accept4_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
int __sys_accept4_file(struct file * file, unsigned int file_flags, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags, long unsigned int nofile)
```

```json
{
  "name": "__sys_accept4_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589202048,
      "name": "__sys_accept4_file",
      "external": true,
      "loc": "net/socket.c:1681",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "net/socket.c:__sys_accept4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589202048,
      "name": "__sys_accept4_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
int __sys_accept4_file(struct file * file, unsigned int file_flags, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags, long unsigned int nofile)
```

```json
{
  "name": "__sys_accept4_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589095632,
      "name": "__sys_accept4_file",
      "external": true,
      "loc": "net/socket.c:1672",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_issue_sqe",
        "net/socket.c:__sys_accept4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589095632,
      "name": "__sys_accept4_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
int __sys_accept4_file(struct file * file, unsigned int file_flags, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags, long unsigned int nofile)
```

```json
{
  "name": "__sys_accept4_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589813632,
      "name": "__sys_accept4_file",
      "external": true,
      "loc": "net/socket.c:1801",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589813632,
      "name": "__sys_accept4_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int __sys_accept4_file(struct file * file, unsigned int file_flags, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags, long unsigned int nofile)
```

```json
{
  "name": "__sys_accept4_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591333280,
      "name": "__sys_accept4_file",
      "external": true,
      "loc": "net/socket.c:1881",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_accept4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591333280,
      "name": "__sys_accept4_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sys_accept4_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593088393,
      "name": "__sys_accept4_file",
      "external": false,
      "loc": "net/socket.c:1881",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_accept4"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sys_accept4_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593540537,
      "name": "__sys_accept4_file",
      "external": false,
      "loc": "net/socket.c:1911",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_accept4"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sys_accept4_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594313193,
      "name": "__sys_accept4_file",
      "external": false,
      "loc": "net/socket.c:1953",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_accept4"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int __sys_accept4_file(struct file * file, unsigned int file_flags, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags, long unsigned int nofile)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int __sys_accept4_file(struct file * file, unsigned int file_flags, struct sockaddr * upeer_sockaddr, int * upeer_addrlen, int flags, long unsigned int nofile)
```
</details>
</li>
</ul>
