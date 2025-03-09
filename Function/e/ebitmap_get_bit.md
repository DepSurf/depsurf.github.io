# Function: <code>ebitmap_get_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582309136,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:239",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_policycap_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582309136,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582530336,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:239",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582530336,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582623136,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:239",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582623136,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582714432,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:241",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582714432,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582870320,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:242",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582870320,
      "name": "ebitmap_get_bit",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583068480,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:242",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583068480,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583181968,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:242",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583181968,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583369408,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:242",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583369408,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583475360,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:242",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583475360,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583821434,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:261",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_and"
      ],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583819552,
      "name": "ebitmap_get_bit.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071583820816,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583942810,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:261",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_and"
      ],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583940928,
      "name": "ebitmap_get_bit.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071583942192,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583969738,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:261",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_and"
      ],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583967872,
      "name": "ebitmap_get_bit.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071583969120,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584335242,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:261",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_and"
      ],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584332864,
      "name": "ebitmap_get_bit.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071584334448,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584956123,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:261",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_and"
      ],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584953520,
      "name": "ebitmap_get_bit.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071584955296,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int ebitmap_get_bit(const struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585669035,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:262",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_and"
      ],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585666304,
      "name": "ebitmap_get_bit.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071585668176,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int ebitmap_get_bit(const struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585898795,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:262",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_and"
      ],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585896112,
      "name": "ebitmap_get_bit.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071585897984,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int ebitmap_get_bit(const struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586147259,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:262",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_and"
      ],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_load_isids",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586144576,
      "name": "ebitmap_get_bit.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    },
    {
      "addr": 18446744071586146448,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495239952,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:242",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495239952,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228621696,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:242",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval",
        "security/selinux/ss/services.c:constraint_expr_eval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228621696,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289205552,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:242",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289205552,
      "name": "ebitmap_get_bit",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274465832,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:242",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274465832,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583444096,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:242",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583444096,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583381168,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:242",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583381168,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583427872,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:242",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583427872,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int ebitmap_get_bit(struct ebitmap * e, long unsigned int bit)
```

```json
{
  "name": "ebitmap_get_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583524144,
      "name": "ebitmap_get_bit",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:242",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/policydb.c:policydb_context_isvalid",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_load_policycaps",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583524144,
      "name": "ebitmap_get_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
<code>struct ebitmap * e</code> ➡️ <code>const struct ebitmap * e</code>
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
