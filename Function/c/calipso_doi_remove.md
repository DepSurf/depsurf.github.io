# Function: <code>calipso_doi_remove</code>

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
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587690000,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:448",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587772141,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:447",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587690000,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 18446744071587772624,
      "name": "calipso_doi_remove",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587898752,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:448",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587987341,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:450",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587898752,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 18446744071587987824,
      "name": "calipso_doi_remove",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588055936,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:448",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588145261,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:450",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588055936,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071588145760,
      "name": "calipso_doi_remove",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588594192,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:448",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588693117,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:450",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588594192,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071588693664,
      "name": "calipso_doi_remove",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588964544,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:448",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589059879,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:450",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588964544,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071589060416,
      "name": "calipso_doi_remove",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589188640,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:448",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589285575,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:450",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589188640,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071589286112,
      "name": "calipso_doi_remove",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589639504,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:434",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589741451,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:437",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589639504,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071589742000,
      "name": "calipso_doi_remove",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589863712,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:434",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589965579,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:437",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589863712,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071589966128,
      "name": "calipso_doi_remove",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590894752,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:434",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590995723,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:437",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590894752,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
    },
    {
      "addr": 18446744071590996368,
      "name": "calipso_doi_remove",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590953776,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:437",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591060347,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:438",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590953776,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    },
    {
      "addr": 18446744071591060992,
      "name": "calipso_doi_remove",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590886000,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:437",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590991115,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:438",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590886000,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    },
    {
      "addr": 18446744071590991760,
      "name": "calipso_doi_remove",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591716720,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:437",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591828747,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:438",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591716720,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    },
    {
      "addr": 18446744071591829440,
      "name": "calipso_doi_remove",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593414960,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:437",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593542467,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:438",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593414960,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    },
    {
      "addr": 18446744071593543280,
      "name": "calipso_doi_remove",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595325664,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:437",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595463459,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:439",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595325664,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    },
    {
      "addr": 18446744071595464368,
      "name": "calipso_doi_remove",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595720832,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:437",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595970547,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:439",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595720832,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    },
    {
      "addr": 18446744071595971456,
      "name": "calipso_doi_remove",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596568656,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:437",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596832974,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:442",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596568656,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    },
    {
      "addr": 18446744071596833952,
      "name": "calipso_doi_remove",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503582600,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:434",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503700364,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:437",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503582600,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446603336503701024,
      "name": "calipso_doi_remove",
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
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236225540,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:434",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236335844,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:437",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236225540,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 3236336516,
      "name": "calipso_doi_remove",
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
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297382896,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:434",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297531832,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:437",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297382896,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
    },
    {
      "addr": 13835058055297532784,
      "name": "calipso_doi_remove",
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
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279540818,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:434",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279631338,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:437",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279540818,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
    },
    {
      "addr": 18446743936279631810,
      "name": "calipso_doi_remove",
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
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589468080,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:434",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589569179,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:437",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589468080,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071589569728,
      "name": "calipso_doi_remove",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589193072,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:434",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589293755,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:437",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589193072,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071589294304,
      "name": "calipso_doi_remove",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589904944,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:434",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590011211,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:437",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589904944,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071590011760,
      "name": "calipso_doi_remove",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
```

```json
{
  "name": "calipso_doi_remove",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589954800,
      "name": "calipso_doi_remove",
      "external": false,
      "loc": "net/ipv6/calipso.c:434",
      "file": "net/ipv6/calipso.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590061291,
      "name": "calipso_doi_remove",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:437",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589954800,
      "name": "calipso_doi_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    },
    {
      "addr": 18446744071590061840,
      "name": "calipso_doi_remove",
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
int calipso_doi_remove(u32 doi, struct netlbl_audit * audit_info)
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
