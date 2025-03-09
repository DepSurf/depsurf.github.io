# Function: <code>alloc_huge_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580797056,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1836",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_huge_page_noerr",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_fault",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580797056,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1242
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580920560,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1883",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:alloc_huge_page_noerr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920560,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1277
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580988912,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1989",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:alloc_huge_page_noerr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580988912,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1277
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581035680,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1969",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:alloc_huge_page_noerr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581035680,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1202
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581145424,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1975",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:alloc_huge_page_noerr",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145424,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1202
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581288736,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1991",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581288736,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1299
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581371648,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1991",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581371648,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1299
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581482480,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2034",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581482480,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1432
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581546896,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2114",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581546896,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1432
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581756880,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2370",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756880,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1200
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581804864,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2320",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804864,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1196
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581832416,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2463",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832416,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1593
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2742",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592212291,
      "name": "alloc_huge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071582121760,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1584
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2853",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593990879,
      "name": "alloc_huge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    },
    {
      "addr": 18446744071582567600,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1270
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:3015",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596041652,
      "name": "alloc_huge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071583086320,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1169
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492981320,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2114",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492981320,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1348
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286402304,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2114",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286402304,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1812
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272886438,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2114",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272886438,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 890
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581515632,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2114",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581515632,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1432
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581457824,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2114",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581457824,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1432
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581506944,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2114",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581506944,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1432
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
```

```json
{
  "name": "alloc_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581571984,
      "name": "alloc_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2114",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571984,
      "name": "alloc_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1405
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
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
struct page * alloc_huge_page(struct vm_area_struct * vma, long unsigned int addr, int avoid_reserve)
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
