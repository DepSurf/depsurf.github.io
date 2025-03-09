# Function: <code>calipso_sock_setattr</code>

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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587695984,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1143",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587772784,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:554",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587695984,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071587772784,
      "name": "calipso_sock_setattr",
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587904736,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1143",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587987984,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:557",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587904736,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071587987984,
      "name": "calipso_sock_setattr",
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588061808,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1143",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588145920,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:557",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588061808,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071588145920,
      "name": "calipso_sock_setattr",
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588600240,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1143",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588693904,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:557",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588600240,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071588693904,
      "name": "calipso_sock_setattr",
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588965424,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1142",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589060656,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:557",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588965424,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071589060656,
      "name": "calipso_sock_setattr",
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589189520,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1142",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589286352,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:557",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589189520,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071589286352,
      "name": "calipso_sock_setattr",
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589642320,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1128",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589742240,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:544",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589642320,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071589742240,
      "name": "calipso_sock_setattr",
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589866528,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1128",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589966368,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:544",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589866528,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071589966368,
      "name": "calipso_sock_setattr",
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590894208,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1129",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590996608,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:544",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590894208,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071590996608,
      "name": "calipso_sock_setattr",
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590955936,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1125",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591061232,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:545",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590955936,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    },
    {
      "addr": 18446744071591061232,
      "name": "calipso_sock_setattr",
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590885008,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1125",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590992000,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:545",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590885008,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071590992000,
      "name": "calipso_sock_setattr",
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1125",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591829680,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:545",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591716432,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071592744452,
      "name": "calipso_sock_setattr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071591829680,
      "name": "calipso_sock_setattr",
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1125",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593543584,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:545",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593417472,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071594631032,
      "name": "calipso_sock_setattr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593543584,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1125",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595464752,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:546",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595328304,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    },
    {
      "addr": 18446744071596364576,
      "name": "calipso_sock_setattr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071595464752,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1125",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595971840,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:546",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595723440,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071596892600,
      "name": "calipso_sock_setattr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071595971840,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1125",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596834336,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:549",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596571264,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071597817224,
      "name": "calipso_sock_setattr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071596834336,
      "name": "calipso_sock_setattr",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503582056,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1128",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503701424,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:544",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503582056,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446603336503701424,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236230928,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1128",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236336808,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:544",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236230928,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 3236336808,
      "name": "calipso_sock_setattr",
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297390976,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1128",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297533248,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:544",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297390976,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    },
    {
      "addr": 13835058055297533248,
      "name": "calipso_sock_setattr",
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279538724,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1128",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279632102,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:544",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279538724,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446743936279632102,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589470896,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1128",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589569968,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:544",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589470896,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071589569968,
      "name": "calipso_sock_setattr",
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589195888,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1128",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589294544,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:544",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589195888,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071589294544,
      "name": "calipso_sock_setattr",
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589907760,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1128",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590012000,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:544",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589907760,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071590012000,
      "name": "calipso_sock_setattr",
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_sock_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589960128,
      "name": "calipso_sock_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1128",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590062080,
      "name": "calipso_sock_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:544",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_conn_setattr",
        "net/netlabel/netlabel_kapi.c:netlbl_sock_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589960128,
      "name": "calipso_sock_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071590062080,
      "name": "calipso_sock_setattr",
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
int calipso_sock_setattr(struct sock * sk, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
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
