# Function: <code>flush_tlb_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void flush_tlb_page(struct vm_area_struct * vma, long unsigned int start)
```

```json
{
  "name": "flush_tlb_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579314752,
      "name": "flush_tlb_page",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:239",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pgtable-generic.c:ptep_clear_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579314752,
      "name": "flush_tlb_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void flush_tlb_page(struct vm_area_struct * vma, long unsigned int start)
```

```json
{
  "name": "flush_tlb_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579314688,
      "name": "flush_tlb_page",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:359",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pgtable-generic.c:ptep_clear_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579314688,
      "name": "flush_tlb_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void flush_tlb_page(struct vm_area_struct * vma, long unsigned int start)
```

```json
{
  "name": "flush_tlb_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579329968,
      "name": "flush_tlb_page",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:374",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pgtable-generic.c:ptep_clear_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329968,
      "name": "flush_tlb_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
  "name": "flush_tlb_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580953524,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:251",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush"
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
  "name": "flush_tlb_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581055259,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:519",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush"
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
  "name": "flush_tlb_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581193985,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:564",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush"
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
  "name": "flush_tlb_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581277265,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:565",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush"
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
  "name": "flush_tlb_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581351714,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:567",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush"
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
  "name": "flush_tlb_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581411218,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:583",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush"
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
  "name": "flush_tlb_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581611348,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:233",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush"
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
  "name": "flush_tlb_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581580167,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:233",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658676,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:233",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush"
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
  "name": "flush_tlb_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581600848,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:237",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680484,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:237",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush"
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
  "name": "flush_tlb_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581867376,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:237",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581949764,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:237",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush"
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
  "name": "flush_tlb_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582264496,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:237",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582359265,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:237",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush"
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
  "name": "flush_tlb_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582756071,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:238",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582861585,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:238",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush"
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
  "name": "flush_tlb_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582971894,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:251",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583077089,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:251",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush"
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
  "name": "flush_tlb_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583144405,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583259345,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:252",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush"
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
  "name": "flush_tlb_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490341000,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:167",
      "file": "arch/arm64/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/fault.c:ptep_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492752828,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:167",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492810280,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:167",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush"
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
void flush_tlb_page(struct vm_area_struct * vma, long unsigned int uaddr)
```

```json
{
  "name": "flush_tlb_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224453372,
      "name": "flush_tlb_page",
      "external": true,
      "loc": "arch/arm/kernel/smp_tlb.c:196",
      "file": "arch/arm/kernel/smp_tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/pgtable-generic.c:ptep_clear_flush",
        "mm/pgtable-generic.c:ptep_clear_flush_young",
        "mm/pgtable-generic.c:ptep_set_access_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224453372,
      "name": "flush_tlb_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
  "name": "flush_tlb_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286112880,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush.h:121",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286190660,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush.h:121",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush",
        "mm/pgtable-generic.c:ptep_clear_flush_young"
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
void flush_tlb_page(struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "flush_tlb_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271361348,
      "name": "flush_tlb_page",
      "external": true,
      "loc": "arch/riscv/mm/tlbflush.c:47",
      "file": "arch/riscv/mm/tlbflush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pgtable-generic.c:ptep_clear_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271361348,
      "name": "flush_tlb_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
  "name": "flush_tlb_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581380066,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:583",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush"
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
  "name": "flush_tlb_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581322770,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:583",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush"
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
  "name": "flush_tlb_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581371266,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:583",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush"
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
  "name": "flush_tlb_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581435154,
      "name": "flush_tlb_page",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:583",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:ptep_clear_flush"
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
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void flush_tlb_page(struct vm_area_struct * vma, long unsigned int start)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void flush_tlb_page(struct vm_area_struct * vma, long unsigned int uaddr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void flush_tlb_page(struct vm_area_struct * vma, long unsigned int addr)
```
</details>
</li>
</ul>
