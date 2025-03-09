# Function: <code>ebitmap_contains</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582308944,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:198",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/mls.c:mls_level_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582308944,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582530112,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:198",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582530112,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582622912,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:198",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582622912,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582714224,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:200",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582714224,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582870032,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:201",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582870032,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583068208,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:201",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583068208,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583181696,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:201",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583181696,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583369232,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:201",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583369232,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583475184,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:201",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583475184,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583820624,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:220",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583820624,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583942000,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:220",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583942000,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583968944,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:220",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583968944,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584334048,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:220",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584334048,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584954816,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:220",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584954816,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int ebitmap_contains(const struct ebitmap * e1, const struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585667680,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:221",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585667680,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int ebitmap_contains(const struct ebitmap * e1, const struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585897504,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:221",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585897504,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int ebitmap_contains(const struct ebitmap * e1, const struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586145968,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:221",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586145968,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495239688,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:201",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495239688,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228621456,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:201",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228621456,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289205232,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:201",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289205232,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274465534,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:201",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274465534,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583443920,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:201",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583443920,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583380992,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:201",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583380992,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583427696,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:201",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583427696,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int ebitmap_contains(struct ebitmap * e1, struct ebitmap * e2, u32 last_e2bit)
```

```json
{
  "name": "ebitmap_contains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583523968,
      "name": "ebitmap_contains",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:201",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_setup_user_range",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_context_isvalid",
        "security/selinux/ss/mls.c:mls_range_isvalid",
        "security/selinux/ss/mls.c:mls_level_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583523968,
      "name": "ebitmap_contains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ebitmap * e1</code> ➡️ <code>const struct ebitmap * e1</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct ebitmap * e2</code> ➡️ <code>const struct ebitmap * e2</code>
</li>
</ul>
</details>
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
