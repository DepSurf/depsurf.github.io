# Function: <code>__sys_recvmsg_sock</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket * sock, struct user_msghdr * msg, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588144768,
      "name": "__sys_recvmsg_sock",
      "external": true,
      "loc": "net/socket.c:2515",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588144768,
      "name": "__sys_recvmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
long int __sys_recvmsg_sock(struct socket * sock, struct user_msghdr * umsg, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588349856,
      "name": "__sys_recvmsg_sock",
      "external": true,
      "loc": "net/socket.c:2579",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588349856,
      "name": "__sys_recvmsg_sock",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket * sock, struct msghdr * msg, struct user_msghdr * umsg, struct sockaddr * uaddr, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589211024,
      "name": "__sys_recvmsg_sock",
      "external": true,
      "loc": "net/socket.c:2626",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589211024,
      "name": "__sys_recvmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
long int __sys_recvmsg_sock(struct socket * sock, struct msghdr * msg, struct user_msghdr * umsg, struct sockaddr * uaddr, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589210096,
      "name": "__sys_recvmsg_sock",
      "external": true,
      "loc": "net/socket.c:2619",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_recvmsg",
        "fs/io_uring.c:io_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589210096,
      "name": "__sys_recvmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
long int __sys_recvmsg_sock(struct socket * sock, struct msghdr * msg, struct user_msghdr * umsg, struct sockaddr * uaddr, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589103696,
      "name": "__sys_recvmsg_sock",
      "external": true,
      "loc": "net/socket.c:2609",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589103696,
      "name": "__sys_recvmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
long int __sys_recvmsg_sock(struct socket * sock, struct msghdr * msg, struct user_msghdr * umsg, struct sockaddr * uaddr, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589821344,
      "name": "__sys_recvmsg_sock",
      "external": true,
      "loc": "net/socket.c:2682",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589821344,
      "name": "__sys_recvmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
long int __sys_recvmsg_sock(struct socket * sock, struct msghdr * msg, struct user_msghdr * umsg, struct sockaddr * uaddr, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591342176,
      "name": "__sys_recvmsg_sock",
      "external": true,
      "loc": "net/socket.c:2758",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_recvmsg",
        "io_uring/io_uring.c:io_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591342176,
      "name": "__sys_recvmsg_sock",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket * sock, struct msghdr * msg, struct user_msghdr * umsg, struct sockaddr * uaddr, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593097632,
      "name": "__sys_recvmsg_sock",
      "external": true,
      "loc": "net/socket.c:2746",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593097632,
      "name": "__sys_recvmsg_sock",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket * sock, struct msghdr * msg, struct user_msghdr * umsg, struct sockaddr * uaddr, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593549840,
      "name": "__sys_recvmsg_sock",
      "external": true,
      "loc": "net/socket.c:2784",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593549840,
      "name": "__sys_recvmsg_sock",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket * sock, struct msghdr * msg, struct user_msghdr * umsg, struct sockaddr * uaddr, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594322128,
      "name": "__sys_recvmsg_sock",
      "external": true,
      "loc": "net/socket.c:2854",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594322128,
      "name": "__sys_recvmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
long int __sys_recvmsg_sock(struct socket * sock, struct user_msghdr * umsg, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501856720,
      "name": "__sys_recvmsg_sock",
      "external": true,
      "loc": "net/socket.c:2579",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501856720,
      "name": "__sys_recvmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
long int __sys_recvmsg_sock(struct socket * sock, struct user_msghdr * umsg, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234624312,
      "name": "__sys_recvmsg_sock",
      "external": true,
      "loc": "net/socket.c:2579",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234624312,
      "name": "__sys_recvmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
long int __sys_recvmsg_sock(struct socket * sock, struct user_msghdr * umsg, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295259056,
      "name": "__sys_recvmsg_sock",
      "external": true,
      "loc": "net/socket.c:2579",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295259056,
      "name": "__sys_recvmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
long int __sys_recvmsg_sock(struct socket * sock, struct user_msghdr * umsg, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278184048,
      "name": "__sys_recvmsg_sock",
      "external": true,
      "loc": "net/socket.c:2579",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278184048,
      "name": "__sys_recvmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
long int __sys_recvmsg_sock(struct socket * sock, struct user_msghdr * umsg, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587956640,
      "name": "__sys_recvmsg_sock",
      "external": true,
      "loc": "net/socket.c:2579",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587956640,
      "name": "__sys_recvmsg_sock",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket * sock, struct user_msghdr * umsg, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587669744,
      "name": "__sys_recvmsg_sock",
      "external": true,
      "loc": "net/socket.c:2579",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587669744,
      "name": "__sys_recvmsg_sock",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket * sock, struct user_msghdr * umsg, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588288416,
      "name": "__sys_recvmsg_sock",
      "external": true,
      "loc": "net/socket.c:2579",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588288416,
      "name": "__sys_recvmsg_sock",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket * sock, struct user_msghdr * umsg, unsigned int flags)
```

```json
{
  "name": "__sys_recvmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588423488,
      "name": "__sys_recvmsg_sock",
      "external": true,
      "loc": "net/socket.c:2579",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588423488,
      "name": "__sys_recvmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
long int __sys_recvmsg_sock(struct socket * sock, struct user_msghdr * msg, unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_msghdr * umsg</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_msghdr * msg</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct msghdr * msg</code>
</li>
<li>
<b>Param added. </b>
<code>struct sockaddr * uaddr</code>
</li>
<li>
<b>Param reordered. </b>
<code>sock, umsg, flags</code> ➡️ <code>sock, msg, umsg, uaddr, flags</code>
</li>
</ul>
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
