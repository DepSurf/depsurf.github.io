# Function: <code>arch_enter_lazy_mmu_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579258298,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:668",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu",
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580670120,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:668",
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
      "addr": 18446744071580715030,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:668",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580718756,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:668",
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
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579257852,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:641",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580794959,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:641",
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
      "addr": 18446744071580830403,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:641",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580834399,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:641",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580871576,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:641",
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
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579271367,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:632",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580859233,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:632",
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
      "addr": 18446744071580895966,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:632",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580900504,
      "name": "arch_enter_lazy_mmu_mode",
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
      "addr": 18446744071580939479,
      "name": "arch_enter_lazy_mmu_mode",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579268071,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:679",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580904098,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:679",
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
      "addr": 18446744071580940701,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:679",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580945030,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:679",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580983691,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:679",
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
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579285049,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:643",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581003618,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:643",
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
      "addr": 18446744071581040837,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:643",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581045956,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:643",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581086708,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:643",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581250531,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:643",
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
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579296522,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:648",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581142289,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:648",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581176190,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:648",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581183328,
      "name": "arch_enter_lazy_mmu_mode",
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
      "addr": 18446744071581229682,
      "name": "arch_enter_lazy_mmu_mode",
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
      "addr": 18446744071581392786,
      "name": "arch_enter_lazy_mmu_mode",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579321050,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:626",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581216932,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:626",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581259561,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:626",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581265762,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:626",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312658,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:626",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581478402,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:626",
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
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579336234,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:627",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581290277,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:627",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333270,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:627",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581340353,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:627",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423482,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:627",
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
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579340442,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581349013,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392678,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581399642,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581484874,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581657244,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
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
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579369861,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:629",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581526479,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:629",
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
      "addr": 18446744071581591028,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:629",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581597890,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:629",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581690076,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:629",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581875960,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:629",
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
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579368869,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:527",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581570474,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:527",
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
      "addr": 18446744071581637044,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:527",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581644069,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:527",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581739820,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:527",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581924440,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:527",
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
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579373157,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:558",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581591458,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:558",
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
      "addr": 18446744071581658687,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:558",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665576,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:558",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581768104,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:558",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581947352,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:558",
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
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579434453,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:558",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581858274,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:558",
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
      "addr": 18446744071581926959,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:558",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581934264,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:558",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582050760,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:558",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582251994,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:558",
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
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579503794,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:564",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582252954,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:564",
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
      "addr": 18446744071582333807,
      "name": "arch_enter_lazy_mmu_mode",
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
      "addr": 18446744071582343252,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:564",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582476373,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:564",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582740568,
      "name": "arch_enter_lazy_mmu_mode",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579601461,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:564",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582544714,
      "name": "arch_enter_lazy_mmu_mode",
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
      "addr": 18446744071582744314,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:564",
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
      "addr": 18446744071582834697,
      "name": "arch_enter_lazy_mmu_mode",
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
      "addr": 18446744071582844566,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:564",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582990788,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:564",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583271851,
      "name": "arch_enter_lazy_mmu_mode",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579614213,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:559",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582742620,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:559",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582960669,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:559",
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
      "addr": 18446744071583049899,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:559",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583058811,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:559",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583202358,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:559",
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
      "addr": 18446744071583495233,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:559",
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
void arch_enter_lazy_mmu_mode()
```

```json
{
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579078960,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579097123,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_end_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579103509,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218210,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579244272,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579306928,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579472880,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579643213,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582685280,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582910086,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583096720,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583138157,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
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
      "addr": 18446744071583232602,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583240526,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583267104,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583294128,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583437902,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583468896,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583517392,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583566584,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_split_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583600688,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583618688,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583659776,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583686463,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583700962,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583890992,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584745013,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_scan_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590183216,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:557",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583121728,
      "name": "arch_enter_lazy_mmu_mode",
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
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282761328,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:29",
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
      "addr": 13835058055282817428,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:29",
      "file": "arch/powerpc/mm/book3s64/subpage_prot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/subpage_prot.c:hpte_flush_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286118588,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:29",
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
      "addr": 13835058055286170064,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:29",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286175384,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:29",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286304924,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:29",
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
      "addr": 13835058055286572144,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:29",
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
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579336346,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581317861,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361526,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581368490,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581453722,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625980,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
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
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579336266,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581309061,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581352726,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581359690,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581444922,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581617292,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
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
  "name": "arch_enter_lazy_mmu_mode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579344696,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_end_context_switch",
        "arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581373059,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581416662,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423596,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581509402,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581685736,
      "name": "arch_enter_lazy_mmu_mode",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:615",
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
void arch_enter_lazy_mmu_mode()
```
</details>
</li>
</ul>
