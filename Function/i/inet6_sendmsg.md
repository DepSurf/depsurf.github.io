# Function: <code>inet6_sendmsg</code>

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
int inet6_sendmsg(struct socket * sock, struct msghdr * msg, size_t size)
```

```json
{
  "name": "inet6_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589323952,
      "name": "inet6_sendmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:569",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:___sys_sendmsg",
        "net/socket.c:sock_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589323952,
      "name": "inet6_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int inet6_sendmsg(struct socket * sock, struct msghdr * msg, size_t size)
```

```json
{
  "name": "inet6_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589548192,
      "name": "inet6_sendmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:569",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/socket.c:sock_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589548192,
      "name": "inet6_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int inet6_sendmsg(struct socket * sock, struct msghdr * msg, size_t size)
```

```json
{
  "name": "inet6_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590551616,
      "name": "inet6_sendmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:631",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/socket.c:sock_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590551616,
      "name": "inet6_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int inet6_sendmsg(struct socket * sock, struct msghdr * msg, size_t size)
```

```json
{
  "name": "inet6_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590611328,
      "name": "inet6_sendmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:631",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/socket.c:sock_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590611328,
      "name": "inet6_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int inet6_sendmsg(struct socket * sock, struct msghdr * msg, size_t size)
```

```json
{
  "name": "inet6_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590536816,
      "name": "inet6_sendmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:635",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/socket.c:sock_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590536816,
      "name": "inet6_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int inet6_sendmsg(struct socket * sock, struct msghdr * msg, size_t size)
```

```json
{
  "name": "inet6_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591346384,
      "name": "inet6_sendmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:637",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/socket.c:sock_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591346384,
      "name": "inet6_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int inet6_sendmsg(struct socket * sock, struct msghdr * msg, size_t size)
```

```json
{
  "name": "inet6_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593018864,
      "name": "inet6_sendmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:643",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/socket.c:sock_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593018864,
      "name": "inet6_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int inet6_sendmsg(struct socket * sock, struct msghdr * msg, size_t size)
```

```json
{
  "name": "inet6_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594909440,
      "name": "inet6_sendmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:651",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/socket.c:sock_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594909440,
      "name": "inet6_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int inet6_sendmsg(struct socket * sock, struct msghdr * msg, size_t size)
```

```json
{
  "name": "inet6_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595301136,
      "name": "inet6_sendmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:641",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/socket.c:sock_write_iter",
        "net/socket.c:kernel_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595301136,
      "name": "inet6_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int inet6_sendmsg(struct socket * sock, struct msghdr * msg, size_t size)
```

```json
{
  "name": "inet6_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596142640,
      "name": "inet6_sendmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:650",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/socket.c:____sys_sendmsg",
        "net/socket.c:__sys_sendto",
        "net/socket.c:sock_write_iter",
        "net/socket.c:sock_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596142640,
      "name": "inet6_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int inet6_sendmsg(struct socket * sock, struct msghdr * msg, size_t size)
```

```json
{
  "name": "inet6_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503221048,
      "name": "inet6_sendmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:569",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503221048,
      "name": "inet6_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int inet6_sendmsg(struct socket * sock, struct msghdr * msg, size_t size)
```

```json
{
  "name": "inet6_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235890476,
      "name": "inet6_sendmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:569",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235890476,
      "name": "inet6_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int inet6_sendmsg(struct socket * sock, struct msghdr * msg, size_t size)
```

```json
{
  "name": "inet6_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296958304,
      "name": "inet6_sendmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:569",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296958304,
      "name": "inet6_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int inet6_sendmsg(struct socket * sock, struct msghdr * msg, size_t size)
```

```json
{
  "name": "inet6_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279254366,
      "name": "inet6_sendmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:569",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279254366,
      "name": "inet6_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int inet6_sendmsg(struct socket * sock, struct msghdr * msg, size_t size)
```

```json
{
  "name": "inet6_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589152560,
      "name": "inet6_sendmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:569",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/socket.c:sock_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589152560,
      "name": "inet6_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int inet6_sendmsg(struct socket * sock, struct msghdr * msg, size_t size)
```

```json
{
  "name": "inet6_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588877552,
      "name": "inet6_sendmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:569",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/socket.c:sock_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588877552,
      "name": "inet6_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int inet6_sendmsg(struct socket * sock, struct msghdr * msg, size_t size)
```

```json
{
  "name": "inet6_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589589424,
      "name": "inet6_sendmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:569",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/socket.c:sock_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589589424,
      "name": "inet6_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int inet6_sendmsg(struct socket * sock, struct msghdr * msg, size_t size)
```

```json
{
  "name": "inet6_sendmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589637232,
      "name": "inet6_sendmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:569",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_sendmsg",
        "net/socket.c:sock_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589637232,
      "name": "inet6_sendmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int inet6_sendmsg(struct socket * sock, struct msghdr * msg, size_t size)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
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
