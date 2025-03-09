# Function: <code>calipso_doi_putdef</code>

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
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587691824,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:518",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587771818,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:485",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587691824,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071587772688,
      "name": "calipso_doi_putdef",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587900576,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:518",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587987018,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:488",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587900576,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071587987888,
      "name": "calipso_doi_putdef",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588057728,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:518",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588144930,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:488",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588057728,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071588145824,
      "name": "calipso_doi_putdef",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588596000,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:518",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588692776,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:488",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588596000,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071588693760,
      "name": "calipso_doi_putdef",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588962560,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:518",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589059528,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:488",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588962560,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071589060512,
      "name": "calipso_doi_putdef",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589186224,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:518",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589285224,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:488",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589186224,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071589286208,
      "name": "calipso_doi_putdef",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589639392,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:504",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589741092,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:475",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589639392,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071589742096,
      "name": "calipso_doi_putdef",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589863600,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:504",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589965220,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:475",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589863600,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071589966224,
      "name": "calipso_doi_putdef",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590892720,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:504",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590995314,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:475",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590892720,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071590996464,
      "name": "calipso_doi_putdef",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590951120,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:502",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/calipso.c:calipso_doi_remove"
      ]
    },
    {
      "addr": 18446744071591059938,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:476",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590951120,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071591061088,
      "name": "calipso_doi_putdef",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590881520,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:502",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/calipso.c:calipso_doi_remove"
      ]
    },
    {
      "addr": 18446744071590990690,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:476",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590881520,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071590991856,
      "name": "calipso_doi_putdef",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591712176,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:502",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/calipso.c:calipso_doi_remove"
      ]
    },
    {
      "addr": 18446744071591828370,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:476",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591712176,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071591829536,
      "name": "calipso_doi_putdef",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593411744,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:502",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/calipso.c:calipso_doi_remove"
      ]
    },
    {
      "addr": 18446744071593542034,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:476",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593411744,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071593543392,
      "name": "calipso_doi_putdef",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595322336,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:502",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/calipso.c:calipso_doi_remove"
      ]
    },
    {
      "addr": 18446744071595463010,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:477",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595322336,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071595464512,
      "name": "calipso_doi_putdef",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595717344,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:502",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/calipso.c:calipso_doi_remove"
      ]
    },
    {
      "addr": 18446744071595970098,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:477",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595717344,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071595971600,
      "name": "calipso_doi_putdef",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596565120,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:502",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/calipso.c:calipso_doi_remove"
      ]
    },
    {
      "addr": 18446744071596832530,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:480",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596565120,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071596834096,
      "name": "calipso_doi_putdef",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503580912,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:504",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503699856,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:475",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503580912,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 18446603336503701184,
      "name": "calipso_doi_putdef",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236226412,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:504",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236335408,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:475",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236226412,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 3236336636,
      "name": "calipso_doi_putdef",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297385616,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:504",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297531244,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:475",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297385616,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 13835058055297532976,
      "name": "calipso_doi_putdef",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279537976,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:504",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279631080,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:475",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279537976,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446743936279631922,
      "name": "calipso_doi_putdef",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589467968,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:504",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589568820,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:475",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589467968,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071589569824,
      "name": "calipso_doi_putdef",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589192960,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:504",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589293396,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:475",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589192960,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071589294400,
      "name": "calipso_doi_putdef",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589904832,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:504",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590010852,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:475",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589904832,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071590011856,
      "name": "calipso_doi_putdef",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void calipso_doi_putdef(struct calipso_doi * doi_def)
```

```json
{
  "name": "calipso_doi_putdef",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589956576,
      "name": "calipso_doi_putdef",
      "external": false,
      "loc": "net/ipv6/calipso.c:504",
      "file": "net/ipv6/calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590060932,
      "name": "calipso_doi_putdef",
      "external": true,
      "loc": "net/netlabel/netlabel_calipso.c:475",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589956576,
      "name": "calipso_doi_putdef",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071590061936,
      "name": "calipso_doi_putdef",
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
void calipso_doi_putdef(struct calipso_doi * doi_def)
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
