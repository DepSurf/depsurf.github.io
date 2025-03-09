# Function: <code>ebitmap_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582308288,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:324",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_cpy",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_insert",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:sens_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/policydb.c:constraint_expr_destroy",
        "security/selinux/ss/policydb.c:constraint_expr_destroy",
        "security/selinux/ss/policydb.c:constraint_expr_destroy",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:ocontext_destroy",
        "security/selinux/ss/policydb.c:ocontext_destroy",
        "security/selinux/ss/policydb.c:ocontext_destroy",
        "security/selinux/ss/policydb.c:ocontext_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582309728,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582531482,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:324",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_insert",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:ocontext_destroy",
        "security/selinux/ss/policydb.c:ocontext_destroy",
        "security/selinux/ss/policydb.c:ocontext_destroy",
        "security/selinux/ss/policydb.c:ocontext_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:sens_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/policydb.c:constraint_expr_destroy",
        "security/selinux/ss/policydb.c:constraint_expr_destroy",
        "security/selinux/ss/policydb.c:constraint_expr_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582530928,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582624282,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:324",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_insert",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:ocontext_destroy",
        "security/selinux/ss/policydb.c:ocontext_destroy",
        "security/selinux/ss/policydb.c:ocontext_destroy",
        "security/selinux/ss/policydb.c:ocontext_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:sens_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/policydb.c:constraint_expr_destroy",
        "security/selinux/ss/policydb.c:constraint_expr_destroy",
        "security/selinux/ss/policydb.c:constraint_expr_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582623728,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582715040,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:326",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_insert",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:sens_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_cpy_high"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582715040,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582870928,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:327",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_insert",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:sens_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_cpy_high"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582870928,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583069120,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:327",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_insert",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:sens_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583069120,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583182608,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:327",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:sens_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583182608,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583369968,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:327",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:sens_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583369968,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583475920,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:327",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:sens_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583475920,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583822253,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:346",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:filenametr_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583821616,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583943629,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:346",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:filenametr_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583942992,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583970570,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:346",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:filenametr_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583969936,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584336084,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:346",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:filenametr_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584335440,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584957031,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:346",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:filenametr_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584956336,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585669917,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:347",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:context_read_and_validate",
        "security/selinux/ss/policydb.c:context_read_and_validate",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:filenametr_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:services_convert_context",
        "security/selinux/ss/services.c:services_convert_context",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585669248,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585899677,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:347",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:context_read_and_validate",
        "security/selinux/ss/policydb.c:context_read_and_validate",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:filenametr_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:services_convert_context",
        "security/selinux/ss/services.c:services_convert_context",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585899008,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586148141,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:347",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:context_read_and_validate",
        "security/selinux/ss/policydb.c:context_read_and_validate",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:filenametr_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:services_convert_context",
        "security/selinux/ss/services.c:services_convert_context",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586147472,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495240648,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:327",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:sens_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495240648,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228622304,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:327",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:sens_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228622304,
      "name": "ebitmap_destroy",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289206416,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:327",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:sens_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289206416,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274466366,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:327",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:sens_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274466366,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583444656,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:327",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:sens_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583444656,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583381728,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:327",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:sens_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583381728,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583428432,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:327",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:sens_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583428432,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void ebitmap_destroy(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583524704,
      "name": "ebitmap_destroy",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:327",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_netlbl_import",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_destroy_tree",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:range_tr_destroy",
        "security/selinux/ss/policydb.c:sens_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:user_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/policydb.c:role_destroy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_import_netlbl_cat",
        "security/selinux/ss/mls.c:mls_compute_sid",
        "security/selinux/ss/mls.c:mls_compute_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583524704,
      "name": "ebitmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
