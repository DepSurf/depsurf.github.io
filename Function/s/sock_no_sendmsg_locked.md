# Function: <code>sock_no_sendmsg_locked</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:2540",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587415472,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:2615",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587719056,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:2559",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587852320,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588148208,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:2702",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588148208,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588353472,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:2717",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588353472,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:2825",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589218784,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:2803",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589216768,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:2826",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589110416,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:2957",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589828656,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:3120",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591350720,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:3200",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593104480,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:3261",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked",
        "net/core/skbuff.c:sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593555840,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:3271",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked",
        "net/core/skbuff.c:sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594328272,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:2717",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501864640,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:2717",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234633608,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295262720,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:2717",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295262720,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:2717",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278193390,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587960256,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:2717",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587960256,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587673360,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:2717",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587673360,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588292032,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:2717",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588292032,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```

```json
{
  "name": "sock_no_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588427104,
      "name": "sock_no_sendmsg_locked",
      "external": true,
      "loc": "net/core/sock.c:2717",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588427104,
      "name": "sock_no_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int sock_no_sendmsg_locked(struct sock * sk, struct msghdr * m, size_t len)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
