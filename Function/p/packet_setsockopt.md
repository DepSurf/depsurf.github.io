# Function: <code>packet_setsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int packet_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587257552,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3506",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587257552,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2914
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
int packet_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587718960,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3580",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587718960,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3190
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
int packet_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587936000,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3545",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587936000,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3210
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
int packet_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588091744,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3611",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588091744,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3393
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
int packet_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588636256,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3610",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588636256,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3427
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
int packet_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3588",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589015888,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3406
    },
    {
      "addr": 18446744071589019646,
      "name": "packet_setsockopt.cold.84",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int packet_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3600",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589240992,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3627
    },
    {
      "addr": 18446744071589244976,
      "name": "packet_setsockopt.cold.86",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int packet_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3635",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589696000,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3628
    },
    {
      "addr": 18446744071589700083,
      "name": "packet_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int packet_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3654",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589917456,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3628
    },
    {
      "addr": 18446744071589924362,
      "name": "packet_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int packet_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590946352,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3665",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590946352,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2027
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
int packet_setsockopt(struct socket * sock, int level, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3682",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591015984,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2284
    },
    {
      "addr": 18446744071591637689,
      "name": "packet_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int packet_setsockopt(struct socket * sock, int level, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3696",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590943456,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2789
    },
    {
      "addr": 18446744071591581069,
      "name": "packet_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int packet_setsockopt(struct socket * sock, int level, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3700",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591779312,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2796
    },
    {
      "addr": 18446744071592745520,
      "name": "packet_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int packet_setsockopt(struct socket * sock, int level, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3754",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593491440,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3051
    },
    {
      "addr": 18446744071594632134,
      "name": "packet_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int packet_setsockopt(struct socket * sock, int level, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3753",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595409952,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2748
    },
    {
      "addr": 18446744071596364876,
      "name": "packet_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int packet_setsockopt(struct socket * sock, int level, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3766",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595808000,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2767
    },
    {
      "addr": 18446744071596892999,
      "name": "packet_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int packet_setsockopt(struct socket * sock, int level, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3767",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596658560,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2767
    },
    {
      "addr": 18446744071597817652,
      "name": "packet_setsockopt.cold",
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
int packet_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503641416,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3654",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503641416,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3200
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
int packet_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236287888,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3654",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3236287888,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4112
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
int packet_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297466464,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3654",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297466464,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4144
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
int packet_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279588296,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3654",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279588296,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2566
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
int packet_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3654",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589521824,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3628
    },
    {
      "addr": 18446744071589528730,
      "name": "packet_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int packet_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3654",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589247888,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3628
    },
    {
      "addr": 18446744071589254794,
      "name": "packet_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int packet_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3654",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589963088,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3628
    },
    {
      "addr": 18446744071589969994,
      "name": "packet_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int packet_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "packet_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "packet_setsockopt",
      "external": false,
      "loc": "net/packet/af_packet.c:3654",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590015648,
      "name": "packet_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3663
    },
    {
      "addr": 18446744071590019685,
      "name": "packet_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char * optval</code> ➡️ <code>sockptr_t optval</code>
</li>
</ul>
</details>
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
