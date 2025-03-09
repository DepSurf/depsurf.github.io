# Function: <code>context_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void context_destroy(struct context * c)
```

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582314366,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:141",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582325964,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:141",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:ocontext_destroy",
        "security/selinux/ss/policydb.c:ocontext_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582341616,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:141",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:selinux_audit_rule_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582341616,
      "name": "context_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void context_destroy(struct context * c)
```

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582535582,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:141",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582547148,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:141",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:ocontext_destroy",
        "security/selinux/ss/policydb.c:ocontext_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582581407,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:141",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582562064,
      "name": "context_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void context_destroy(struct context * c)
```

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582628398,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:141",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582639996,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:141",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:ocontext_destroy",
        "security/selinux/ss/policydb.c:ocontext_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582674623,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:141",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582655264,
      "name": "context_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void context_destroy(struct context * c)
```

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582720382,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:141",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582728291,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:141",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582767323,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:141",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582747824,
      "name": "context_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void context_destroy(struct context * c)
```

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582876350,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582884275,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582923345,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582903840,
      "name": "context_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void context_destroy(struct context * c)
```

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583074522,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583081909,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583121951,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583101808,
      "name": "context_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583190115,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583197669,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583238035,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583377491,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583383909,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583424813,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583483379,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583489797,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583530717,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void context_destroy(struct context * c)
```

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583829112,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:174",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583848782,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:174",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:context_read_and_validate"
      ]
    },
    {
      "addr": 18446744071583880031,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:174",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:convert_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583834752,
      "name": "context_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071583857952,
      "name": "context_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void context_destroy(struct context * c)
```

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583950648,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:174",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583971742,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:174",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:context_read_and_validate"
      ]
    },
    {
      "addr": 18446744071584000687,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:174",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:convert_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583956192,
      "name": "context_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071583979888,
      "name": "context_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void context_destroy(struct context * c)
```

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583977739,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:174",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583998814,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:174",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:context_read_and_validate"
      ]
    },
    {
      "addr": 18446744071584028431,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:174",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:convert_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583983776,
      "name": "context_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071584008496,
      "name": "context_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void context_destroy(struct context * c)
```

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584344020,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:174",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584365839,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:174",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:context_read_and_validate"
      ]
    },
    {
      "addr": 18446744071584398752,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:174",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:convert_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584350512,
      "name": "context_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071584377136,
      "name": "context_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void context_destroy(struct context * c)
```

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584965076,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:174",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584990704,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:174",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:context_read_and_validate"
      ]
    },
    {
      "addr": 18446744071585024992,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:174",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:convert_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584973136,
      "name": "context_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446744071585001472,
      "name": "context_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585678500,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:175",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585707880,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:175",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:context_read_and_validate",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585742848,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:175",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:services_convert_context",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585908756,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:177",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585938136,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:177",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:context_read_and_validate",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585973578,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:177",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:services_convert_context",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586157380,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:177",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586186712,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:177",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:context_read_and_validate",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586220203,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:177",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:services_convert_context",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495248612,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495256556,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495300276,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228630224,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 3228637472,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228680788,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289218968,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289229320,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289287632,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
void context_destroy(struct context * c)
```

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274473464,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274479364,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:context_read_and_validate"
      ]
    },
    {
      "addr": 18446743936274520334,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274479364,
      "name": "context_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583452115,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583458533,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583499453,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583389187,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583395605,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583436509,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583435891,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583442309,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583483229,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "context_destroy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583532147,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583538565,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583579595,
      "name": "context_destroy",
      "external": false,
      "loc": "security/selinux/ss/context.h:142",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void context_destroy(struct context * c)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void context_destroy(struct context * c)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void context_destroy(struct context * c)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void context_destroy(struct context * c)
```
</details>
</li>
</ul>
