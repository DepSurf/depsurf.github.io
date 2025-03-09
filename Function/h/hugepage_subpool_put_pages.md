# Function: <code>hugepage_subpool_put_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int hugepage_subpool_put_pages(struct hugepage_subpool * spool, long int delta)
```

```json
{
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580792480,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:173",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:free_huge_page",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_unreserve_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580792480,
      "name": "hugepage_subpool_put_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
long int hugepage_subpool_put_pages(struct hugepage_subpool * spool, long int delta)
```

```json
{
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916048,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:174",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916048,
      "name": "hugepage_subpool_put_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
long int hugepage_subpool_put_pages(struct hugepage_subpool * spool, long int delta)
```

```json
{
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580983840,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:174",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580983840,
      "name": "hugepage_subpool_put_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581039698,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:176",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581030176,
      "name": "hugepage_subpool_put_pages.part.54",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581149618,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:177",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139760,
      "name": "hugepage_subpool_put_pages.part.63",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581293093,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:176",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581284160,
      "name": "hugepage_subpool_put_pages.part.69",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581376005,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:176",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581365888,
      "name": "hugepage_subpool_put_pages.part.69",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581486902,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:178",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581479152,
      "name": "hugepage_subpool_put_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581551318,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:179",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581543440,
      "name": "hugepage_subpool_put_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581761702,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:185",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581753136,
      "name": "hugepage_subpool_put_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581809766,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:202",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581801232,
      "name": "hugepage_subpool_put_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581838151,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:199",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828800,
      "name": "hugepage_subpool_put_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582128982,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:201",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582119168,
      "name": "hugepage_subpool_put_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582575703,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:215",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582564176,
      "name": "hugepage_subpool_put_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583094567,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:215",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583078400,
      "name": "hugepage_subpool_put_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583304407,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:215",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583288928,
      "name": "hugepage_subpool_put_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583542279,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:217",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:free_huge_folio"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:free_huge_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583528464,
      "name": "hugepage_subpool_put_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492987468,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:179",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492975640,
      "name": "hugepage_subpool_put_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286424300,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:179",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286395712,
      "name": "hugepage_subpool_put_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272890340,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:179",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272882048,
      "name": "hugepage_subpool_put_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581520054,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:179",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581512176,
      "name": "hugepage_subpool_put_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581462214,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:179",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581454368,
      "name": "hugepage_subpool_put_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581511366,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:179",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503488,
      "name": "hugepage_subpool_put_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
  "name": "hugepage_subpool_put_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581576420,
      "name": "hugepage_subpool_put_pages",
      "external": false,
      "loc": "mm/hugetlb.c:179",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unreserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_vm_op_close",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581568464,
      "name": "hugepage_subpool_put_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
long int hugepage_subpool_put_pages(struct hugepage_subpool * spool, long int delta)
```
</details>
</li>
</ul>
