# Function: <code>inet6_recvmsg</code>

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
int inet6_recvmsg(struct socket * sock, struct msghdr * msg, size_t size, int flags)
```

```json
{
  "name": "inet6_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589324064,
      "name": "inet6_recvmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:582",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589324064,
      "name": "inet6_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int inet6_recvmsg(struct socket * sock, struct msghdr * msg, size_t size, int flags)
```

```json
{
  "name": "inet6_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589548304,
      "name": "inet6_recvmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:582",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589548304,
      "name": "inet6_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int inet6_recvmsg(struct socket * sock, struct msghdr * msg, size_t size, int flags)
```

```json
{
  "name": "inet6_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590551728,
      "name": "inet6_recvmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:644",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_recvmsg",
        "net/socket.c:sock_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590551728,
      "name": "inet6_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
int inet6_recvmsg(struct socket * sock, struct msghdr * msg, size_t size, int flags)
```

```json
{
  "name": "inet6_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590611440,
      "name": "inet6_recvmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:644",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_recvmsg",
        "net/socket.c:sock_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590611440,
      "name": "inet6_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int inet6_recvmsg(struct socket * sock, struct msghdr * msg, size_t size, int flags)
```

```json
{
  "name": "inet6_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590536928,
      "name": "inet6_recvmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:648",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_recvmsg",
        "net/socket.c:sock_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590536928,
      "name": "inet6_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int inet6_recvmsg(struct socket * sock, struct msghdr * msg, size_t size, int flags)
```

```json
{
  "name": "inet6_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591346496,
      "name": "inet6_recvmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:650",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_recvmsg",
        "net/socket.c:sock_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591346496,
      "name": "inet6_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int inet6_recvmsg(struct socket * sock, struct msghdr * msg, size_t size, int flags)
```

```json
{
  "name": "inet6_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593018992,
      "name": "inet6_recvmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:659",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_recvmsg",
        "net/socket.c:sock_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593018992,
      "name": "inet6_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int inet6_recvmsg(struct socket * sock, struct msghdr * msg, size_t size, int flags)
```

```json
{
  "name": "inet6_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594909584,
      "name": "inet6_recvmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:667",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_recvmsg",
        "net/socket.c:sock_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594909584,
      "name": "inet6_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int inet6_recvmsg(struct socket * sock, struct msghdr * msg, size_t size, int flags)
```

```json
{
  "name": "inet6_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595301280,
      "name": "inet6_recvmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:657",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595301280,
      "name": "inet6_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int inet6_recvmsg(struct socket * sock, struct msghdr * msg, size_t size, int flags)
```

```json
{
  "name": "inet6_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596142784,
      "name": "inet6_recvmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:666",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:____sys_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596142784,
      "name": "inet6_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int inet6_recvmsg(struct socket * sock, struct msghdr * msg, size_t size, int flags)
```

```json
{
  "name": "inet6_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503220144,
      "name": "inet6_recvmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:582",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503220144,
      "name": "inet6_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int inet6_recvmsg(struct socket * sock, struct msghdr * msg, size_t size, int flags)
```

```json
{
  "name": "inet6_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235889648,
      "name": "inet6_recvmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:582",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235889648,
      "name": "inet6_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int inet6_recvmsg(struct socket * sock, struct msghdr * msg, size_t size, int flags)
```

```json
{
  "name": "inet6_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296956816,
      "name": "inet6_recvmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:582",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296956816,
      "name": "inet6_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int inet6_recvmsg(struct socket * sock, struct msghdr * msg, size_t size, int flags)
```

```json
{
  "name": "inet6_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279253414,
      "name": "inet6_recvmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:582",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279253414,
      "name": "inet6_recvmsg",
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
int inet6_recvmsg(struct socket * sock, struct msghdr * msg, size_t size, int flags)
```

```json
{
  "name": "inet6_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589152672,
      "name": "inet6_recvmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:582",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589152672,
      "name": "inet6_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int inet6_recvmsg(struct socket * sock, struct msghdr * msg, size_t size, int flags)
```

```json
{
  "name": "inet6_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588877664,
      "name": "inet6_recvmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:582",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588877664,
      "name": "inet6_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int inet6_recvmsg(struct socket * sock, struct msghdr * msg, size_t size, int flags)
```

```json
{
  "name": "inet6_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589589536,
      "name": "inet6_recvmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:582",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589589536,
      "name": "inet6_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int inet6_recvmsg(struct socket * sock, struct msghdr * msg, size_t size, int flags)
```

```json
{
  "name": "inet6_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589637344,
      "name": "inet6_recvmsg",
      "external": true,
      "loc": "net/ipv6/af_inet6.c:582",
      "file": "net/ipv6/af_inet6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589637344,
      "name": "inet6_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
int inet6_recvmsg(struct socket * sock, struct msghdr * msg, size_t size, int flags)
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
