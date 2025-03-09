# Function: <code>shmem_swapin_page</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int shmem_swapin_page(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_swapin_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581151328,
      "name": "shmem_swapin_page",
      "external": false,
      "loc": "mm/shmem.c:1619",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581151328,
      "name": "shmem_swapin_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1658
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
int shmem_swapin_page(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_swapin_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581209216,
      "name": "shmem_swapin_page",
      "external": false,
      "loc": "mm/shmem.c:1634",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581209216,
      "name": "shmem_swapin_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1621
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
int shmem_swapin_page(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_swapin_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581391568,
      "name": "shmem_swapin_page",
      "external": false,
      "loc": "mm/shmem.c:1638",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581391568,
      "name": "shmem_swapin_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 923
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
int shmem_swapin_page(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_swapin_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581440016,
      "name": "shmem_swapin_page",
      "external": false,
      "loc": "mm/shmem.c:1693",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581440016,
      "name": "shmem_swapin_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 855
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
int shmem_swapin_page(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_swapin_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581460848,
      "name": "shmem_swapin_page",
      "external": false,
      "loc": "mm/shmem.c:1691",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581460848,
      "name": "shmem_swapin_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
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
int shmem_swapin_page(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_swapin_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581713648,
      "name": "shmem_swapin_page",
      "external": false,
      "loc": "mm/shmem.c:1714",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581713648,
      "name": "shmem_swapin_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int shmem_swapin_page(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_swapin_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492594784,
      "name": "shmem_swapin_page",
      "external": false,
      "loc": "mm/shmem.c:1634",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492594784,
      "name": "shmem_swapin_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1880
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
int shmem_swapin_page(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_swapin_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226450172,
      "name": "shmem_swapin_page",
      "external": false,
      "loc": "mm/shmem.c:1634",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226450172,
      "name": "shmem_swapin_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1600
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
int shmem_swapin_page(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_swapin_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285909184,
      "name": "shmem_swapin_page",
      "external": false,
      "loc": "mm/shmem.c:1634",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285909184,
      "name": "shmem_swapin_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2304
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
int shmem_swapin_page(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_swapin_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272627526,
      "name": "shmem_swapin_page",
      "external": false,
      "loc": "mm/shmem.c:1634",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272627526,
      "name": "shmem_swapin_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1450
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
int shmem_swapin_page(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_swapin_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581178064,
      "name": "shmem_swapin_page",
      "external": false,
      "loc": "mm/shmem.c:1634",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581178064,
      "name": "shmem_swapin_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1621
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
int shmem_swapin_page(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_swapin_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581124864,
      "name": "shmem_swapin_page",
      "external": false,
      "loc": "mm/shmem.c:1634",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581124864,
      "name": "shmem_swapin_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1589
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
int shmem_swapin_page(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_swapin_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581169264,
      "name": "shmem_swapin_page",
      "external": false,
      "loc": "mm/shmem.c:1634",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581169264,
      "name": "shmem_swapin_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1621
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
int shmem_swapin_page(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, vm_fault_t * fault_type)
```

```json
{
  "name": "shmem_swapin_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581232048,
      "name": "shmem_swapin_page",
      "external": false,
      "loc": "mm/shmem.c:1634",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581232048,
      "name": "shmem_swapin_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1879
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int shmem_swapin_page(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, vm_fault_t * fault_type)
```
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int shmem_swapin_page(struct inode * inode, long unsigned int index, struct page * * pagep, enum sgp_type sgp, gfp_t gfp, struct vm_area_struct * vma, vm_fault_t * fault_type)
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
