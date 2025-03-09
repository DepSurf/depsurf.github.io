# Function: <code>dev_ifsioc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int dev_ifsioc(struct net * net, struct socket * sock, unsigned int cmd, struct compat_ifreq * uifr32)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586169372,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/socket.c:2867",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl_trans"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586395936,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:241",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586395936,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 957
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int dev_ifsioc(struct net * net, struct socket * sock, unsigned int cmd, struct compat_ifreq * uifr32)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586589835,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/socket.c:2869",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl_trans"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586836832,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:241",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586836832,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 957
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int dev_ifsioc(struct net * net, struct socket * sock, unsigned int cmd, struct compat_ifreq * uifr32)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586774395,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/socket.c:2916",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl_trans"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587027760,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:241",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587027760,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 957
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int dev_ifsioc(struct net * net, struct socket * sock, unsigned int cmd, struct compat_ifreq * uifr32)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586904930,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/socket.c:2966",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587155952,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:243",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587155952,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 991
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int dev_ifsioc(struct net * net, struct socket * sock, unsigned int cmd, struct compat_ifreq * uifr32)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587396818,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/socket.c:2968",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587664352,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:244",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587664352,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1054
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
int dev_ifsioc(struct net * net, struct ifreq * ifr, unsigned int cmd)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587991472,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:224",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587991472,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 979
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
int dev_ifsioc(struct net * net, struct ifreq * ifr, unsigned int cmd)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588150272,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:224",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588150272,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 970
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
int dev_ifsioc(struct net * net, struct ifreq * ifr, unsigned int cmd)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588471408,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:224",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588471408,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
int dev_ifsioc(struct net * net, struct ifreq * ifr, unsigned int cmd)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588676848,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:224",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588676848,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
int dev_ifsioc(struct net * net, struct ifreq * ifr, unsigned int cmd)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589543152,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:231",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589543152,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 988
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
int dev_ifsioc(struct net * net, struct ifreq * ifr, unsigned int cmd)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589551744,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:241",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589551744,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1041
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
int dev_ifsioc(struct net * net, struct ifreq * ifr, unsigned int cmd)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589449696,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:241",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589449696,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1058
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
int dev_ifsioc(struct net * net, struct ifreq * ifr, void * data, unsigned int cmd)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590185008,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:310",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590185008,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1318
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
int dev_ifsioc(struct net * net, struct ifreq * ifr, void * data, unsigned int cmd)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591747888,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:312",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591747888,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1293
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
int dev_ifsioc(struct net * net, struct ifreq * ifr, void * data, unsigned int cmd)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593537984,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:312",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593537984,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1285
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
int dev_ifsioc(struct net * net, struct ifreq * ifr, void * data, unsigned int cmd)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594006960,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:333",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594006960,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1249
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
int dev_ifsioc(struct net * net, struct ifreq * ifr, void * data, unsigned int cmd)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:515",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594793088,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1466
    },
    {
      "addr": 18446744071597784040,
      "name": "dev_ifsioc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int dev_ifsioc(struct net * net, struct ifreq * ifr, unsigned int cmd)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502231208,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:224",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502231208,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
int dev_ifsioc(struct net * net, struct ifreq * ifr, unsigned int cmd)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234976200,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:224",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234976200,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 964
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
int dev_ifsioc(struct net * net, struct ifreq * ifr, unsigned int cmd)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295719536,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:224",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295719536,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1116
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
int dev_ifsioc(struct net * net, struct ifreq * ifr, unsigned int cmd)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278474120,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:224",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278474120,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
int dev_ifsioc(struct net * net, struct ifreq * ifr, unsigned int cmd)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588283584,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:224",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588283584,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
int dev_ifsioc(struct net * net, struct ifreq * ifr, unsigned int cmd)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587996400,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:224",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587996400,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
int dev_ifsioc(struct net * net, struct ifreq * ifr, unsigned int cmd)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588615408,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:224",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588615408,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
int dev_ifsioc(struct net * net, struct ifreq * ifr, unsigned int cmd)
```

```json
{
  "name": "dev_ifsioc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588753120,
      "name": "dev_ifsioc",
      "external": false,
      "loc": "net/core/dev_ioctl.c:224",
      "file": "net/core/dev_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl",
        "net/core/dev_ioctl.c:dev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588753120,
      "name": "dev_ifsioc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ifreq * ifr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct socket * sock</code>
</li>
<li>
<b>Param removed. </b>
<code>struct compat_ifreq * uifr32</code>
</li>
</ul>
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
<code>void * data</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, ifr, cmd</code> ➡️ <code>net, ifr, data, cmd</code>
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
