# Function: <code>shmem_is_huge</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool shmem_is_huge(struct vm_area_struct * vma, struct inode * inode, long unsigned int index)
```

```json
{
  "name": "shmem_is_huge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581716400,
      "name": "shmem_is_huge",
      "external": true,
      "loc": "mm/shmem.c:476",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getattr",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:transparent_hugepage_active",
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716400,
      "name": "shmem_is_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool shmem_is_huge(struct vm_area_struct * vma, struct inode * inode, long unsigned int index)
```

```json
{
  "name": "shmem_is_huge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582093231,
      "name": "shmem_is_huge",
      "external": true,
      "loc": "mm/shmem.c:474",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getattr"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getattr",
        "mm/huge_memory.c:transparent_hugepage_active",
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582080128,
      "name": "shmem_is_huge.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071582106016,
      "name": "shmem_is_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool shmem_is_huge(struct vm_area_struct * vma, struct inode * inode, long unsigned int index, bool shmem_huge_force)
```

```json
{
  "name": "shmem_is_huge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582568688,
      "name": "shmem_is_huge",
      "external": true,
      "loc": "mm/shmem.c:471",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_getattr"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_getattr",
        "mm/huge_memory.c:hugepage_vma_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582555536,
      "name": "shmem_is_huge.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    },
    {
      "addr": 18446744071582580064,
      "name": "shmem_is_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool shmem_is_huge(struct inode * inode, long unsigned int index, bool shmem_huge_force, struct mm_struct * mm, long unsigned int vm_flags)
```

```json
{
  "name": "shmem_is_huge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582775607,
      "name": "shmem_is_huge",
      "external": true,
      "loc": "mm/shmem.c:472",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_getattr"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_getattr",
        "mm/huge_memory.c:hugepage_vma_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582760784,
      "name": "shmem_is_huge.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
    },
    {
      "addr": 18446744071582787248,
      "name": "shmem_is_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool shmem_is_huge(struct inode * inode, long unsigned int index, bool shmem_huge_force, struct mm_struct * mm, long unsigned int vm_flags)
```

```json
{
  "name": "shmem_is_huge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582951792,
      "name": "shmem_is_huge",
      "external": true,
      "loc": "mm/shmem.c:538",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_getattr"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_getattr",
        "mm/huge_memory.c:__thp_vma_allowable_orders"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582935872,
      "name": "shmem_is_huge.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
    },
    {
      "addr": 18446744071582962512,
      "name": "shmem_is_huge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool shmem_is_huge(struct vm_area_struct * vma, struct inode * inode, long unsigned int index)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool shmem_huge_force</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mm_struct * mm</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int vm_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, inode, index, shmem_huge_force</code> ➡️ <code>inode, index, shmem_huge_force, mm, vm_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
