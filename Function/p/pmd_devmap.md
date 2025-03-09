# Function: <code>pmd_devmap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579309229,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580766836,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580789807,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580803765,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580829856,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580834816,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580864781,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580938863,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032134,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581077458,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619480,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
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
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579324461,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580832399,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580854258,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580868805,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580895424,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580900992,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580906749,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581107429,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581153055,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583805,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581707880,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:191",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
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
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580880388,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages_fast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580899307,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580913881,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580940302,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580945528,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580952405,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581157606,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581200351,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642634,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581761512,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
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
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580965265,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:246",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581002106,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:246",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581013161,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:246",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581041449,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:246",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581046540,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:246",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581054316,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:246",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581168502,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:246",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581251958,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:246",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581280693,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:246",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330428,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:246",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394370,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:246",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581789252,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:246",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581907375,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:246",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pmd_devmap(pmd_t pmd)
```

```json
{
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581101581,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581139223,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147721,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581179592,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection",
        "mm/mprotect.c:change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581184117,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581193218,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581313209,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393775,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581428818,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581478760,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581502256,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581544923,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581962728,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582092911,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581097632,
      "name": "pmd_devmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pmd_devmap(pmd_t pmd)
```

```json
{
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581178691,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:258",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581212233,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:258",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581227545,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:258",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581260933,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:258",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581266671,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:258",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581276103,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:258",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394815,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:258",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479421,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:258",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581514633,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:258",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581568952,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:258",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581587507,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:258",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627736,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:258",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582045306,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:258",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582187295,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:258",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581177360,
      "name": "pmd_devmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581248898,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581288464,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581301614,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581335392,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581341262,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581350554,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581507028,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581624248,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680538,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698822,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581746824,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582209668,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582350673,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pmd_devmap(pmd_t pmd)
```

```json
{
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581307506,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347184,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581360254,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581395033,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581400586,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581409177,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581486676,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581571396,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658550,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581695121,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581752506,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772262,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581819104,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582290564,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582449537,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581305632,
      "name": "pmd_devmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581510776,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:280",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581551582,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:280",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:pte_alloc_one_map",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581557710,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:280",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581592370,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:280",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581598600,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:280",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608165,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:280",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581691960,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:280",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581789453,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:280",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581877179,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:280",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581913223,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:280",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581972906,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:280",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581993000,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:280",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582036735,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:280",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042460,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:280",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582578102,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:280",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582744492,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:280",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
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
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581550904,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581594718,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:pte_alloc_one_map",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602622,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638389,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581644969,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581655589,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581736824,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581836877,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581925434,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581958899,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582021114,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042568,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582085567,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582091420,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582649323,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582817900,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
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
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581333984,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581575184,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581615383,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:finish_fault",
        "mm/memory.c:copy_pmd_range",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625143,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581660020,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581666465,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677076,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581765169,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581867709,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581948623,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581984882,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582047608,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582069047,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582110904,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582116492,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582678631,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582848204,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:279",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
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
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581582160,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581839817,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581881812,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:finish_fault",
        "mm/memory.c:copy_pmd_range",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581892631,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581928355,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581935320,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946272,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582047830,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582158749,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582253203,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582286865,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354392,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582381012,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582427224,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582432876,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583004613,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583181260,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
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
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581938925,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582231947,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582284046,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:finish_fault",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582290731,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582303759,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582336081,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582344983,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582352932,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582355475,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582478816,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582614025,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582742019,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582770522,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582854671,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582882412,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582943840,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582949508,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583475162,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583668968,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:253",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
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
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582373949,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582512575,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582720985,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582776476,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:finish_fault",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582783221,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582798222,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582837106,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582846221,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582854536,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582857580,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582992369,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583137679,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583273458,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583305164,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583331517,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:find_pmd_or_thp_or_none"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583401487,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583432217,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583500768,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583506724,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584067722,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584275742,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:254",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
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
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582714607,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582938652,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582992739,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583000232,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583012379,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583052389,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583061834,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583070483,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583073100,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583078381,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:__pte_offset_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583202747,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583348222,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_folios_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583495039,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583524456,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583550349,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:find_pmd_or_thp_or_none"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583622246,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583651352,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583715112,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583721862,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584239048,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584294109,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584506245,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:255",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
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
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582883835,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583113882,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583174551,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583179608,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583191491,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583234037,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583243396,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583252234,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583255148,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583260716,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:__pte_offset_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583439398,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583584238,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_folios_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583683097,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_insert_page",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583719208,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583744557,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:find_pmd_or_thp_or_none"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583816915,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583845880,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583905170,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:move_pages",
        "mm/userfaultfd.c:move_pages",
        "mm/userfaultfd.c:move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583916008,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583922621,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584451161,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584510925,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584735614,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:291",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_devmap",
      "external": false,
      "loc": "include/linux/mm.h:568",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_devmap",
      "external": false,
      "loc": "include/linux/mm.h:568",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_devmap",
      "external": false,
      "loc": "include/linux/mm.h:568",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_devmap",
      "external": false,
      "loc": "include/linux/mm.h:568",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282719400,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1309",
      "file": "arch/powerpc/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/pgtable.c:__find_linux_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282816836,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1309",
      "file": "arch/powerpc/mm/book3s64/subpage_prot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/subpage_prot.c:subpage_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286058464,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1309",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286112240,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1309",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286129568,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1309",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286170400,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1309",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286177992,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1309",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286188104,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1309",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286309908,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1309",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286435988,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1309",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286574080,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1309",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286623772,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1309",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286712936,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1309",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286746016,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1309",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286818240,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1309",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287496156,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1309",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287723024,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1309",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
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
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_devmap",
      "external": false,
      "loc": "include/linux/mm.h:568",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_devmap",
      "external": false,
      "loc": "include/linux/mm.h:568",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_devmap",
      "external": false,
      "loc": "include/linux/mm.h:568",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_devmap",
      "external": false,
      "loc": "include/linux/mm.h:568",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_devmap",
      "external": false,
      "loc": "include/linux/mm.h:568",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pmd_devmap(pmd_t pmd)
```

```json
{
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581276354,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581316032,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329102,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363881,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369434,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581378025,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581455524,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581540132,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627286,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663857,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721242,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740998,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581787840,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582259300,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582418273,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581274480,
      "name": "pmd_devmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581222816,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581258747,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581272921,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306720,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581311327,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581321482,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581481834,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581568518,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581603528,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581660090,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581679752,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581725767,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582196208,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582357659,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pmd_devmap(pmd_t pmd)
```

```json
{
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581267554,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581307232,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581320302,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581355081,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581360634,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369225,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581446724,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531444,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618598,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581655169,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581712554,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581732310,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581779152,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582249780,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582408753,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581265680,
      "name": "pmd_devmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pmd_devmap(pmd_t pmd)
```

```json
{
  "name": "pmd_devmap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581331410,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581371232,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384279,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581418958,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581424523,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581433097,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581511188,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581594063,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581687038,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721558,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581780088,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581800598,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581848112,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582328009,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582489626,
      "name": "pmd_devmap",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:275",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581329536,
      "name": "pmd_devmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int pmd_devmap(pmd_t pmd)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int pmd_devmap(pmd_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int pmd_devmap(pmd_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int pmd_devmap(pmd_t pmd)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int pmd_devmap(pmd_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int pmd_devmap(pmd_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int pmd_devmap(pmd_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int pmd_devmap(pmd_t pmd)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int pmd_devmap(pmd_t pmd)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
