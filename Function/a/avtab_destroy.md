# Function: <code>avtab_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582316496,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:279",
      "file": "security/selinux/ss/avtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582316496,
      "name": "avtab_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582537744,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:279",
      "file": "security/selinux/ss/avtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582537744,
      "name": "avtab_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582630560,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:279",
      "file": "security/selinux/ss/avtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582630560,
      "name": "avtab_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582724639,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:279",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582721168,
      "name": "avtab_destroy.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071582722672,
      "name": "avtab_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582880623,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:279",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582877136,
      "name": "avtab_destroy.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071582878640,
      "name": "avtab_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583078519,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:279",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583075296,
      "name": "avtab_destroy.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071583076816,
      "name": "avtab_destroy",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583194039,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:279",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583190688,
      "name": "avtab_destroy.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071583192208,
      "name": "avtab_destroy",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583380971,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:277",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583377936,
      "name": "avtab_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071583379280,
      "name": "avtab_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583486859,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:277",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583483824,
      "name": "avtab_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071583485168,
      "name": "avtab_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583832971,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:277",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583829600,
      "name": "avtab_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071583831232,
      "name": "avtab_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583954875,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:277",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_duplicate"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_duplicate",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_destroy_dup",
        "security/selinux/ss/conditional.c:duplicate_policydb_cond_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583951120,
      "name": "avtab_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071583952752,
      "name": "avtab_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583981755,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:277",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_dup",
        "security/selinux/ss/conditional.c:cond_policydb_destroy_dup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583978208,
      "name": "avtab_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071583979904,
      "name": "avtab_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584348443,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:279",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_dup",
        "security/selinux/ss/conditional.c:cond_policydb_dup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584344528,
      "name": "avtab_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071584346224,
      "name": "avtab_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584970329,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:279",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_dup",
        "security/selinux/ss/conditional.c:cond_policydb_dup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584966272,
      "name": "avtab_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071584967968,
      "name": "avtab_destroy",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585684397,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:279",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_dup",
        "security/selinux/ss/conditional.c:cond_policydb_dup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585680032,
      "name": "avtab_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071585681824,
      "name": "avtab_destroy",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585914637,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:279",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_dup",
        "security/selinux/ss/conditional.c:cond_policydb_dup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585910288,
      "name": "avtab_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071585912096,
      "name": "avtab_destroy",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586162621,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:223",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_dup",
        "security/selinux/ss/conditional.c:cond_policydb_dup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586158816,
      "name": "avtab_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071586160256,
      "name": "avtab_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495252744,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:277",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495249104,
      "name": "avtab_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446603336495250856,
      "name": "avtab_destroy",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228634272,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:277",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228630372,
      "name": "avtab_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 3228632320,
      "name": "avtab_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289224244,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:277",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289219504,
      "name": "avtab_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 13835058055289221728,
      "name": "avtab_destroy",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274477558,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:277",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274473900,
      "name": "avtab_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446743936274475756,
      "name": "avtab_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583455595,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:277",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583452560,
      "name": "avtab_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071583453904,
      "name": "avtab_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583392667,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:277",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389632,
      "name": "avtab_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071583390976,
      "name": "avtab_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583439371,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:277",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583436336,
      "name": "avtab_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071583437680,
      "name": "avtab_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void avtab_destroy(struct avtab * h)
```

```json
{
  "name": "avtab_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583535627,
      "name": "avtab_destroy",
      "external": true,
      "loc": "security/selinux/ss/avtab.c:277",
      "file": "security/selinux/ss/avtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/conditional.c:cond_policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583532592,
      "name": "avtab_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071583533936,
      "name": "avtab_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
