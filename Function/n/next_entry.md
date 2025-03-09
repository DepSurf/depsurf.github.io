# Function: <code>next_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581487486,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:377",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582309828,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:337",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582317129,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:337",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582320177,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:337",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582362262,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:337",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list"
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
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581672278,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:377",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582531025,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:337",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582539737,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:337",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582553116,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:337",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582585362,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:337",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
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
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581760376,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:377",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582623825,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:337",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582632553,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:337",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582645980,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:337",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582678594,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:337",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void next_entry(struct ctl_table_header * * phead, struct ctl_table * * pentry)
```

```json
{
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581814911,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:408",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582715700,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582724521,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582738109,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 18446744071582771206,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582725904,
      "name": "next_entry",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void next_entry(struct ctl_table_header * * phead, struct ctl_table * * pentry)
```

```json
{
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581964470,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:409",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582871588,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582880505,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582894109,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 18446744071582927270,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582881888,
      "name": "next_entry",
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
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582150594,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:409",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583069812,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583078373,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583091911,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 18446744071583127125,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583080128,
      "name": "next_entry.isra.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582245266,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:409",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583183300,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583193893,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583209883,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 18446744071583243285,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:348",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583195568,
      "name": "next_entry.isra.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582408844,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:414",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583370612,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583380821,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583397484,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 18446744071583430277,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583382752,
      "name": "next_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582507804,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:414",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583476564,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583486709,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583503372,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 18446744071583536181,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583488640,
      "name": "next_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void next_entry(struct ctl_table_header * * phead, struct ctl_table * * pentry)
```

```json
{
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582812678,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:382",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583821748,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:349",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583832805,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:349",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583852366,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:349",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:context_read_and_validate",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 18446744071583886133,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:349",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_node",
        "security/selinux/ss/conditional.c:cond_read_node",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583834992,
      "name": "next_entry",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void next_entry(struct ctl_table_header * * phead, struct ctl_table * * pentry)
```

```json
{
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582886390,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:383",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583943124,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583954722,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583975302,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:context_read_and_validate",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 18446744071584006005,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_node",
        "security/selinux/ss/conditional.c:cond_read_node",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583956656,
      "name": "next_entry",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void next_entry(struct ctl_table_header * * phead, struct ctl_table * * pentry)
```

```json
{
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582914056,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:378",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583970068,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583981602,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584002386,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:context_read_and_validate",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 18446744071584033157,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583983408,
      "name": "next_entry",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void next_entry(struct ctl_table_header * * phead, struct ctl_table * * pentry)
```

```json
{
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583248633,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:378",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584335572,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584348290,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584369562,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:context_read_and_validate",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 18446744071584404373,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584350144,
      "name": "next_entry",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void next_entry(struct ctl_table_header * * phead, struct ctl_table * * pentry)
```

```json
{
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583747753,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:403",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584956503,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584970194,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584994703,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:context_read_and_validate",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 18446744071585031045,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584972784,
      "name": "next_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void next_entry(struct ctl_table_header * * phead, struct ctl_table * * pentry)
```

```json
{
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584363257,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:396",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585669431,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585684276,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585710736,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:filename_trans_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:context_read_and_validate",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 18446744071585749445,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585687296,
      "name": "next_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void next_entry(struct ctl_table_header * * phead, struct ctl_table * * pentry)
```

```json
{
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584593740,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:390",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585899191,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585914516,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585940992,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:filename_trans_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:context_read_and_validate",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 18446744071585980117,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585917552,
      "name": "next_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void next_entry(struct ctl_table_header * * phead, struct ctl_table * * pentry)
```

```json
{
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584825340,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:392",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586147655,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586162500,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586189653,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:filename_trans_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:range_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:context_read_and_validate",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 18446744071586227445,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:358",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586165392,
      "name": "next_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494135440,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:414",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495241372,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495252608,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495270828,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 18446603336495306952,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495254648,
      "name": "next_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
void next_entry(struct ctl_table_header * * phead, struct ctl_table * * pentry)
```

```json
{
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227582668,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:414",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 3228623020,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3228634124,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 3228652628,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:ocontext_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 3228685584,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228635984,
      "name": "next_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287810392,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:414",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289207396,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289224052,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289249140,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 13835058055289294248,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289226912,
      "name": "next_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273615792,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:414",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274467014,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274477424,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274494474,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:context_read_and_validate",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274524414,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
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
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582476540,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:414",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583445300,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583455445,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583472108,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 18446744071583504917,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583457376,
      "name": "next_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582413772,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:414",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583382372,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583392517,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583409180,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 18446744071583441973,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583394448,
      "name": "next_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582467020,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:414",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583429076,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583439221,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583455884,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 18446744071583488693,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583441152,
      "name": "next_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_entry",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582547404,
      "name": "next_entry",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:414",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583525348,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583535477,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/avtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/avtab.c:avtab_read",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item",
        "security/selinux/ss/avtab.c:avtab_read_item"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583552108,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:cat_read",
        "security/selinux/ss/policydb.c:sens_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:type_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:class_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:str_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    },
    {
      "addr": 18446744071583585061,
      "name": "next_entry",
      "external": false,
      "loc": "security/selinux/ss/policydb.h:344",
      "file": "security/selinux/ss/conditional.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_list",
        "security/selinux/ss/conditional.c:cond_read_av_list",
        "security/selinux/ss/conditional.c:cond_read_bool",
        "security/selinux/ss/conditional.c:cond_read_bool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583537408,
      "name": "next_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void next_entry(struct ctl_table_header * * phead, struct ctl_table * * pentry)
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
void next_entry(struct ctl_table_header * * phead, struct ctl_table * * pentry)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void next_entry(struct ctl_table_header * * phead, struct ctl_table * * pentry)
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void next_entry(struct ctl_table_header * * phead, struct ctl_table * * pentry)
```
</details>
</li>
</ul>
