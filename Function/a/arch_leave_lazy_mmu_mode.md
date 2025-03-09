# Function: <code>arch_leave_lazy_mmu_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579258291,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:673",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu",
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580670605,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:673",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580715492,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:673",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580719008,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:673",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579257778,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:646",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580795074,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:646",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830896,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:646",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580834535,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:646",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580872121,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:646",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579271298,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:637",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580859342,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:637",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580896473,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:637",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580900804,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:637",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580940008,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:637",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
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
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579267993,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:684",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580904205,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:684",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580941354,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:684",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580945348,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:684",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580984541,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:684",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
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
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579284978,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:648",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581003736,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:648",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581041345,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:648",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581046153,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:648",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581087581,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:648",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581250825,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:648",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
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
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579296450,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:653",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581142427,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:653",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581176645,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:653",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581183729,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:653",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581230440,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:653",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393450,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:653",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
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
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579320978,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:631",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581217070,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:631",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581260073,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:631",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581266113,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:631",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581313419,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:631",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479054,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:631",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
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
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579336162,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:632",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581290328,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:632",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333733,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:632",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581340698,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:632",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423974,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:632",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
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
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579340370,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581349064,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393141,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581400020,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581485366,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581657825,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
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
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579369797,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:634",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581526559,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:634",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:remap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581591770,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:634",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581598010,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:634",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581690610,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:634",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581876862,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:634",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
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
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579368805,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581570561,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:remap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581637776,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581644179,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581740354,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581924801,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
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
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579373093,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:563",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581591545,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:563",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659419,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:563",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665686,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:563",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581768635,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:563",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581947664,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:563",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
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
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579434389,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:563",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581858361,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:563",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581927722,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:563",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581934374,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:563",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582051291,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:563",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582252300,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:563",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
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
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579503677,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:569",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582253042,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:569",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582334702,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:569",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582343363,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:569",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582476899,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:569",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582740732,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:569",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
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
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579601325,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:569",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582545010,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:569",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582744402,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:569",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582835385,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:569",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582844677,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:569",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582991171,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:569",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583272151,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:569",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
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
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579614077,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:564",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582742941,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:564",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582960766,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:564",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:remap_p4d_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583050588,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:564",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583058918,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:564",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583202127,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:564",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583495558,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:564",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void arch_leave_lazy_mmu_mode()
```

```json
{
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579078991,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579095097,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579103503,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218228,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579244303,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579306959,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579472911,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579643231,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582685311,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582910424,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583096751,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583138254,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": [
        "mm/memory.c:zap_pte_range"
      ]
    },
    {
      "addr": 18446744071583232620,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583240585,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583267135,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583294146,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583437663,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583468927,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583517423,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583566602,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_split_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583600719,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583618719,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583659807,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583686792,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583700980,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583891023,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584745049,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_scan_pmd_entry",
        "fs/proc/task_mmu.c:pagemap_scan_pmd_entry",
        "fs/proc/task_mmu.c:pagemap_scan_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590183247,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:562",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583121792,
      "name": "arch_leave_lazy_mmu_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282761532,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:39",
      "file": "arch/powerpc/mm/book3s64/hash_tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/hash_tlb.c:flush_tlb_pmd_range",
        "arch/powerpc/mm/book3s64/hash_tlb.c:flush_tlb_pmd_range",
        "arch/powerpc/mm/book3s64/hash_tlb.c:__flush_hash_table_range",
        "arch/powerpc/mm/book3s64/hash_tlb.c:__flush_hash_table_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282817520,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:39",
      "file": "arch/powerpc/mm/book3s64/subpage_prot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/subpage_prot.c:hpte_flush_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286118664,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:39",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286170200,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:39",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286175676,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:39",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286305136,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:39",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286572672,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:39",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579336274,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581317912,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361989,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581368868,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581454214,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626561,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579336194,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581309112,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581353189,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581360068,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581445414,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581617873,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
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
  "name": "arch_leave_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579344608,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581373110,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581417125,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423961,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581509893,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581686317,
      "name": "arch_leave_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:620",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
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
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void arch_leave_lazy_mmu_mode()
```
</details>
</li>
</ul>
