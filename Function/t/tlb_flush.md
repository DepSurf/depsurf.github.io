# Function: <code>tlb_flush</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_flush",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581202399,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:13",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581257495,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:13",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush",
        "mm/mmu_gather.c:tlb_flush_mmu"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_flush",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581274333,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:14",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581331968,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:14",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_flush",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581332892,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:14",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581391376,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:14",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_flush",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581530615,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:14",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581589211,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:14",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_flush",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581574458,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:14",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581635163,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:14",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_flush",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581595400,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:13",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581656779,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:13",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_flush",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581862387,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:13",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581924971,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:13",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582131039,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:13",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__unmap_hugepage_range"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_flush",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582260688,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:10",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582331737,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:10",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582338262,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:10",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582473268,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:10",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582578583,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:10",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_flush",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582751986,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:10",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582832153,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:10",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582839250,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:10",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582985922,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:10",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583104814,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:10",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_flush",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582968329,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:10",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583047545,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:10",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583054703,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:10",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583197442,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:10",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583314666,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:10",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_flush",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583147241,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:10",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583229385,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:10",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583236335,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:10",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583434840,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:10",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583552822,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:10",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_flush",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492740160,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/arm64/include/asm/tlb.h:24",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492795952,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/arm64/include/asm/tlb.h:24",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492898644,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/arm64/include/asm/tlb.h:24",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:tlb_flush_mmu_tlbonly"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492989868,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/arm64/include/asm/tlb.h:24",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__unmap_hugepage_range"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
void tlb_flush(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_flush",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226571632,
      "name": "tlb_flush",
      "external": false,
      "loc": "include/asm-generic/tlb.h:361",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range"
      ],
      "caller_func": [
        "mm/memory.c:unmap_page_range"
      ]
    },
    {
      "addr": 3226611796,
      "name": "tlb_flush",
      "external": false,
      "loc": "include/asm-generic/tlb.h:361",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 3226694608,
      "name": "tlb_flush",
      "external": false,
      "loc": "include/asm-generic/tlb.h:361",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:tlb_flush_mmu_tlbonly"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226559820,
      "name": "tlb_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
  "name": "tlb_flush",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286091516,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush.h:106",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286168112,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush.h:106",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_flush",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272725986,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/riscv/include/asm/tlb.h:16",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272764886,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/riscv/include/asm/tlb.h:16",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272830272,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/riscv/include/asm/tlb.h:16",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272891742,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/riscv/include/asm/tlb.h:16",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__unmap_hugepage_range"
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
  "name": "tlb_flush",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581301740,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:14",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581360224,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:14",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_flush",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581246623,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:14",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581303936,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:14",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_flush",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581292940,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:14",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581351424,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:14",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_flush",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581357066,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:14",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581415360,
      "name": "tlb_flush",
      "external": false,
      "loc": "arch/x86/include/asm/tlb.h:14",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush"
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

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void tlb_flush(struct mmu_gather * tlb)
```
</details>
</li>
</ul>
