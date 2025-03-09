# Function: <code>calipso_req_setattr</code>

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
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587695728,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1207",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587772848,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:594",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587695728,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071587772848,
      "name": "calipso_req_setattr",
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
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587904480,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1207",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587988048,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:597",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587904480,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071587988048,
      "name": "calipso_req_setattr",
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
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588061584,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1207",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588145984,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:597",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588061584,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    },
    {
      "addr": 18446744071588145984,
      "name": "calipso_req_setattr",
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
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588600016,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1207",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588694000,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:597",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588600016,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
    },
    {
      "addr": 18446744071588694000,
      "name": "calipso_req_setattr",
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
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588965216,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1206",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589060752,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:597",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588965216,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071589060752,
      "name": "calipso_req_setattr",
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
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589189312,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1206",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589286448,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:597",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589189312,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071589286448,
      "name": "calipso_req_setattr",
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
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589642112,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1192",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589742336,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:584",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589642112,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071589742336,
      "name": "calipso_req_setattr",
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
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589866320,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1192",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589966464,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:584",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589866320,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071589966464,
      "name": "calipso_req_setattr",
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
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590893984,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1193",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590996704,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:584",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590893984,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071590996704,
      "name": "calipso_req_setattr",
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
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590955712,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1189",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591061328,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:585",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590955712,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071591061328,
      "name": "calipso_req_setattr",
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
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590884192,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1189",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590992096,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:585",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590884192,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071590992096,
      "name": "calipso_req_setattr",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591714848,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1189",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591829776,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:585",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591714848,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071591829776,
      "name": "calipso_req_setattr",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593415712,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1189",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593543712,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:585",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593415712,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071593543712,
      "name": "calipso_req_setattr",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595326464,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1189",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595464912,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:586",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595326464,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071595464912,
      "name": "calipso_req_setattr",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595721632,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1189",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595972000,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:586",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595721632,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071595972000,
      "name": "calipso_req_setattr",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596569456,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1189",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596834496,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:589",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596569456,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071596834496,
      "name": "calipso_req_setattr",
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
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503582336,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1192",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503701584,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:584",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503582336,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446603336503701584,
      "name": "calipso_req_setattr",
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
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236230688,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1192",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236336920,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:584",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236230688,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 3236336920,
      "name": "calipso_req_setattr",
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
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297390592,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1192",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297533424,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:584",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297390592,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 13835058055297533424,
      "name": "calipso_req_setattr",
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
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279538518,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1192",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279632220,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:584",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279538518,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446743936279632220,
      "name": "calipso_req_setattr",
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
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589470688,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1192",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589570064,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:584",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589470688,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071589570064,
      "name": "calipso_req_setattr",
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
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589195680,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1192",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589294640,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:584",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589195680,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071589294640,
      "name": "calipso_req_setattr",
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
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589907552,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1192",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590012096,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:584",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589907552,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071590012096,
      "name": "calipso_req_setattr",
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
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_req_setattr",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589959920,
      "name": "calipso_req_setattr",
      "external": false,
      "loc": "net/ipv6/calipso.c:1192",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590062176,
      "name": "calipso_req_setattr",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:584",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_req_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589959920,
      "name": "calipso_req_setattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071590062176,
      "name": "calipso_req_setattr",
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
int calipso_req_setattr(struct request_sock * req, const struct calipso_doi * doi_def, const struct netlbl_lsm_secattr * secattr)
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
