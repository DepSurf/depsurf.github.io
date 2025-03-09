# Function: <code>sock_recvmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sock_recvmsg(struct socket * sock, struct msghdr * msg, size_t size, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586175792,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:716",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:SYSC_recvfrom"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586175792,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586596448,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:714",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SYSC_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586596448,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586780896,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:745",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SYSC_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586780896,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586898688,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:795",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SYSC_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586898688,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587390416,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:814",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SYSC_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587390416,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587694864,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:818",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587694864,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587828768,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:798",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587828768,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588135216,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:885",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588135216,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588343056,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:885",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588343056,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589197328,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:900",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_recv",
        "fs/io_uring.c:io_recv",
        "fs/io_uring.c:io_recv",
        "net/socket.c:____sys_recvmsg",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589197328,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589195296,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:900",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_recv",
        "fs/io_uring.c:io_recv",
        "net/socket.c:____sys_recvmsg",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589195296,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589088560,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:902",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_recv",
        "net/socket.c:____sys_recvmsg",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589088560,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589806688,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:961",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_recv",
        "net/socket.c:____sys_recvmsg",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589806688,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591325600,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:1009",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_recv",
        "io_uring/io_uring.c:io_recv",
        "net/socket.c:____sys_recvmsg",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591325600,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593078816,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:1014",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recvmsg",
        "net/socket.c:____sys_recvmsg",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593078816,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593533386,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:1042",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": [
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recvmsg",
        "net/socket.c:____sys_recvmsg",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:sock_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593532240,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594305930,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:1064",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": [
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recv",
        "io_uring/net.c:io_recvmsg",
        "net/socket.c:____sys_recvmsg",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:sock_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594304784,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501830064,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:885",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501830064,
      "name": "sock_recvmsg",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234611336,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:885",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234611336,
      "name": "sock_recvmsg",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295233792,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:885",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295233792,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278176314,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:885",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278176314,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587949840,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:885",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587949840,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587662944,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:885",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587662944,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588281616,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:885",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588281616,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int sock_recvmsg(struct socket * sock, struct msghdr * msg, int flags)
```

```json
{
  "name": "sock_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588416768,
      "name": "sock_recvmsg",
      "external": true,
      "loc": "net/socket.c:885",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:__sys_recvfrom",
        "net/socket.c:sock_read_iter",
        "net/socket.c:kernel_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588416768,
      "name": "sock_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
<li>
<b>Param reordered. </b>
<code>sock, msg, size, flags</code> ➡️ <code>sock, msg, flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
