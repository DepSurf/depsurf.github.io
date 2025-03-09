# Function: <code>hugetlb_acct_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int hugetlb_acct_memory(struct hstate * h, long int delta)
```

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580791664,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:2920",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugepage_subpool_put_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:hugepage_new_subpool",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_unreserve_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580791664,
      "name": "hugetlb_acct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
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
int hugetlb_acct_memory(struct hstate * h, long int delta)
```

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580915136,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:2947",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_subpool_put_pages",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915136,
      "name": "hugetlb_acct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 898
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
int hugetlb_acct_memory(struct hstate * h, long int delta)
```

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580982992,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:3053",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_subpool_put_pages",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580982992,
      "name": "hugetlb_acct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 848
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
int hugetlb_acct_memory(struct hstate * h, long int delta)
```

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581029360,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:3036",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029360,
      "name": "hugetlb_acct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 812
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
int hugetlb_acct_memory(struct hstate * h, long int delta)
```

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581138880,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:3044",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581138880,
      "name": "hugetlb_acct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 878
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
int hugetlb_acct_memory(struct hstate * h, long int delta)
```

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581283280,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:3059",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581283280,
      "name": "hugetlb_acct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 878
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
int hugetlb_acct_memory(struct hstate * h, long int delta)
```

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581365008,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:3053",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581365008,
      "name": "hugetlb_acct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 878
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
int hugetlb_acct_memory(struct hstate * h, long int delta)
```

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581478256,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:3121",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581478256,
      "name": "hugetlb_acct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
int hugetlb_acct_memory(struct hstate * h, long int delta)
```

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581542544,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:3238",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581542544,
      "name": "hugetlb_acct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
int hugetlb_acct_memory(struct hstate * h, long int delta)
```

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581752880,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:3649",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581752880,
      "name": "hugetlb_acct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int hugetlb_acct_memory(struct hstate * h, long int delta)
```

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581801088,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:3613",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581801088,
      "name": "hugetlb_acct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581838170,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:3781",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828432,
      "name": "hugetlb_acct_memory.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582129001,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:4067",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582118656,
      "name": "hugetlb_acct_memory.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582575719,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:4519",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582563632,
      "name": "hugetlb_acct_memory.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583094583,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:4716",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583077776,
      "name": "hugetlb_acct_memory.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583304423,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:4791",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583288304,
      "name": "hugetlb_acct_memory.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583542295,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:5049",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583527792,
      "name": "hugetlb_acct_memory.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
int hugetlb_acct_memory(struct hstate * h, long int delta)
```

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492974480,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:3238",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492974480,
      "name": "hugetlb_acct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int hugetlb_acct_memory(struct hstate * h, long int delta)
```

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286394048,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:3238",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286394048,
      "name": "hugetlb_acct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1656
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
int hugetlb_acct_memory(struct hstate * h, long int delta)
```

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272881250,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:3238",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272881250,
      "name": "hugetlb_acct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 798
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
int hugetlb_acct_memory(struct hstate * h, long int delta)
```

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581511280,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:3238",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581511280,
      "name": "hugetlb_acct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
int hugetlb_acct_memory(struct hstate * h, long int delta)
```

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581453472,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:3238",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581453472,
      "name": "hugetlb_acct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
int hugetlb_acct_memory(struct hstate * h, long int delta)
```

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581502592,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:3238",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581502592,
      "name": "hugetlb_acct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
int hugetlb_acct_memory(struct hstate * h, long int delta)
```

```json
{
  "name": "hugetlb_acct_memory",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581567536,
      "name": "hugetlb_acct_memory",
      "external": false,
      "loc": "mm/hugetlb.c:3238",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_fix_reserve_counts",
        "mm/hugetlb.c:hugepage_put_subpool",
        "mm/hugetlb.c:hugepage_new_subpool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581567536,
      "name": "hugetlb_acct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 921
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int hugetlb_acct_memory(struct hstate * h, long int delta)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int hugetlb_acct_memory(struct hstate * h, long int delta)
```
</details>
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
