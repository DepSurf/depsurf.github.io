# Function: <code>calipso_doi_add</code>

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
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587690272,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:359",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587772462,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:409",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_add"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587690272,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    },
    {
      "addr": 18446744071587772560,
      "name": "calipso_doi_add",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587899024,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:359",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587987662,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:412",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_add"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587899024,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    },
    {
      "addr": 18446744071587987760,
      "name": "calipso_doi_add",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588056208,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:359",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588145565,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:412",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588056208,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 18446744071588145696,
      "name": "calipso_doi_add",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588594480,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:359",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588693421,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:412",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588594480,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 18446744071588693568,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588963680,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:359",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589060173,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:412",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588963680,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 18446744071589060320,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589187776,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:359",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589285869,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:412",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589187776,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 18446744071589286016,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589641424,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:345",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589741761,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:399",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589641424,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    },
    {
      "addr": 18446744071589741904,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589865632,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:345",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589965889,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:399",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589865632,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    },
    {
      "addr": 18446744071589966032,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590894464,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:345",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590995985,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:399",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590894464,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    },
    {
      "addr": 18446744071590996272,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590956208,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:348",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591060609,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:400",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590956208,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071591060896,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590886240,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:348",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590991383,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:400",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590886240,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071590991664,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591716960,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:348",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591829063,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:400",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591716960,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071591829344,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593415408,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:348",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593542830,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:400",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593415408,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071593543152,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595326144,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:348",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595463854,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:401",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595326144,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071595464208,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595721312,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:348",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595970942,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:401",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595721312,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071595971296,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596569136,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:348",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596833430,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:404",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_add"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596569136,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071596833792,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503582968,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:345",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503700712,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:399",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503582968,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 18446603336503700880,
      "name": "calipso_doi_add",
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
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236225888,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:345",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236336244,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:399",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236225888,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 3236336404,
      "name": "calipso_doi_add",
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
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297383440,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:345",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297532284,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:399",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297383440,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
    },
    {
      "addr": 13835058055297532608,
      "name": "calipso_doi_add",
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
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279540450,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:345",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279631590,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:399",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_add"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279540450,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446743936279631700,
      "name": "calipso_doi_add",
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
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589470000,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:345",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589569489,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:399",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589470000,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    },
    {
      "addr": 18446744071589569632,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589194992,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:345",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589294065,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:399",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589194992,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    },
    {
      "addr": 18446744071589294208,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589906864,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:345",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590011521,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:399",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589906864,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    },
    {
      "addr": 18446744071590011664,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_add",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589955088,
      "name": "calipso_doi_add",
      "external": false,
      "loc": "net/ipv6/calipso.c:345",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590061601,
      "name": "calipso_doi_add",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:399",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589955088,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071590061744,
      "name": "calipso_doi_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int calipso_doi_add(struct calipso_doi * doi_def, struct netlbl_audit * audit_info)
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
