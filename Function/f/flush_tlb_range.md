# Function: <code>flush_tlb_range</code>

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
  "name": "flush_tlb_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490358724,
      "name": "flush_tlb_range",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:214",
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
      "addr": 18446603336492799468,
      "name": "flush_tlb_range",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:214",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492802836,
      "name": "flush_tlb_range",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:214",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492811388,
      "name": "flush_tlb_range",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:214",
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
      "addr": 18446603336492818388,
      "name": "flush_tlb_range",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:214",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492997108,
      "name": "flush_tlb_range",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:214",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493137888,
      "name": "flush_tlb_range",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:214",
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
void flush_tlb_range(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224453828,
      "name": "flush_tlb_range",
      "external": true,
      "loc": "arch/arm/kernel/smp_tlb.c:220",
      "file": "arch/arm/kernel/smp_tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:tlb_flush",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/madvise.c:tlb_flush_mmu_tlbonly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224453828,
      "name": "flush_tlb_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
  "name": "flush_tlb_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286172608,
      "name": "flush_tlb_range",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush.h:68",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286176112,
      "name": "flush_tlb_range",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush.h:68",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286201124,
      "name": "flush_tlb_range",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush.h:68",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286574212,
      "name": "flush_tlb_range",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush.h:68",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286622136,
      "name": "flush_tlb_range",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush.h:68",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void flush_tlb_range(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_tlb_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271361410,
      "name": "flush_tlb_range",
      "external": true,
      "loc": "arch/riscv/mm/tlbflush.c:52",
      "file": "arch/riscv/mm/tlbflush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271361410,
      "name": "flush_tlb_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void flush_tlb_range(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void flush_tlb_range(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```
</details>
</li>
</ul>
