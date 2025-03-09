# Function: <code>sock_getsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586197968,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1029",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:SyS_socketcall",
        "net/compat.c:compat_sock_getsockopt",
        "net/compat.c:compat_sock_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586197968,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1858
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586618480,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1029",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:SyS_socketcall",
        "net/compat.c:compat_sock_getsockopt",
        "net/compat.c:compat_sock_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586618480,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2094
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586803040,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1037",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:SyS_socketcall",
        "net/compat.c:compat_sock_getsockopt",
        "net/compat.c:compat_sock_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586803040,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2094
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
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586931872,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1093",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586931872,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2490
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
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587424864,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1097",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587424864,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2540
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1108",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:__sys_getsockopt",
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587731653,
      "name": "sock_getsockopt.cold.66",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587729120,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1093",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:__sys_getsockopt",
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587865877,
      "name": "sock_getsockopt.cold.65",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587862672,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3088
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1213",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:__sys_getsockopt",
        "net/compat.c:__compat_sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588170731,
      "name": "sock_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588167312,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3089
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1215",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:__sys_getsockopt",
        "net/compat.c:__compat_sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588375944,
      "name": "sock_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588372592,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3081
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1302",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt",
        "net/compat.c:__compat_sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589238525,
      "name": "sock_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589229152,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1292",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591625852,
      "name": "sock_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589227744,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1308",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591569236,
      "name": "sock_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589121200,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3293
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1417",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592692645,
      "name": "sock_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589839888,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3466
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1539",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594578161,
      "name": "sock_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071591372384,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3433
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
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593136336,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1963",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593136336,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593589152,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:2021",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593589152,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501882888,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1215",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:__arm64_sys_getsockopt",
        "net/compat.c:__compat_sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501882888,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3604
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
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234646828,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1215",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:__se_sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234646828,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3076
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
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295290688,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1215",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:__sys_getsockopt",
        "net/compat.c:__compat_sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295290688,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4020
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
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278203170,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1215",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:__se_sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278203170,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1696
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1215",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:__sys_getsockopt",
        "net/compat.c:__compat_sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587982728,
      "name": "sock_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587979376,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3081
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1215",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:__sys_getsockopt",
        "net/compat.c:__compat_sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587695832,
      "name": "sock_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587692480,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3081
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1215",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:__sys_getsockopt",
        "net/compat.c:__compat_sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588314504,
      "name": "sock_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588311152,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3081
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```

```json
{
  "name": "sock_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_getsockopt",
      "external": true,
      "loc": "net/core/sock.c:1215",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:__sys_getsockopt",
        "net/compat.c:__compat_sys_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588449721,
      "name": "sock_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588446368,
      "name": "sock_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3082
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int sock_getsockopt(struct socket * sock, int level, int optname, char * optval, int * optlen)
```
</details>
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
