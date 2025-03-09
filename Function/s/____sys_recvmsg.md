# Function: <code>____sys_recvmsg</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int ____sys_recvmsg(struct socket * sock, struct msghdr * msg_sys, struct user_msghdr * msg, struct sockaddr * uaddr, unsigned int flags, int nosec)
```

```json
{
  "name": "____sys_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588332384,
      "name": "____sys_recvmsg",
      "external": false,
      "loc": "net/socket.c:2507",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588332384,
      "name": "____sys_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int ____sys_recvmsg(struct socket * sock, struct msghdr * msg_sys, struct user_msghdr * msg, struct sockaddr * uaddr, unsigned int flags, int nosec)
```

```json
{
  "name": "____sys_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589197760,
      "name": "____sys_recvmsg",
      "external": false,
      "loc": "net/socket.c:2549",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589197760,
      "name": "____sys_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
int ____sys_recvmsg(struct socket * sock, struct msghdr * msg_sys, struct user_msghdr * msg, struct sockaddr * uaddr, unsigned int flags, int nosec)
```

```json
{
  "name": "____sys_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589195728,
      "name": "____sys_recvmsg",
      "external": false,
      "loc": "net/socket.c:2542",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589195728,
      "name": "____sys_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
int ____sys_recvmsg(struct socket * sock, struct msghdr * msg_sys, struct user_msghdr * msg, struct sockaddr * uaddr, unsigned int flags, int nosec)
```

```json
{
  "name": "____sys_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589088992,
      "name": "____sys_recvmsg",
      "external": false,
      "loc": "net/socket.c:2532",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589088992,
      "name": "____sys_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
int ____sys_recvmsg(struct socket * sock, struct msghdr * msg_sys, struct user_msghdr * msg, struct sockaddr * uaddr, unsigned int flags, int nosec)
```

```json
{
  "name": "____sys_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589807120,
      "name": "____sys_recvmsg",
      "external": false,
      "loc": "net/socket.c:2605",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589807120,
      "name": "____sys_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
int ____sys_recvmsg(struct socket * sock, struct msghdr * msg_sys, struct user_msghdr * msg, struct sockaddr * uaddr, unsigned int flags, int nosec)
```

```json
{
  "name": "____sys_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591326080,
      "name": "____sys_recvmsg",
      "external": false,
      "loc": "net/socket.c:2681",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591326080,
      "name": "____sys_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int ____sys_recvmsg(struct socket * sock, struct msghdr * msg_sys, struct user_msghdr * msg, struct sockaddr * uaddr, unsigned int flags, int nosec)
```

```json
{
  "name": "____sys_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593079344,
      "name": "____sys_recvmsg",
      "external": false,
      "loc": "net/socket.c:2669",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593079344,
      "name": "____sys_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int ____sys_recvmsg(struct socket * sock, struct msghdr * msg_sys, struct user_msghdr * msg, struct sockaddr * uaddr, unsigned int flags, int nosec)
```

```json
{
  "name": "____sys_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593532768,
      "name": "____sys_recvmsg",
      "external": false,
      "loc": "net/socket.c:2707",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593532768,
      "name": "____sys_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int ____sys_recvmsg(struct socket * sock, struct msghdr * msg_sys, struct user_msghdr * msg, struct sockaddr * uaddr, unsigned int flags, int nosec)
```

```json
{
  "name": "____sys_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594305312,
      "name": "____sys_recvmsg",
      "external": false,
      "loc": "net/socket.c:2777",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594305312,
      "name": "____sys_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int ____sys_recvmsg(struct socket * sock, struct msghdr * msg_sys, struct user_msghdr * msg, struct sockaddr * uaddr, unsigned int flags, int nosec)
```

```json
{
  "name": "____sys_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501839720,
      "name": "____sys_recvmsg",
      "external": false,
      "loc": "net/socket.c:2507",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501839720,
      "name": "____sys_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
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
int ____sys_recvmsg(struct socket * sock, struct msghdr * msg_sys, struct user_msghdr * msg, struct sockaddr * uaddr, unsigned int flags, int nosec)
```

```json
{
  "name": "____sys_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234614212,
      "name": "____sys_recvmsg",
      "external": false,
      "loc": "net/socket.c:2507",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234614212,
      "name": "____sys_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int ____sys_recvmsg(struct socket * sock, struct msghdr * msg_sys, struct user_msghdr * msg, struct sockaddr * uaddr, unsigned int flags, int nosec)
```

```json
{
  "name": "____sys_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295238128,
      "name": "____sys_recvmsg",
      "external": false,
      "loc": "net/socket.c:2507",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295238128,
      "name": "____sys_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
int ____sys_recvmsg(struct socket * sock, struct msghdr * msg_sys, struct user_msghdr * msg, struct sockaddr * uaddr, unsigned int flags, int nosec)
```

```json
{
  "name": "____sys_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278172824,
      "name": "____sys_recvmsg",
      "external": false,
      "loc": "net/socket.c:2507",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278172824,
      "name": "____sys_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int ____sys_recvmsg(struct socket * sock, struct msghdr * msg_sys, struct user_msghdr * msg, struct sockaddr * uaddr, unsigned int flags, int nosec)
```

```json
{
  "name": "____sys_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587939168,
      "name": "____sys_recvmsg",
      "external": false,
      "loc": "net/socket.c:2507",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587939168,
      "name": "____sys_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int ____sys_recvmsg(struct socket * sock, struct msghdr * msg_sys, struct user_msghdr * msg, struct sockaddr * uaddr, unsigned int flags, int nosec)
```

```json
{
  "name": "____sys_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587652272,
      "name": "____sys_recvmsg",
      "external": false,
      "loc": "net/socket.c:2507",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587652272,
      "name": "____sys_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int ____sys_recvmsg(struct socket * sock, struct msghdr * msg_sys, struct user_msghdr * msg, struct sockaddr * uaddr, unsigned int flags, int nosec)
```

```json
{
  "name": "____sys_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588270944,
      "name": "____sys_recvmsg",
      "external": false,
      "loc": "net/socket.c:2507",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588270944,
      "name": "____sys_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int ____sys_recvmsg(struct socket * sock, struct msghdr * msg_sys, struct user_msghdr * msg, struct sockaddr * uaddr, unsigned int flags, int nosec)
```

```json
{
  "name": "____sys_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588406224,
      "name": "____sys_recvmsg",
      "external": false,
      "loc": "net/socket.c:2507",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmsg_sock",
        "net/socket.c:___sys_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588406224,
      "name": "____sys_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int ____sys_recvmsg(struct socket * sock, struct msghdr * msg_sys, struct user_msghdr * msg, struct sockaddr * uaddr, unsigned int flags, int nosec)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
