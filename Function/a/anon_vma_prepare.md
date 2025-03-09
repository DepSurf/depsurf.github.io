# Function: <code>anon_vma_prepare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int anon_vma_prepare(struct vm_area_struct * vma)
```

```json
{
  "name": "anon_vma_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580728736,
      "name": "anon_vma_prepare",
      "external": true,
      "loc": "mm/rmap.c:169",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/mmap.c:expand_downwards",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_zeropage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580728736,
      "name": "anon_vma_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
int anon_vma_prepare(struct vm_area_struct * vma)
```

```json
{
  "name": "anon_vma_prepare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580847984,
      "name": "anon_vma_prepare",
      "external": true,
      "loc": "mm/rmap.c:170",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:wp_page_copy",
        "mm/mmap.c:expand_downwards",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580847984,
      "name": "anon_vma_prepare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580586727,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:146",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580857309,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:146",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580887878,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:146",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581000543,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:146",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581100016,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:146",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581203638,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:146",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580616804,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:144",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580900848,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:144",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580932869,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:144",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581043621,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:144",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581148787,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:144",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581252598,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:144",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579406402,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580697451,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580998220,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032629,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581154134,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245613,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581269301,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384543,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579416976,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580829817,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581131207,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581167213,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581297236,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581397008,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581418161,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535067,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579456658,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580899029,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581213398,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581247261,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581380532,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581480640,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581504223,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581621130,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
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
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579465662,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580996691,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581285031,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581321862,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581491884,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613699,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581733488,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
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
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579491966,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581051107,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581343751,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581381094,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581556364,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659458,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581684611,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581807040,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
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
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581233882,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581539841,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581575398,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581766550,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581880783,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581902871,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582027437,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
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
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581276502,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:147",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583041,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:147",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620918,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:147",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581814709,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:147",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581926802,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:147",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581949047,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:147",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582076215,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:147",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
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
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581292424,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581605697,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581647350,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581842797,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581952169,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581974755,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582102478,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
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
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581537336,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:144",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581871741,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:144",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581915462,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:144",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582134156,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:144",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582256883,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:144",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582277431,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:144",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582418622,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:144",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
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
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581887015,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582267309,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582321898,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582582799,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582744005,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582761319,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582932701,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
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
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582319895,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582758970,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582822835,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583109151,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583275679,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583295265,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583488382,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
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
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582521155,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582974577,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583037598,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583319441,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583492045,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583514372,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583704023,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:154",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy"
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
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582690000,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:159",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583169177,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:159",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583219220,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:159",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583557221,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:159",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583683130,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:159",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583708164,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:159",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583904178,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:159",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:move_pages",
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy"
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
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490625792,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492407972,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492749504,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492788000,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492993292,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493131948,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493271980,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224703816,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3226292336,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 3226580732,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 3226603488,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 3226878364,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283443352,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285673184,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286107804,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286157236,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286415336,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286565196,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286610996,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286799736,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
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
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271382206,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272732856,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272758626,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272894682,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273024504,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
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
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579465630,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581019955,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312599,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581349942,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581525100,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581628194,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581653347,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581775776,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
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
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579394590,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580966051,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581256311,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293654,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581467120,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581569346,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581593571,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581713924,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
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
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579465550,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581011155,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581303799,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581341142,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581516412,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619506,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581644659,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767088,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
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
  "name": "anon_vma_prepare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579497294,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581072363,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581367767,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581405094,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581581409,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581682786,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581711075,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581835927,
      "name": "anon_vma_prepare",
      "external": false,
      "loc": "include/linux/rmap.h:148",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int anon_vma_prepare(struct vm_area_struct * vma)
```
</details>
</li>
</ul>
