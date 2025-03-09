# Function: <code>symtab_search</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void * symtab_search(struct symtab * s, const char * name)
```

```json
{
  "name": "symtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583945984,
      "name": "symtab_search",
      "external": true,
      "loc": "security/selinux/ss/symtab.c:51",
      "file": "security/selinux/ss/symtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
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
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_range_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583945984,
      "name": "symtab_search",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void * symtab_search(struct symtab * s, const char * name)
```

```json
{
  "name": "symtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583972976,
      "name": "symtab_search",
      "external": true,
      "loc": "security/selinux/ss/symtab.c:51",
      "file": "security/selinux/ss/symtab.c",
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
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_range_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972976,
      "name": "symtab_search",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void * symtab_search(struct symtab * s, const char * name)
```

```json
{
  "name": "symtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584338576,
      "name": "symtab_search",
      "external": true,
      "loc": "security/selinux/ss/symtab.c:51",
      "file": "security/selinux/ss/symtab.c",
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
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_range_isvalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584338576,
      "name": "symtab_search",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void * symtab_search(struct symtab * s, const char * name)
```

```json
{
  "name": "symtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584959808,
      "name": "symtab_search",
      "external": true,
      "loc": "security/selinux/ss/symtab.c:51",
      "file": "security/selinux/ss/symtab.c",
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
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584959808,
      "name": "symtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void * symtab_search(struct symtab * s, const char * name)
```

```json
{
  "name": "symtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585672960,
      "name": "symtab_search",
      "external": true,
      "loc": "security/selinux/ss/symtab.c:51",
      "file": "security/selinux/ss/symtab.c",
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
        "security/selinux/ss/services.c:services_convert_context",
        "security/selinux/ss/services.c:services_convert_context",
        "security/selinux/ss/services.c:services_convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585672960,
      "name": "symtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void * symtab_search(struct symtab * s, const char * name)
```

```json
{
  "name": "symtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585902720,
      "name": "symtab_search",
      "external": true,
      "loc": "security/selinux/ss/symtab.c:51",
      "file": "security/selinux/ss/symtab.c",
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
        "security/selinux/ss/services.c:services_convert_context",
        "security/selinux/ss/services.c:services_convert_context",
        "security/selinux/ss/services.c:services_convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585902720,
      "name": "symtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void * symtab_search(struct symtab * s, const char * name)
```

```json
{
  "name": "symtab_search",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586151040,
      "name": "symtab_search",
      "external": true,
      "loc": "security/selinux/ss/symtab.c:51",
      "file": "security/selinux/ss/symtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:string_to_av_perm",
        "security/selinux/ss/policydb.c:string_to_av_perm",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:services_convert_context",
        "security/selinux/ss/services.c:services_convert_context",
        "security/selinux/ss/services.c:services_convert_context",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid",
        "security/selinux/ss/mls.c:mls_context_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586151040,
      "name": "symtab_search",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void * symtab_search(struct symtab * s, const char * name)
```
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
