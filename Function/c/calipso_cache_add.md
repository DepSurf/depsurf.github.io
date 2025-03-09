# Function: <code>calipso_cache_add</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587693408,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:275",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587773072,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:730",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587693408,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
    },
    {
      "addr": 18446744071587773072,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587902160,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:275",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587988272,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:733",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587902160,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
    },
    {
      "addr": 18446744071587988272,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588058848,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:275",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588146208,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:733",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588058848,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
    },
    {
      "addr": 18446744071588146208,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588597008,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:275",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588694336,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:733",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588597008,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
    },
    {
      "addr": 18446744071588694336,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588963024,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:275",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589061088,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:733",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588963024,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
    },
    {
      "addr": 18446744071589061088,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589185072,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:275",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589286784,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:733",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589185072,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 760
    },
    {
      "addr": 18446744071589286784,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589638256,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:261",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589742672,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:720",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589638256,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 761
    },
    {
      "addr": 18446744071589742672,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589862464,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:261",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589966800,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:720",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589862464,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 761
    },
    {
      "addr": 18446744071589966800,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590889616,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:261",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590997040,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:720",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590889616,
      "name": "calipso_cache_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
    },
    {
      "addr": 18446744071590890032,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071590997040,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590951216,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:264",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591061664,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:721",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590951216,
      "name": "calipso_cache_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
    },
    {
      "addr": 18446744071590951632,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071591061664,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590881056,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:264",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590992432,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:721",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590881056,
      "name": "calipso_cache_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071590881472,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071590992432,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591711712,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:264",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591830112,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:721",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591711712,
      "name": "calipso_cache_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071591712128,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071591830112,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593411888,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:264",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593544128,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:721",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593411888,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    },
    {
      "addr": 18446744071593544128,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595322496,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:264",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595465440,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:722",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595322496,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    },
    {
      "addr": 18446744071595465440,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595717504,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:264",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595972528,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:722",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595717504,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
    },
    {
      "addr": 18446744071595972528,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596565280,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:264",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596835024,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:725",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596565280,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
    },
    {
      "addr": 18446744071596835024,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503583344,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:261",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503702120,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:720",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503583344,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 908
    },
    {
      "addr": 18446603336503702120,
      "name": "calipso_cache_add",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236227528,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:261",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236337324,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:720",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236227528,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
    },
    {
      "addr": 3236337324,
      "name": "calipso_cache_add",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297386960,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:261",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297534064,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:720",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297386960,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1068
    },
    {
      "addr": 13835058055297534064,
      "name": "calipso_cache_add",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279536782,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:261",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279632614,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:720",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279536782,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 870
    },
    {
      "addr": 18446743936279632614,
      "name": "calipso_cache_add",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589466832,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:261",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589570400,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:720",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589466832,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 761
    },
    {
      "addr": 18446744071589570400,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589191824,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:261",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589294976,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:720",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589191824,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 761
    },
    {
      "addr": 18446744071589294976,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589903696,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:261",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590012432,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:720",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589903696,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 761
    },
    {
      "addr": 18446744071590012432,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "calipso_cache_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589956688,
      "name": "calipso_cache_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:261",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590062512,
      "name": "calipso_cache_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:720",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589956688,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 761
    },
    {
      "addr": 18446744071590062512,
      "name": "calipso_cache_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int calipso_cache_add(const unsigned char * calipso_ptr, const struct netlbl_lsm_secattr * secattr)
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
