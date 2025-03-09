# Function: <code>khugepaged_enter_vma</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void khugepaged_enter_vma(struct vm_area_struct * vma, long unsigned int vm_flags)
```

```json
{
  "name": "khugepaged_enter_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582808130,
      "name": "khugepaged_enter_vma",
      "external": true,
      "loc": "mm/khugepaged.c:508",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:hugepage_madvise",
        "mm/khugepaged.c:hugepage_madvise"
      ],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582808256,
      "name": "khugepaged_enter_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void khugepaged_enter_vma(struct vm_area_struct * vma, long unsigned int vm_flags)
```

```json
{
  "name": "khugepaged_enter_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583348736,
      "name": "khugepaged_enter_vma",
      "external": true,
      "loc": "mm/khugepaged.c:450",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:vma_merge",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:hugepage_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583348736,
      "name": "khugepaged_enter_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void khugepaged_enter_vma(struct vm_area_struct * vma, long unsigned int vm_flags)
```

```json
{
  "name": "khugepaged_enter_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583568000,
      "name": "khugepaged_enter_vma",
      "external": true,
      "loc": "mm/khugepaged.c:451",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:vma_merge",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:hugepage_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583568000,
      "name": "khugepaged_enter_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void khugepaged_enter_vma(struct vm_area_struct * vma, long unsigned int vm_flags)
```

```json
{
  "name": "khugepaged_enter_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583760496,
      "name": "khugepaged_enter_vma",
      "external": true,
      "loc": "mm/khugepaged.c:445",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:vma_merge",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:hugepage_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583760496,
      "name": "khugepaged_enter_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void khugepaged_enter_vma(struct vm_area_struct * vma, long unsigned int vm_flags)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
