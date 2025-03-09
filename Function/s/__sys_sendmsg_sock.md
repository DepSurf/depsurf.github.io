# Function: <code>__sys_sendmsg_sock</code>

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
long int __sys_sendmsg_sock(struct socket * sock, struct user_msghdr * msg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588143840,
      "name": "__sys_sendmsg_sock",
      "external": true,
      "loc": "net/socket.c:2334",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588143840,
      "name": "__sys_sendmsg_sock",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long int __sys_sendmsg_sock(struct socket * sock, struct user_msghdr * umsg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588348736,
      "name": "__sys_sendmsg_sock",
      "external": true,
      "loc": "net/socket.c:2360",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588348736,
      "name": "__sys_sendmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
long int __sys_sendmsg_sock(struct socket * sock, struct msghdr * msg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589210000,
      "name": "__sys_sendmsg_sock",
      "external": true,
      "loc": "net/socket.c:2415",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sendmsg",
        "fs/io_uring.c:io_sendmsg",
        "fs/io_uring.c:io_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589210000,
      "name": "__sys_sendmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
long int __sys_sendmsg_sock(struct socket * sock, struct msghdr * msg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589209104,
      "name": "__sys_sendmsg_sock",
      "external": true,
      "loc": "net/socket.c:2408",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sendmsg",
        "fs/io_uring.c:io_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589209104,
      "name": "__sys_sendmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
long int __sys_sendmsg_sock(struct socket * sock, struct msghdr * msg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589102752,
      "name": "__sys_sendmsg_sock",
      "external": true,
      "loc": "net/socket.c:2402",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sendmsg",
        "fs/io_uring.c:io_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589102752,
      "name": "__sys_sendmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
long int __sys_sendmsg_sock(struct socket * sock, struct msghdr * msg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589820400,
      "name": "__sys_sendmsg_sock",
      "external": true,
      "loc": "net/socket.c:2475",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_sendmsg",
        "fs/io_uring.c:io_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589820400,
      "name": "__sys_sendmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
long int __sys_sendmsg_sock(struct socket * sock, struct msghdr * msg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591340976,
      "name": "__sys_sendmsg_sock",
      "external": true,
      "loc": "net/socket.c:2551",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591340976,
      "name": "__sys_sendmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long int __sys_sendmsg_sock(struct socket * sock, struct msghdr * msg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593096304,
      "name": "__sys_sendmsg_sock",
      "external": true,
      "loc": "net/socket.c:2539",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_sendmsg_zc",
        "io_uring/net.c:io_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593096304,
      "name": "__sys_sendmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long int __sys_sendmsg_sock(struct socket * sock, struct msghdr * msg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593548512,
      "name": "__sys_sendmsg_sock",
      "external": true,
      "loc": "net/socket.c:2577",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_sendmsg_zc",
        "io_uring/net.c:io_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593548512,
      "name": "__sys_sendmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long int __sys_sendmsg_sock(struct socket * sock, struct msghdr * msg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594320800,
      "name": "__sys_sendmsg_sock",
      "external": true,
      "loc": "net/socket.c:2647",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_sendmsg_zc",
        "io_uring/net.c:io_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594320800,
      "name": "__sys_sendmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long int __sys_sendmsg_sock(struct socket * sock, struct user_msghdr * umsg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501855128,
      "name": "__sys_sendmsg_sock",
      "external": true,
      "loc": "net/socket.c:2360",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501855128,
      "name": "__sys_sendmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
long int __sys_sendmsg_sock(struct socket * sock, struct user_msghdr * umsg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234623444,
      "name": "__sys_sendmsg_sock",
      "external": true,
      "loc": "net/socket.c:2360",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234623444,
      "name": "__sys_sendmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
long int __sys_sendmsg_sock(struct socket * sock, struct user_msghdr * umsg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295257424,
      "name": "__sys_sendmsg_sock",
      "external": true,
      "loc": "net/socket.c:2360",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295257424,
      "name": "__sys_sendmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
long int __sys_sendmsg_sock(struct socket * sock, struct user_msghdr * umsg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278183288,
      "name": "__sys_sendmsg_sock",
      "external": true,
      "loc": "net/socket.c:2360",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278183288,
      "name": "__sys_sendmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
long int __sys_sendmsg_sock(struct socket * sock, struct user_msghdr * umsg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587955520,
      "name": "__sys_sendmsg_sock",
      "external": true,
      "loc": "net/socket.c:2360",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587955520,
      "name": "__sys_sendmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
long int __sys_sendmsg_sock(struct socket * sock, struct user_msghdr * umsg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587668624,
      "name": "__sys_sendmsg_sock",
      "external": true,
      "loc": "net/socket.c:2360",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587668624,
      "name": "__sys_sendmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
long int __sys_sendmsg_sock(struct socket * sock, struct user_msghdr * umsg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588287296,
      "name": "__sys_sendmsg_sock",
      "external": true,
      "loc": "net/socket.c:2360",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588287296,
      "name": "__sys_sendmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
long int __sys_sendmsg_sock(struct socket * sock, struct user_msghdr * umsg, unsigned int flags)
```

```json
{
  "name": "__sys_sendmsg_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588422448,
      "name": "__sys_sendmsg_sock",
      "external": true,
      "loc": "net/socket.c:2360",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588422448,
      "name": "__sys_sendmsg_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
long int __sys_sendmsg_sock(struct socket * sock, struct user_msghdr * msg, unsigned int flags)
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
<b>Param removed. </b>
<code>struct user_msghdr * umsg</code>
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
