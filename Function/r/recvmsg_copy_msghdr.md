# Function: <code>recvmsg_copy_msghdr</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "recvmsg_copy_msghdr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588349970,
      "name": "recvmsg_copy_msghdr",
      "external": false,
      "loc": "net/socket.c:2486",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int recvmsg_copy_msghdr(struct msghdr * msg, struct user_msghdr * umsg, unsigned int flags, struct sockaddr * * uaddr, struct iovec * * iov)
```

```json
{
  "name": "recvmsg_copy_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589207813,
      "name": "recvmsg_copy_msghdr",
      "external": true,
      "loc": "net/socket.c:2528",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:___sys_recvmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589210944,
      "name": "recvmsg_copy_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int recvmsg_copy_msghdr(struct msghdr * msg, struct user_msghdr * umsg, unsigned int flags, struct sockaddr * * uaddr, struct iovec * * iov)
```

```json
{
  "name": "recvmsg_copy_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589206949,
      "name": "recvmsg_copy_msghdr",
      "external": true,
      "loc": "net/socket.c:2521",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:___sys_recvmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589210016,
      "name": "recvmsg_copy_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int recvmsg_copy_msghdr(struct msghdr * msg, struct user_msghdr * umsg, unsigned int flags, struct sockaddr * * uaddr, struct iovec * * iov)
```

```json
{
  "name": "recvmsg_copy_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589100585,
      "name": "recvmsg_copy_msghdr",
      "external": true,
      "loc": "net/socket.c:2511",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:___sys_recvmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589103632,
      "name": "recvmsg_copy_msghdr",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int recvmsg_copy_msghdr(struct msghdr * msg, struct user_msghdr * umsg, unsigned int flags, struct sockaddr * * uaddr, struct iovec * * iov)
```

```json
{
  "name": "recvmsg_copy_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589818233,
      "name": "recvmsg_copy_msghdr",
      "external": true,
      "loc": "net/socket.c:2584",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:___sys_recvmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589821280,
      "name": "recvmsg_copy_msghdr",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int recvmsg_copy_msghdr(struct msghdr * msg, struct user_msghdr * umsg, unsigned int flags, struct sockaddr * * uaddr, struct iovec * * iov)
```

```json
{
  "name": "recvmsg_copy_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591338506,
      "name": "recvmsg_copy_msghdr",
      "external": true,
      "loc": "net/socket.c:2660",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:___sys_recvmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591342080,
      "name": "recvmsg_copy_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int recvmsg_copy_msghdr(struct msghdr * msg, struct user_msghdr * umsg, unsigned int flags, struct sockaddr * * uaddr, struct iovec * * iov)
```

```json
{
  "name": "recvmsg_copy_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593093897,
      "name": "recvmsg_copy_msghdr",
      "external": true,
      "loc": "net/socket.c:2648",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:___sys_recvmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593097520,
      "name": "recvmsg_copy_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int recvmsg_copy_msghdr(struct msghdr * msg, struct user_msghdr * umsg, unsigned int flags, struct sockaddr * * uaddr, struct iovec * * iov)
```

```json
{
  "name": "recvmsg_copy_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593546105,
      "name": "recvmsg_copy_msghdr",
      "external": true,
      "loc": "net/socket.c:2686",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:___sys_recvmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593549728,
      "name": "recvmsg_copy_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int recvmsg_copy_msghdr(struct msghdr * msg, struct user_msghdr * umsg, unsigned int flags, struct sockaddr * * uaddr, struct iovec * * iov)
```

```json
{
  "name": "recvmsg_copy_msghdr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594318393,
      "name": "recvmsg_copy_msghdr",
      "external": true,
      "loc": "net/socket.c:2756",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:___sys_recvmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594322016,
      "name": "recvmsg_copy_msghdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "recvmsg_copy_msghdr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501856796,
      "name": "recvmsg_copy_msghdr",
      "external": false,
      "loc": "net/socket.c:2486",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "recvmsg_copy_msghdr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234624416,
      "name": "recvmsg_copy_msghdr",
      "external": false,
      "loc": "net/socket.c:2486",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "recvmsg_copy_msghdr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295259188,
      "name": "recvmsg_copy_msghdr",
      "external": false,
      "loc": "net/socket.c:2486",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "recvmsg_copy_msghdr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278184088,
      "name": "recvmsg_copy_msghdr",
      "external": false,
      "loc": "net/socket.c:2486",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "recvmsg_copy_msghdr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587956754,
      "name": "recvmsg_copy_msghdr",
      "external": false,
      "loc": "net/socket.c:2486",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "recvmsg_copy_msghdr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587669858,
      "name": "recvmsg_copy_msghdr",
      "external": false,
      "loc": "net/socket.c:2486",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "recvmsg_copy_msghdr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588288530,
      "name": "recvmsg_copy_msghdr",
      "external": false,
      "loc": "net/socket.c:2486",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "recvmsg_copy_msghdr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588423602,
      "name": "recvmsg_copy_msghdr",
      "external": false,
      "loc": "net/socket.c:2486",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int recvmsg_copy_msghdr(struct msghdr * msg, struct user_msghdr * umsg, unsigned int flags, struct sockaddr * * uaddr, struct iovec * * iov)
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
