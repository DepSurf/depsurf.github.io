# Function: <code>hashtab_search</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * hashtab_search(struct hashtab * h, const void * key)
```

```json
{
  "name": "hashtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582311760,
      "name": "hashtab_search",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:77",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/mls.c:mls_level_isvalid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582311760,
      "name": "hashtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void * hashtab_search(struct hashtab * h, const void * key)
```

```json
{
  "name": "hashtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582532928,
      "name": "hashtab_search",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:77",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582532928,
      "name": "hashtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void * hashtab_search(struct hashtab * h, const void * key)
```

```json
{
  "name": "hashtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582625744,
      "name": "hashtab_search",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:77",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582625744,
      "name": "hashtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void * hashtab_search(struct hashtab * h, const void * key)
```

```json
{
  "name": "hashtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582717664,
      "name": "hashtab_search",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:77",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582717664,
      "name": "hashtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void * hashtab_search(struct hashtab * h, const void * key)
```

```json
{
  "name": "hashtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582873536,
      "name": "hashtab_search",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:80",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582873536,
      "name": "hashtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void * hashtab_search(struct hashtab * h, const void * key)
```

```json
{
  "name": "hashtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583071792,
      "name": "hashtab_search",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:80",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583071792,
      "name": "hashtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void * hashtab_search(struct hashtab * h, const void * key)
```

```json
{
  "name": "hashtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583185296,
      "name": "hashtab_search",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:80",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583185296,
      "name": "hashtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void * hashtab_search(struct hashtab * h, const void * key)
```

```json
{
  "name": "hashtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583372528,
      "name": "hashtab_search",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:80",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583372528,
      "name": "hashtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void * hashtab_search(struct hashtab * h, const void * key)
```

```json
{
  "name": "hashtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583478480,
      "name": "hashtab_search",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:80",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583478480,
      "name": "hashtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void * hashtab_search(struct hashtab * h, const void * key)
```

```json
{
  "name": "hashtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583823936,
      "name": "hashtab_search",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:87",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_preserve_bools",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_range_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583823936,
      "name": "hashtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hashtab_search",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583945989,
      "name": "hashtab_search",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:96",
      "file": "security/selinux/ss/symtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/symtab.c:symtab_search"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583967784,
      "name": "hashtab_search",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:96",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:policydb_roletr_search",
        "security/selinux/ss/policydb.c:policydb_rangetr_search"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hashtab_search",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583972981,
      "name": "hashtab_search",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:96",
      "file": "security/selinux/ss/symtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/symtab.c:symtab_search"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583994840,
      "name": "hashtab_search",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:96",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:policydb_roletr_search",
        "security/selinux/ss/policydb.c:policydb_rangetr_search"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hashtab_search",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584338581,
      "name": "hashtab_search",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:96",
      "file": "security/selinux/ss/symtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/symtab.c:symtab_search"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584361800,
      "name": "hashtab_search",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:96",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:policydb_roletr_search",
        "security/selinux/ss/policydb.c:policydb_rangetr_search"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hashtab_search",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584959813,
      "name": "hashtab_search",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:96",
      "file": "security/selinux/ss/symtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/symtab.c:symtab_search"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584987063,
      "name": "hashtab_search",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:96",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:policydb_roletr_search",
        "security/selinux/ss/policydb.c:policydb_rangetr_search"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hashtab_search",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585672965,
      "name": "hashtab_search",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:96",
      "file": "security/selinux/ss/symtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/symtab.c:symtab_search"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585703127,
      "name": "hashtab_search",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:96",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:policydb_roletr_search",
        "security/selinux/ss/policydb.c:policydb_rangetr_search"
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
  "name": "hashtab_search",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585902725,
      "name": "hashtab_search",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:96",
      "file": "security/selinux/ss/symtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/symtab.c:symtab_search"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585933462,
      "name": "hashtab_search",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:96",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:policydb_roletr_search",
        "security/selinux/ss/policydb.c:policydb_rangetr_search"
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
  "name": "hashtab_search",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586151045,
      "name": "hashtab_search",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:97",
      "file": "security/selinux/ss/symtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/symtab.c:symtab_search"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586182156,
      "name": "hashtab_search",
      "external": false,
      "loc": "security/selinux/ss/hashtab.h:97",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:policydb_roletr_search",
        "security/selinux/ss/policydb.c:policydb_rangetr_search"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * hashtab_search(struct hashtab * h, const void * key)
```

```json
{
  "name": "hashtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495243304,
      "name": "hashtab_search",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:80",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495243304,
      "name": "hashtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void * hashtab_search(struct hashtab * h, const void * key)
```

```json
{
  "name": "hashtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228625112,
      "name": "hashtab_search",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:80",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:string_to_av_perm",
        "security/selinux/ss/policydb.c:string_to_av_perm",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228625112,
      "name": "hashtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void * hashtab_search(struct hashtab * h, const void * key)
```

```json
{
  "name": "hashtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289210000,
      "name": "hashtab_search",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:80",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289210000,
      "name": "hashtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void * hashtab_search(struct hashtab * h, const void * key)
```

```json
{
  "name": "hashtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274469158,
      "name": "hashtab_search",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:80",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274469158,
      "name": "hashtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void * hashtab_search(struct hashtab * h, const void * key)
```

```json
{
  "name": "hashtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583447216,
      "name": "hashtab_search",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:80",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583447216,
      "name": "hashtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void * hashtab_search(struct hashtab * h, const void * key)
```

```json
{
  "name": "hashtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583384288,
      "name": "hashtab_search",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:80",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583384288,
      "name": "hashtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void * hashtab_search(struct hashtab * h, const void * key)
```

```json
{
  "name": "hashtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583430992,
      "name": "hashtab_search",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:80",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583430992,
      "name": "hashtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void * hashtab_search(struct hashtab * h, const void * key)
```

```json
{
  "name": "hashtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583527264,
      "name": "hashtab_search",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:80",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583527264,
      "name": "hashtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void * hashtab_search(struct hashtab * h, const void * key)
```
</details>
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
