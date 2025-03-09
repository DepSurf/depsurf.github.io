# Function: <code>flex_array_get_ptr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * flex_array_get_ptr(struct flex_array * fa, unsigned int element_nr)
```

```json
{
  "name": "flex_array_get_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583018304,
      "name": "flex_array_get_ptr",
      "external": true,
      "loc": "lib/flex_array.c:345",
      "file": "lib/flex_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_insertf",
        "security/selinux/ss/avtab.c:avtab_insert_nonunique",
        "security/selinux/ss/avtab.c:avtab_search",
        "security/selinux/ss/avtab.c:avtab_search_node",
        "security/selinux/ss/avtab.c:avtab_destroy",
        "security/selinux/ss/avtab.c:avtab_hash_eval",
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:type_attribute_bounds_av",
        "security/selinux/ss/services.c:type_attribute_bounds_av",
        "security/selinux/ss/services.c:security_validate_transition",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:security_get_bools",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_level_isvalid",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583018304,
      "name": "flex_array_get_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * flex_array_get_ptr(struct flex_array * fa, unsigned int element_nr)
```

```json
{
  "name": "flex_array_get_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583309664,
      "name": "flex_array_get_ptr",
      "external": true,
      "loc": "lib/flex_array.c:345",
      "file": "lib/flex_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_insertf",
        "security/selinux/ss/avtab.c:avtab_hash_eval",
        "security/selinux/ss/avtab.c:avtab_destroy",
        "security/selinux/ss/avtab.c:avtab_search_node",
        "security/selinux/ss/avtab.c:avtab_search",
        "security/selinux/ss/avtab.c:avtab_insert_nonunique",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_get_bools",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:type_attribute_bounds_av",
        "security/selinux/ss/services.c:type_attribute_bounds_av",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_level_isvalid",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583309664,
      "name": "flex_array_get_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * flex_array_get_ptr(struct flex_array * fa, unsigned int element_nr)
```

```json
{
  "name": "flex_array_get_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583428976,
      "name": "flex_array_get_ptr",
      "external": true,
      "loc": "lib/flex_array.c:345",
      "file": "lib/flex_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_insertf",
        "security/selinux/ss/avtab.c:avtab_hash_eval",
        "security/selinux/ss/avtab.c:avtab_destroy",
        "security/selinux/ss/avtab.c:avtab_search_node",
        "security/selinux/ss/avtab.c:avtab_search",
        "security/selinux/ss/avtab.c:avtab_insert_nonunique",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_get_bools",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:type_attribute_bounds_av",
        "security/selinux/ss/services.c:type_attribute_bounds_av",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_level_isvalid",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583428976,
      "name": "flex_array_get_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * flex_array_get_ptr(struct flex_array * fa, unsigned int element_nr)
```

```json
{
  "name": "flex_array_get_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583450288,
      "name": "flex_array_get_ptr",
      "external": true,
      "loc": "lib/flex_array.c:345",
      "file": "lib/flex_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_insertf",
        "security/selinux/ss/avtab.c:avtab_hash_eval",
        "security/selinux/ss/avtab.c:avtab_search_node",
        "security/selinux/ss/avtab.c:avtab_search",
        "security/selinux/ss/avtab.c:avtab_insert_nonunique",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_get_bools",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:type_attribute_bounds_av",
        "security/selinux/ss/services.c:type_attribute_bounds_av",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_level_isvalid",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583450288,
      "name": "flex_array_get_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * flex_array_get_ptr(struct flex_array * fa, unsigned int element_nr)
```

```json
{
  "name": "flex_array_get_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583630384,
      "name": "flex_array_get_ptr",
      "external": true,
      "loc": "lib/flex_array.c:345",
      "file": "lib/flex_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_insertf",
        "security/selinux/ss/avtab.c:avtab_hash_eval",
        "security/selinux/ss/avtab.c:avtab_search_node",
        "security/selinux/ss/avtab.c:avtab_search",
        "security/selinux/ss/avtab.c:avtab_insert_nonunique",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_get_bools",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:type_attribute_bounds_av",
        "security/selinux/ss/services.c:type_attribute_bounds_av",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_level_isvalid",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583630384,
      "name": "flex_array_get_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * flex_array_get_ptr(struct flex_array * fa, unsigned int element_nr)
```

```json
{
  "name": "flex_array_get_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583846960,
      "name": "flex_array_get_ptr",
      "external": true,
      "loc": "lib/flex_array.c:345",
      "file": "lib/flex_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_insertf",
        "security/selinux/ss/avtab.c:avtab_hash_eval",
        "security/selinux/ss/avtab.c:avtab_search_node",
        "security/selinux/ss/avtab.c:avtab_search",
        "security/selinux/ss/avtab.c:avtab_insert_nonunique",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:type_attribute_bounds_av",
        "security/selinux/ss/services.c:type_attribute_bounds_av",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_level_isvalid",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583846960,
      "name": "flex_array_get_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void * flex_array_get_ptr(struct flex_array * fa, unsigned int element_nr)
```

```json
{
  "name": "flex_array_get_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583930672,
      "name": "flex_array_get_ptr",
      "external": true,
      "loc": "lib/flex_array.c:345",
      "file": "lib/flex_array.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_insertf",
        "security/selinux/ss/avtab.c:avtab_hash_eval",
        "security/selinux/ss/avtab.c:avtab_search_node",
        "security/selinux/ss/avtab.c:avtab_search",
        "security/selinux/ss/avtab.c:avtab_insert_nonunique",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:role_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/policydb.c:user_bounds_sanity_check",
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:convert_context",
        "security/selinux/ss/services.c:compute_sid_handle_invalid_context",
        "security/selinux/ss/services.c:security_bounded_transition",
        "security/selinux/ss/services.c:type_attribute_bounds_av",
        "security/selinux/ss/services.c:type_attribute_bounds_av",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_convert_context",
        "security/selinux/ss/mls.c:mls_level_isvalid",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_sid_to_context",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len",
        "security/selinux/ss/mls.c:mls_compute_context_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583930672,
      "name": "flex_array_get_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void * flex_array_get_ptr(struct flex_array * fa, unsigned int element_nr)
```
</details>
</li>
</ul>
