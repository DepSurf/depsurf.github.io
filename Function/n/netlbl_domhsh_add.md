# Function: <code>netlbl_domhsh_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587283984,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:365",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587283984,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1456
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
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587751104,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:417",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587751104,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1683
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
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587966320,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:417",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587966320,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1683
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588124448,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:417",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588124448,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1683
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588672272,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:417",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588672272,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1683
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589038832,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:417",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589038832,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1689
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589264832,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:417",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589264832,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1689
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
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589720112,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:403",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589720112,
      "name": "netlbl_domhsh_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1371
    },
    {
      "addr": 18446744071589721488,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589944416,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:403",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589944416,
      "name": "netlbl_domhsh_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1371
    },
    {
      "addr": 18446744071589945792,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590975877,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:405",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590974432,
      "name": "netlbl_domhsh_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1384
    },
    {
      "addr": 18446744071590975824,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591040659,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:405",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591039216,
      "name": "netlbl_domhsh_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1374
    },
    {
      "addr": 18446744071591040592,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590971235,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:405",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590969792,
      "name": "netlbl_domhsh_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1368
    },
    {
      "addr": 18446744071590971168,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591808771,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:405",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591807328,
      "name": "netlbl_domhsh_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1368
    },
    {
      "addr": 18446744071591808704,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593520626,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:405",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593519136,
      "name": "netlbl_domhsh_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1402
    },
    {
      "addr": 18446744071593520544,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595440770,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:405",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595439248,
      "name": "netlbl_domhsh_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1402
    },
    {
      "addr": 18446744071595440672,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595947746,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:405",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595946224,
      "name": "netlbl_domhsh_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1400
    },
    {
      "addr": 18446744071595947648,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596809618,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:405",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596808048,
      "name": "netlbl_domhsh_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1447
    },
    {
      "addr": 18446744071596809520,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503675784,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:403",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503675784,
      "name": "netlbl_domhsh_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1604
    },
    {
      "addr": 18446603336503677392,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236312576,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:403",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236312576,
      "name": "netlbl_domhsh_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1640
    },
    {
      "addr": 3236314216,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297501488,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:403",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297501488,
      "name": "netlbl_domhsh_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1880
    },
    {
      "addr": 13835058055297503376,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279612184,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:403",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279612184,
      "name": "netlbl_domhsh_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1172
    },
    {
      "addr": 18446743936279613356,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589548016,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:403",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589548016,
      "name": "netlbl_domhsh_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1371
    },
    {
      "addr": 18446744071589549392,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589272592,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:403",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589272592,
      "name": "netlbl_domhsh_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1371
    },
    {
      "addr": 18446744071589273968,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589990048,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:403",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589990048,
      "name": "netlbl_domhsh_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1371
    },
    {
      "addr": 18446744071589991424,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
int netlbl_domhsh_add(struct netlbl_dom_map * entry, struct netlbl_audit * audit_info)
```

```json
{
  "name": "netlbl_domhsh_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590039904,
      "name": "netlbl_domhsh_add",
      "external": true,
      "loc": "net/netlabel/netlabel_domainhash.c:403",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add",
        "net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590039904,
      "name": "netlbl_domhsh_add.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1364
    },
    {
      "addr": 18446744071590041280,
      "name": "netlbl_domhsh_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
