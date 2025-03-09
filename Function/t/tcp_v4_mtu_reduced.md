# Function: <code>tcp_v4_mtu_reduced</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586696256,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:272",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586696256,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587134704,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:271",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587134704,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587347786,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:270",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587338432,
      "name": "tcp_v4_mtu_reduced.part.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071587338608,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587480585,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:282",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587470096,
      "name": "tcp_v4_mtu_reduced.part.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071587470272,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588002614,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:282",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587999104,
      "name": "tcp_v4_mtu_reduced.part.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071587999296,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588353376,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:339",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588345840,
      "name": "tcp_v4_mtu_reduced.part.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071588346032,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588543915,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:340",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588535312,
      "name": "tcp_v4_mtu_reduced.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071588535504,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588954790,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:335",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588945968,
      "name": "tcp_v4_mtu_reduced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071588946160,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589179078,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:338",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589165664,
      "name": "tcp_v4_mtu_reduced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071589165856,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590150327,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:336",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590138144,
      "name": "tcp_v4_mtu_reduced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071590138336,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590199063,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:337",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590185648,
      "name": "tcp_v4_mtu_reduced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071590185840,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590105008,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:337",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590105008,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590878834,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:337",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592720065,
      "name": "tcp_v4_mtu_reduced.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071590878784,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592517952,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:338",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594606481,
      "name": "tcp_v4_mtu_reduced.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071592517888,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594374560,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:347",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596341818,
      "name": "tcp_v4_mtu_reduced.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071594374496,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594762844,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:348",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596871094,
      "name": "tcp_v4_mtu_reduced.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071594762784,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595569338,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:350",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597794752,
      "name": "tcp_v4_mtu_reduced.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071595569280,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502796892,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:338",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502782264,
      "name": "tcp_v4_mtu_reduced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446603336502782496,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235500184,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:338",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235494444,
      "name": "tcp_v4_mtu_reduced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 3235494648,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296437356,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:338",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296422208,
      "name": "tcp_v4_mtu_reduced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 13835058055296422544,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278914686,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:338",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278903620,
      "name": "tcp_v4_mtu_reduced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 18446743936278903828,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588785462,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:338",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588772048,
      "name": "tcp_v4_mtu_reduced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071588772240,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588497398,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:338",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588483984,
      "name": "tcp_v4_mtu_reduced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071588484176,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589221638,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:338",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589208224,
      "name": "tcp_v4_mtu_reduced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071589208416,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_v4_mtu_reduced(struct sock * sk)
```

```json
{
  "name": "tcp_v4_mtu_reduced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589261748,
      "name": "tcp_v4_mtu_reduced",
      "external": true,
      "loc": "net/ipv4/tcp_ipv4.c:338",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589248496,
      "name": "tcp_v4_mtu_reduced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071589248688,
      "name": "tcp_v4_mtu_reduced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
