# Function: <code>__copy_msghdr_from_user</code>

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
int __copy_msghdr_from_user(struct msghdr * kmsg, struct user_msghdr * umsg, struct sockaddr * * save_addr, struct iovec * * uiov, size_t * nsegs)
```

```json
{
  "name": "__copy_msghdr_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589207264,
      "name": "__copy_msghdr_from_user",
      "external": true,
      "loc": "net/socket.c:2226",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_recvmsg_copy_hdr",
        "net/socket.c:___sys_recvmsg",
        "net/socket.c:sendmsg_copy_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589207264,
      "name": "__copy_msghdr_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int __copy_msghdr_from_user(struct msghdr * kmsg, struct user_msghdr * umsg, struct sockaddr * * save_addr, struct iovec * * uiov, size_t * nsegs)
```

```json
{
  "name": "__copy_msghdr_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589206400,
      "name": "__copy_msghdr_from_user",
      "external": true,
      "loc": "net/socket.c:2219",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_recvmsg_copy_hdr",
        "net/socket.c:___sys_recvmsg",
        "net/socket.c:sendmsg_copy_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589206400,
      "name": "__copy_msghdr_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int __copy_msghdr_from_user(struct msghdr * kmsg, struct user_msghdr * umsg, struct sockaddr * * save_addr, struct iovec * * uiov, size_t * nsegs)
```

```json
{
  "name": "__copy_msghdr_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589100064,
      "name": "__copy_msghdr_from_user",
      "external": true,
      "loc": "net/socket.c:2213",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_recvmsg_copy_hdr",
        "net/socket.c:___sys_recvmsg",
        "net/socket.c:sendmsg_copy_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589100064,
      "name": "__copy_msghdr_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int __copy_msghdr_from_user(struct msghdr * kmsg, struct user_msghdr * umsg, struct sockaddr * * save_addr, struct iovec * * uiov, size_t * nsegs)
```

```json
{
  "name": "__copy_msghdr_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589817712,
      "name": "__copy_msghdr_from_user",
      "external": true,
      "loc": "net/socket.c:2286",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_recvmsg_copy_hdr",
        "net/socket.c:___sys_recvmsg",
        "net/socket.c:sendmsg_copy_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589817712,
      "name": "__copy_msghdr_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int __copy_msghdr_from_user(struct msghdr * kmsg, struct user_msghdr * umsg, struct sockaddr * * save_addr, struct iovec * * uiov, size_t * nsegs)
```

```json
{
  "name": "__copy_msghdr_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591337872,
      "name": "__copy_msghdr_from_user",
      "external": true,
      "loc": "net/socket.c:2361",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__io_recvmsg_copy_hdr",
        "net/socket.c:___sys_recvmsg",
        "net/socket.c:sendmsg_copy_msghdr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591337872,
      "name": "__copy_msghdr_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
    }
  ]
}
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __copy_msghdr_from_user(struct msghdr * kmsg, struct user_msghdr * umsg, struct sockaddr * * save_addr, struct iovec * * uiov, size_t * nsegs)
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
int __copy_msghdr_from_user(struct msghdr * kmsg, struct user_msghdr * umsg, struct sockaddr * * save_addr, struct iovec * * uiov, size_t * nsegs)
```
</details>
</li>
</ul>
