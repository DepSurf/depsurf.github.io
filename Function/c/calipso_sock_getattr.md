# Function: <code>calipso_sock_getattr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587695056,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1090",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587772752,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:530",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587695056,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071587772752,
      "name": "calipso_sock_getattr",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587903808,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1090",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587987952,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:533",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587903808,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071587987952,
      "name": "calipso_sock_getattr",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588060960,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1090",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588145888,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:533",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588060960,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    },
    {
      "addr": 18446744071588145888,
      "name": "calipso_sock_getattr",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588599296,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1090",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588693856,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:533",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588599296,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071588693856,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588962672,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1089",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589060608,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:533",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588962672,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071589060608,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589187424,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1089",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589286304,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:533",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589187424,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071589286304,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589641136,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1075",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589742192,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:520",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589641136,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071589742192,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589865344,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1075",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589966320,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:520",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589865344,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071589966320,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590893216,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1076",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590996560,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:520",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590893216,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    },
    {
      "addr": 18446744071590996560,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590954944,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1072",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591061184,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:521",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590954944,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071591061184,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590885632,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1072",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590991952,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:521",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590885632,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
    },
    {
      "addr": 18446744071590991952,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1072",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591829632,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:521",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591715424,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
    },
    {
      "addr": 18446744071592744356,
      "name": "calipso_sock_getattr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071591829632,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1072",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593543520,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:521",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593416336,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    },
    {
      "addr": 18446744071594630936,
      "name": "calipso_sock_getattr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593543520,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1072",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595464672,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:522",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595327120,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    },
    {
      "addr": 18446744071596364480,
      "name": "calipso_sock_getattr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071595464672,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1072",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595971760,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:522",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595722272,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
    },
    {
      "addr": 18446744071596892525,
      "name": "calipso_sock_getattr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071595971760,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1072",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596834256,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:525",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596570096,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
    },
    {
      "addr": 18446744071597817149,
      "name": "calipso_sock_getattr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071596834256,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503585568,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1075",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503701344,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:520",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503585568,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    },
    {
      "addr": 18446603336503701344,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236230068,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1075",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236336748,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:520",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236230068,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 3236336748,
      "name": "calipso_sock_getattr",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297389520,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1075",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297533152,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:520",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297389520,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
    },
    {
      "addr": 13835058055297533152,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279540174,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1075",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279632040,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:520",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279540174,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446743936279632040,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589469712,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1075",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589569920,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:520",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589469712,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071589569920,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589194704,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1075",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589294496,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:520",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589194704,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071589294496,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589906576,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1075",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590011952,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:520",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589906576,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071590011952,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_getattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589959216,
      "name": "calipso_sock_getattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1075",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590062032,
      "name": "calipso_sock_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:520",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_getattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589959216,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071590062032,
      "name": "calipso_sock_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int calipso_sock_getattr(struct sock * sk, struct netlbl_lsm_secattr * secattr)
```
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
