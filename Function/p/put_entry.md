# Function: <code>put_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582310777,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582318797,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582321063,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582362525,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582532277,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582540261,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582558423,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582586216,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582625093,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582633077,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582651623,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582679448,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int put_entry(const void * buf, size_t bytes, int num, struct policy_file * fp)
```

```json
{
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582716999,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:359",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582725048,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:359",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582743607,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:359",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write"
      ]
    },
    {
      "addr": 18446744071582772059,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:359",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582725952,
      "name": "put_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int put_entry(const void * buf, size_t bytes, int num, struct policy_file * fp)
```

```json
{
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582872887,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:359",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582881032,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:359",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582899623,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:359",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write"
      ]
    },
    {
      "addr": 18446744071582928123,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:359",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582881936,
      "name": "put_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583071053,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:359",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583078824,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:359",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583094456,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:359",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write"
      ]
    },
    {
      "addr": 18446744071583127943,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:359",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583080192,
      "name": "put_entry.isra.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583184541,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:359",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583194344,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:359",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583214170,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:359",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583244103,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:359",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
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
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583371723,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583381259,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583401098,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583431031,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
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
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583477675,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583487147,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583506986,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583536935,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583822945,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:360",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583833243,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:360",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583855644,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:360",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:role_trans_write_one",
        "security/selinux/ss/policydb.c:role_trans_write_one",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583886619,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:360",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_node",
        "security/selinux/ss/conditional.c:cond_write_node",
        "security/selinux/ss/conditional.c:cond_write_node",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583944321,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583955147,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583978684,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:role_trans_write_one",
        "security/selinux/ss/policydb.c:role_trans_write_one",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584006491,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_node",
        "security/selinux/ss/conditional.c:cond_write_node",
        "security/selinux/ss/conditional.c:cond_write_node",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
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
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583971325,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583982043,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584005641,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:role_trans_write_one",
        "security/selinux/ss/policydb.c:role_trans_write_one",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584033947,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
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
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584336875,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584348779,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584373730,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:role_trans_write_one",
        "security/selinux/ss/policydb.c:role_trans_write_one",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584405035,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int put_entry(const void * buf, size_t bytes, int num, struct policy_file * fp)
```

```json
{
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584957874,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584970829,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584998234,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:role_trans_write_one",
        "security/selinux/ss/policydb.c:role_trans_write_one",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write"
      ]
    },
    {
      "addr": 18446744071585031776,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584972864,
      "name": "put_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
int put_entry(const void * buf, size_t bytes, int num, struct policy_file * fp)
```

```json
{
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585670863,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585684941,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item"
      ],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item"
      ]
    },
    {
      "addr": 18446744071585714023,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:role_trans_write_one",
        "security/selinux/ss/policydb.c:role_trans_write_one",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper"
      ]
    },
    {
      "addr": 18446744071585750192,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool"
      ],
      "caller_func": [
        "security/selinux/ss/conditional.c:cond_write_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585679760,
      "name": "put_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071585687392,
      "name": "put_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071585746224,
      "name": "put_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate ❓</summary>

```c
int put_entry(const void * buf, size_t bytes, int num, struct policy_file * fp)
```

```json
{
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585895520,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ]
    },
    {
      "addr": 18446744071585910016,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/avtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item"
      ]
    },
    {
      "addr": 18446744071585917648,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:role_trans_write_one",
        "security/selinux/ss/policydb.c:role_trans_write_one",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper"
      ]
    },
    {
      "addr": 18446744071585976912,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/conditional.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585895520,
      "name": "put_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071585910016,
      "name": "put_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071585917648,
      "name": "put_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071585976912,
      "name": "put_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate ❓</summary>

```c
int put_entry(const void * buf, size_t bytes, size_t num, struct policy_file * fp)
```

```json
{
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586144032,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ]
    },
    {
      "addr": 18446744071586158592,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/avtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item"
      ]
    },
    {
      "addr": 18446744071586165488,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:filename_write_helper_compat",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:role_trans_write_one",
        "security/selinux/ss/policydb.c:role_trans_write_one",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper"
      ]
    },
    {
      "addr": 18446744071586224176,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:369",
      "file": "security/selinux/ss/conditional.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586144032,
      "name": "put_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071586158592,
      "name": "put_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071586165488,
      "name": "put_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071586224176,
      "name": "put_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495242560,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495253212,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495273956,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495307812,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
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
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228624344,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3228634804,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3228656292,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:genfs_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:ocontext_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:write_cons_helper",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3228686508,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
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
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289208944,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289224804,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289253084,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289295380,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274468374,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274478012,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274498842,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper",
        "security/selinux/ss/policydb.c:mls_write_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274525324,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583446411,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583455883,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583475722,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583505671,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
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
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583383483,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583392955,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583412794,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583442727,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
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
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583430187,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583439659,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583459498,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583489447,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
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
  "name": "put_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583526459,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write",
        "security/selinux/ss/ebitmap.c:ebitmap_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583535915,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_write",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item",
        "security/selinux/ss/avtab.c:avtab_write_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583555722,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:filename_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:range_write_helper",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:type_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:role_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:perm_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:cat_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:mls_write_range_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583585815,
      "name": "put_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:355",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_list",
        "security/selinux/ss/conditional.c:cond_write_bool",
        "security/selinux/ss/conditional.c:cond_write_bool"
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int put_entry(const void * buf, size_t bytes, int num, struct policy_file * fp)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int put_entry(const void * buf, size_t bytes, int num, struct policy_file * fp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int put_entry(const void * buf, size_t bytes, int num, struct policy_file * fp)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int num</code> ➡️ <code>size_t num</code>
</li>
</ul>
</details>
</li>
</ul>
