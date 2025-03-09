# Function: <code>dev_ifconf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_ifconf",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586169404,
      "name": "dev_ifconf",
      "external": false,
      "loc": "net/socket.c:2601",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl_trans"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586397711,
      "name": "dev_ifconf",
      "external": false,
      "loc": "net/core/dev_ioctl.c:67",
      "file": "net/core/dev_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev_ioctl.c:dev_ioctl"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_ifconf",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586589867,
      "name": "dev_ifconf",
      "external": false,
      "loc": "net/socket.c:2603",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl_trans"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586838717,
      "name": "dev_ifconf",
      "external": false,
      "loc": "net/core/dev_ioctl.c:67",
      "file": "net/core/dev_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev_ioctl.c:dev_ioctl"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_ifconf",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586774427,
      "name": "dev_ifconf",
      "external": false,
      "loc": "net/socket.c:2650",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl_trans"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587029645,
      "name": "dev_ifconf",
      "external": false,
      "loc": "net/core/dev_ioctl.c:67",
      "file": "net/core/dev_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev_ioctl.c:dev_ioctl"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_ifconf",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586905125,
      "name": "dev_ifconf",
      "external": false,
      "loc": "net/socket.c:2700",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587157396,
      "name": "dev_ifconf",
      "external": false,
      "loc": "net/core/dev_ioctl.c:68",
      "file": "net/core/dev_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev_ioctl.c:dev_ioctl"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_ifconf",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587397013,
      "name": "dev_ifconf",
      "external": false,
      "loc": "net/socket.c:2702",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587665866,
      "name": "dev_ifconf",
      "external": false,
      "loc": "net/core/dev_ioctl.c:69",
      "file": "net/core/dev_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev_ioctl.c:dev_ioctl"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int dev_ifconf(struct net * net, struct ifconf * ifc, int size)
