# Function: <code>huge_node</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```

```json
{
  "name": "huge_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581062304,
      "name": "huge_node",
      "external": true,
      "loc": "mm/mempolicy.c:1741",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581062304,
      "name": "huge_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```

```json
{
  "name": "huge_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581173392,
      "name": "huge_node",
      "external": true,
      "loc": "mm/mempolicy.c:1797",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581173392,
      "name": "huge_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```

```json
{
  "name": "huge_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581318064,
      "name": "huge_node",
      "external": true,
      "loc": "mm/mempolicy.c:1854",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581318064,
      "name": "huge_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```

```json
{
  "name": "huge_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581402224,
      "name": "huge_node",
      "external": true,
      "loc": "mm/mempolicy.c:1894",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581402224,
      "name": "huge_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```

```json
{
  "name": "huge_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581515120,
      "name": "huge_node",
      "external": true,
      "loc": "mm/mempolicy.c:1940",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581515120,
      "name": "huge_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```

```json
{
  "name": "huge_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581579584,
      "name": "huge_node",
      "external": true,
      "loc": "mm/mempolicy.c:1942",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581579584,
      "name": "huge_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```

```json
{
  "name": "huge_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581791472,
      "name": "huge_node",
      "external": true,
      "loc": "mm/mempolicy.c:2039",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:dequeue_huge_page_vma",
        "mm/hugetlb.c:dequeue_huge_page_vma",
        "mm/hugetlb.c:dequeue_huge_page_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581791472,
      "name": "huge_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```

```json
{
  "name": "huge_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581839296,
      "name": "huge_node",
      "external": true,
      "loc": "mm/mempolicy.c:2014",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:dequeue_huge_page_vma",
        "mm/hugetlb.c:dequeue_huge_page_vma",
        "mm/hugetlb.c:dequeue_huge_page_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581839296,
      "name": "huge_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```

```json
{
  "name": "huge_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581870112,
      "name": "huge_node",
      "external": true,
      "loc": "mm/mempolicy.c:2028",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581870112,
      "name": "huge_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```

```json
{
  "name": "huge_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "huge_node",
      "external": true,
      "loc": "mm/mempolicy.c:1934",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592215928,
      "name": "huge_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071582161712,
      "name": "huge_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```

```json
{
  "name": "huge_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "huge_node",
      "external": true,
      "loc": "mm/mempolicy.c:2003",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:dequeue_huge_page_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593994614,
      "name": "huge_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071582617456,
      "name": "huge_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```

```json
{
  "name": "huge_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "huge_node",
      "external": true,
      "loc": "mm/mempolicy.c:2018",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:dequeue_huge_page_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596044811,
      "name": "huge_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071583141360,
      "name": "huge_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```

```json
{
  "name": "huge_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "huge_node",
      "external": true,
      "loc": "mm/mempolicy.c:2029",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio_vma",
        "mm/hugetlb.c:dequeue_hugetlb_folio_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596567245,
      "name": "huge_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071583351488,
      "name": "huge_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```

```json
{
  "name": "huge_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583585856,
      "name": "huge_node",
      "external": true,
      "loc": "mm/mempolicy.c:1973",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:dequeue_hugetlb_folio_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583585856,
      "name": "huge_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```

```json
{
  "name": "huge_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493017248,
      "name": "huge_node",
      "external": true,
      "loc": "mm/mempolicy.c:1942",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493017248,
      "name": "huge_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```

```json
{
  "name": "huge_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286444528,
      "name": "huge_node",
      "external": true,
      "loc": "mm/mempolicy.c:1942",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286444528,
      "name": "huge_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
  "name": "huge_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "huge_node",
      "external": false,
      "loc": "include/linux/mempolicy.h:271",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```

```json
{
  "name": "huge_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581548320,
      "name": "huge_node",
      "external": true,
      "loc": "mm/mempolicy.c:1942",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581548320,
      "name": "huge_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```

```json
{
  "name": "huge_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581489968,
      "name": "huge_node",
      "external": true,
      "loc": "mm/mempolicy.c:1942",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581489968,
      "name": "huge_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```

```json
{
  "name": "huge_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581539632,
      "name": "huge_node",
      "external": true,
      "loc": "mm/mempolicy.c:1942",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581539632,
      "name": "huge_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```

```json
{
  "name": "huge_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581604672,
      "name": "huge_node",
      "external": true,
      "loc": "mm/mempolicy.c:1942",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581604672,
      "name": "huge_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int huge_node(struct vm_area_struct * vma, long unsigned int addr, gfp_t gfp_flags, struct mempolicy * * mpol, nodemask_t * * nodemask)
```
</details>
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
