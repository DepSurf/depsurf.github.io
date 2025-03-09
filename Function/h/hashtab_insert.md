# Function: <code>hashtab_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582311408,
      "name": "hashtab_insert",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:39",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582311408,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int hashtab_insert(struct hashtab * h, void * key, void * datum)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582532592,
      "name": "hashtab_insert",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:39",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582532592,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int hashtab_insert(struct hashtab * h, void * key, void * datum)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582625408,
      "name": "hashtab_insert",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:39",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582625408,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582717312,
      "name": "hashtab_insert",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:39",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582717312,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582873200,
      "name": "hashtab_insert",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:42",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582873200,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583071456,
      "name": "hashtab_insert",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:42",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583071456,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583184944,
      "name": "hashtab_insert",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:42",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583184944,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583372176,
      "name": "hashtab_insert",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:42",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583372176,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583478128,
      "name": "hashtab_insert",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:42",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583478128,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583823584,
      "name": "hashtab_insert",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:49",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583823584,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum, struct hashtab_key_params key_params)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583945799,
      "name": "hashtab_insert",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:61",
      "file": "security/selinux/ss/symtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/symtab.c:symtab_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583966303,
      "name": "hashtab_insert",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:61",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:range_read"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583956432,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum, struct hashtab_key_params key_params)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583972791,
      "name": "hashtab_insert",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:61",
      "file": "security/selinux/ss/symtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/symtab.c:symtab_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583991380,
      "name": "hashtab_insert",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:61",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:range_read"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583983184,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum, struct hashtab_key_params key_params)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584338391,
      "name": "hashtab_insert",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:61",
      "file": "security/selinux/ss/symtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/symtab.c:symtab_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584358292,
      "name": "hashtab_insert",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:61",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:range_read"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584349920,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum, struct hashtab_key_params key_params)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584959592,
      "name": "hashtab_insert",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:61",
      "file": "security/selinux/ss/symtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/symtab.c:symtab_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584980340,
      "name": "hashtab_insert",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:61",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:range_read"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584972528,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum, struct hashtab_key_params key_params)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585672728,
      "name": "hashtab_insert",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:61",
      "file": "security/selinux/ss/symtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/symtab.c:symtab_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585695817,
      "name": "hashtab_insert",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:61",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:range_read"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585687024,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum, struct hashtab_key_params key_params)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585902488,
      "name": "hashtab_insert",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:61",
      "file": "security/selinux/ss/symtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/symtab.c:symtab_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585931180,
      "name": "hashtab_insert",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:61",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:range_read"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585917280,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum, struct hashtab_key_params key_params)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586150808,
      "name": "hashtab_insert",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:62",
      "file": "security/selinux/ss/symtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/symtab.c:symtab_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586179695,
      "name": "hashtab_insert",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:62",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:range_read"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586165120,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495242960,
      "name": "hashtab_insert",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:42",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495242960,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228624752,
      "name": "hashtab_insert",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:42",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228624752,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289209488,
      "name": "hashtab_insert",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:42",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289209488,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274468856,
      "name": "hashtab_insert",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:42",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274468856,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583446864,
      "name": "hashtab_insert",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:42",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446864,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583383936,
      "name": "hashtab_insert",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:42",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583383936,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583430640,
      "name": "hashtab_insert",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:42",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583430640,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int hashtab_insert(struct hashtab * h, void * key, void * datum)
```

```json
{
  "name": "hashtab_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583526912,
      "name": "hashtab_insert",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:42",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583526912,
      "name": "hashtab_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct hashtab_key_params key_params</code>
</li>
</ul>
</details>
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
