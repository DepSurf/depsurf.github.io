# Function: <code>__sock_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586173168,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1088",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_create_kern",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586173168,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586593872,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1085",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586593872,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586778240,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1128",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586778240,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586899360,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1177",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586899360,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 506
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587391088,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1196",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:SyS_socketcall",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587391088,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 511
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1218",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587710098,
      "name": "__sock_create.cold.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071587691936,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1205",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587843426,
      "name": "__sock_create.cold.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071587826032,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1347",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588147492,
      "name": "__sock_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071588128880,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1347",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588352756,
      "name": "__sock_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071588334016,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1357",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589212678,
      "name": "__sock_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071589193520,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1335",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591625548,
      "name": "__sock_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071589192048,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1326",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591568938,
      "name": "__sock_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071589085568,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1396",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592692114,
      "name": "__sock_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071589803904,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1444",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sys_socket_file",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594577619,
      "name": "__sock_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071591322912,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1449",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sys_socket_file",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596321471,
      "name": "__sock_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071593077072,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1478",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sys_socket_file",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596851189,
      "name": "__sock_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071593528512,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1500",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:__sys_socket_file",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597776039,
      "name": "__sock_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071594300352,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501827648,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1347",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501827648,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234609336,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1347",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234609336,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295229776,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1347",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295229776,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278174150,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1347",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278174150,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1347",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587959540,
      "name": "__sock_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071587940800,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1347",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587672644,
      "name": "__sock_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071587653904,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1347",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588291316,
      "name": "__sock_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071588272576,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int __sock_create(struct net * net, int family, int type, int protocol, struct socket * * res, int kern)
```

```json
{
  "name": "__sock_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sock_create",
      "external": true,
      "loc": "net/socket.c:1347",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socketpair",
        "net/socket.c:__sys_socket",
        "net/socket.c:sock_create_kern"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588426416,
      "name": "__sock_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071588407872,
      "name": "__sock_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