```

```json
{
  "name": "dev_ifconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587992576,
      "name": "dev_ifconf",
      "external": true,
      "loc": "net/core/dev_ioctl.c:53",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:sock_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587992576,
      "name": "dev_ifconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int dev_ifconf(struct net * net, struct ifconf * ifc, int size)
```

```json
{
  "name": "dev_ifconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588151360,
      "name": "dev_ifconf",
      "external": true,
      "loc": "net/core/dev_ioctl.c:53",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:sock_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588151360,
      "name": "dev_ifconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int dev_ifconf(struct net * net, struct ifconf * ifc, int size)
```

```json
{
  "name": "dev_ifconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588472512,
      "name": "dev_ifconf",
      "external": true,
      "loc": "net/core/dev_ioctl.c:53",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:sock_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588472512,
      "name": "dev_ifconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int dev_ifconf(struct net * net, struct ifconf * ifc, int size)
```

```json
{
  "name": "dev_ifconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588677952,
      "name": "dev_ifconf",
      "external": true,
      "loc": "net/core/dev_ioctl.c:53",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:sock_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588677952,
      "name": "dev_ifconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int dev_ifconf(struct net * net, struct ifconf * ifc, int size)
```

```json
{
  "name": "dev_ifconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589544144,
      "name": "dev_ifconf",
      "external": true,
      "loc": "net/core/dev_ioctl.c:53",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:sock_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589544144,
      "name": "dev_ifconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int dev_ifconf(struct net * net, struct ifconf * ifc, int size)
```

```json
{
  "name": "dev_ifconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589552800,
      "name": "dev_ifconf",
      "external": true,
      "loc": "net/core/dev_ioctl.c:54",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:sock_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589552800,
      "name": "dev_ifconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int dev_ifconf(struct net * net, struct ifconf * ifc, int size)
```

```json
{
  "name": "dev_ifconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589450768,
      "name": "dev_ifconf",
      "external": true,
      "loc": "net/core/dev_ioctl.c:54",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:sock_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589450768,
      "name": "dev_ifconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int dev_ifconf(struct net * net, struct ifconf * uifc)
```

```json
{
  "name": "dev_ifconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590186336,
      "name": "dev_ifconf",
      "external": true,
      "loc": "net/core/dev_ioctl.c:35",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590186336,
      "name": "dev_ifconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int dev_ifconf(struct net * net, struct ifconf * uifc)
```

```json
{
  "name": "dev_ifconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591749184,
      "name": "dev_ifconf",
      "external": true,
      "loc": "net/core/dev_ioctl.c:37",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591749184,
      "name": "dev_ifconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int dev_ifconf(struct net * net, struct ifconf * uifc)
```

```json
{
  "name": "dev_ifconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593539296,
      "name": "dev_ifconf",
      "external": true,
      "loc": "net/core/dev_ioctl.c:37",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593539296,
      "name": "dev_ifconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int dev_ifconf(struct net * net, struct ifconf * uifc)
```

```json
{
  "name": "dev_ifconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594008240,
      "name": "dev_ifconf",
      "external": true,
      "loc": "net/core/dev_ioctl.c:37",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594008240,
      "name": "dev_ifconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int dev_ifconf(struct net * net, struct ifconf * uifc)
```

```json
{
  "name": "dev_ifconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594794576,
      "name": "dev_ifconf",
      "external": true,
      "loc": "net/core/dev_ioctl.c:38",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594794576,
      "name": "dev_ifconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int dev_ifconf(struct net * net, struct ifconf * ifc, int size)
```

```json
{
  "name": "dev_ifconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502231880,
      "name": "dev_ifconf",
      "external": true,
      "loc": "net/core/dev_ioctl.c:53",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:sock_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502231880,
      "name": "dev_ifconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int dev_ifconf(struct net * net, struct ifconf * ifc, int size)
```

```json
{
  "name": "dev_ifconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234977164,
      "name": "dev_ifconf",
      "external": true,
      "loc": "net/core/dev_ioctl.c:53",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234977164,
      "name": "dev_ifconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int dev_ifconf(struct net * net, struct ifconf * ifc, int size)
```

```json
{
  "name": "dev_ifconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295720880,
      "name": "dev_ifconf",
      "external": true,
      "loc": "net/core/dev_ioctl.c:53",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:sock_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295720880,
      "name": "dev_ifconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int dev_ifconf(struct net * net, struct ifconf * ifc, int size)
```

```json
{
  "name": "dev_ifconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278474832,
      "name": "dev_ifconf",
      "external": true,
      "loc": "net/core/dev_ioctl.c:53",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:sock_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278474832,
      "name": "dev_ifconf",
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
int dev_ifconf(struct net * net, struct ifconf * ifc, int size)
```

```json
{
  "name": "dev_ifconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588284688,
      "name": "dev_ifconf",
      "external": true,
      "loc": "net/core/dev_ioctl.c:53",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:sock_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588284688,
      "name": "dev_ifconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int dev_ifconf(struct net * net, struct ifconf * ifc, int size)
```

```json
{
  "name": "dev_ifconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587997504,
      "name": "dev_ifconf",
      "external": true,
      "loc": "net/core/dev_ioctl.c:53",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:sock_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587997504,
      "name": "dev_ifconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int dev_ifconf(struct net * net, struct ifconf * ifc, int size)
```

```json
{
  "name": "dev_ifconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588616512,
      "name": "dev_ifconf",
      "external": true,
      "loc": "net/core/dev_ioctl.c:53",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:sock_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588616512,
      "name": "dev_ifconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int dev_ifconf(struct net * net, struct ifconf * ifc, int size)
```

```json
{
  "name": "dev_ifconf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588754256,
      "name": "dev_ifconf",
      "external": true,
      "loc": "net/core/dev_ioctl.c:53",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:sock_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588754256,
      "name": "dev_ifconf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int dev_ifconf(struct net * net, struct ifconf * ifc, int size)
```
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ifconf * uifc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ifconf * ifc</code>
</li>
<li>
<b>Param removed. </b>
<code>int size</code>
</li>
</ul>
</details>
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
