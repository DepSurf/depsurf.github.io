# Function: <code>flush_tlb_mm</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "flush_tlb_mm",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490358924,
      "name": "flush_tlb_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:147",
      "file": "arch/arm64/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/hugetlbpage.c:huge_ptep_clear_flush",
        "arch/arm64/mm/hugetlbpage.c:set_huge_pte_at",
        "arch/arm64/mm/hugetlbpage.c:get_clear_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490626116,
      "name": "flush_tlb_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:147",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492741512,
      "name": "flush_tlb_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:147",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492796496,
      "name": "flush_tlb_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:147",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492799648,
      "name": "flush_tlb_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:147",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492803420,
      "name": "flush_tlb_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:147",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492811548,
      "name": "flush_tlb_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:147",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pmdp_huge_clear_flush",
        "mm/pgtable-generic.c:pmdp_clear_flush_young"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492819912,
      "name": "flush_tlb_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:147",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492899180,
      "name": "flush_tlb_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:147",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:tlb_flush_mmu_tlbonly",
        "mm/madvise.c:tlb_flush_mmu_tlbonly"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492997716,
      "name": "flush_tlb_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:147",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493138204,
      "name": "flush_tlb_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:147",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void flush_tlb_mm(struct mm_struct * mm)
```

```json
{
  "name": "flush_tlb_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224453224,
      "name": "flush_tlb_mm",
      "external": true,
      "loc": "arch/arm/kernel/smp_tlb.c:187",
      "file": "arch/arm/kernel/smp_tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/memory.c:unmap_page_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/madvise.c:tlb_flush_mmu_tlbonly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224453224,
      "name": "flush_tlb_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
  "name": "flush_tlb_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283443976,
      "name": "flush_tlb_mm",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush.h:114",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void flush_tlb_mm(struct mm_struct * mm)
```

```json
{
  "name": "flush_tlb_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271361294,
      "name": "flush_tlb_mm",
      "external": true,
      "loc": "arch/riscv/mm/tlbflush.c:42",
      "file": "arch/riscv/mm/tlbflush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271361294,
      "name": "flush_tlb_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void flush_tlb_mm(struct mm_struct * mm)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void flush_tlb_mm(struct mm_struct * mm)
```
</details>
</li>
</ul>
