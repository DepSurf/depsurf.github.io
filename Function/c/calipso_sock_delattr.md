# Function: <code>calipso_sock_delattr</code>

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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587693200,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1174",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587772816,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:574",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_delattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587693200,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071587772816,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587901952,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1174",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587988016,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:577",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_delattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587901952,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071587988016,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588059760,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1174",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588145952,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:577",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_delattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588059760,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    },
    {
      "addr": 18446744071588145952,
      "name": "calipso_sock_delattr",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588598016,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1174",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588693952,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:577",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_delattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588598016,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    },
    {
      "addr": 18446744071588693952,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588964288,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1173",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589060704,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:577",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_delattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588964288,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    },
    {
      "addr": 18446744071589060704,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589188384,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1173",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589286400,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:577",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_delattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589188384,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    },
    {
      "addr": 18446744071589286400,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589643040,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1159",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589742288,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:564",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_delattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589643040,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071589742288,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589867248,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1159",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589966416,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:564",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_delattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589867248,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071589966416,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590892464,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1160",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590996656,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:564",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590892464,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071590996656,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590954320,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1156",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591061280,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:565",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590954320,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
    },
    {
      "addr": 18446744071591061280,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590884736,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1156",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590992048,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:565",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590884736,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 18446744071590992048,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1156",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591829728,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:565",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591716144,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071592744420,
      "name": "calipso_sock_delattr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071591829728,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1156",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593543648,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:565",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593417152,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
    },
    {
      "addr": 18446744071594631000,
      "name": "calipso_sock_delattr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593543648,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1156",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595464832,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:566",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595327968,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
    },
    {
      "addr": 18446744071596364544,
      "name": "calipso_sock_delattr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071595464832,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1156",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595971920,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:566",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595723104,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    },
    {
      "addr": 18446744071596892575,
      "name": "calipso_sock_delattr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071595971920,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1156",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596834416,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:569",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596570928,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    },
    {
      "addr": 18446744071597817199,
      "name": "calipso_sock_delattr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071596834416,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503581832,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1159",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503701520,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:564",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_delattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503581832,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446603336503701520,
      "name": "calipso_sock_delattr",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236231732,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1159",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236336868,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:564",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_delattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236231732,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 3236336868,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297392176,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1159",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297533344,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:564",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_delattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297392176,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    },
    {
      "addr": 13835058055297533344,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279536584,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1159",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279632172,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:564",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_delattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279536584,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446743936279632172,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589471616,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1159",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589570016,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:564",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_delattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589471616,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071589570016,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589196608,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1159",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589294592,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:564",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_delattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589196608,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071589294592,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589908480,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1159",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590012048,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:564",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_delattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589908480,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071590012048,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void calipso_sock_delattr(struct sock * sk)
```

```json
{
  "name": "calipso_sock_delattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589960896,
      "name": "calipso_sock_delattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1159",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590062128,
      "name": "calipso_sock_delattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:564",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_sock_delattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589960896,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    },
    {
      "addr": 18446744071590062128,
      "name": "calipso_sock_delattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void calipso_sock_delattr(struct sock * sk)
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
