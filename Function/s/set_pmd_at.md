# Function: <code>set_pmd_at</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580747414,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:503",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580890182,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:503",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580894192,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:503",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437871,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:503",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580787532,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580866566,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020720,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581031447,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050822,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620295,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:476",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580851827,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580908502,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095320,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581106743,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581133784,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581585195,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581708689,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:467",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580897133,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580954054,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580955283,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581142120,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581156431,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581173918,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581646130,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581755580,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580995676,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:989",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:989",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:989",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581264332,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:989",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293764,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:989",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581310194,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:989",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:989",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:989",
      "file": "fs/proc/task_mmu.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581129765,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1040",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581195349,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1040",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581411330,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1040",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440904,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1040",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581451862,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1040",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581959865,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1040",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582094353,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1040",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581209544,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1065",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581267098,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1065",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581278779,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1065",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581494709,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1065",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581524325,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1065",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535522,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1065",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582041151,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1065",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582190117,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1065",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581284493,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581341676,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581354655,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602625,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581633240,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581645628,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582202241,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582353484,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581343213,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581401002,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581414182,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487968,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673313,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581704280,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581717302,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582283078,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582452380,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581517976,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1045",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581597323,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1045",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_normal_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613825,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1045",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581694295,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1045",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581891840,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1045",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581920310,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1045",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581936176,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1045",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570793,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1045",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582748498,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1045",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581563683,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1041",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581643516,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1041",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581662219,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1041",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581739154,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1041",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581937900,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1041",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581966994,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1041",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581978692,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1041",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582643113,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1041",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582820745,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1041",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581604054,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1041",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665019,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1041",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581684140,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1041",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767448,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1041",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581963397,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1041",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581995117,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1041",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582006713,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1041",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582671126,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1041",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582849517,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1041",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581870265,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1012",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581953352,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1012",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582050106,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1012",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582297309,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1012",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582309147,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1012",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582997382,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1012",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583182573,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1012",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582265507,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1011",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582364229,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1011",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582481217,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1011",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582785144,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1011",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582805320,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1011",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583468744,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1011",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583673724,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1011",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582756949,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582867779,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582995171,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583318166,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583338922,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584061538,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_pmd_load_hole"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584281273,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582972758,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1030",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583085127,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1030",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583204502,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1030",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583536683,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1030",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583558043,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1030",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584287974,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1030",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_pmd_load_hole"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584511357,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1030",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583150515,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1245",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583267738,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1245",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583440273,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1245",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583730625,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1245",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583757902,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1245",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584504774,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1245",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_pmd_load_hole"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584733987,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1245",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void set_pmd_at(struct mm_struct * mm, long unsigned int addr, pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "set_pmd_at",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282756288,
      "name": "set_pmd_at",
      "external": true,
      "loc": "arch/powerpc/mm/book3s64/pgtable.c:64",
      "file": "arch/powerpc/mm/book3s64/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:alloc_set_pte",
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_huge_page",
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282756288,
      "name": "set_pmd_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
    }
  ]
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
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581312061,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369850,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383030,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581456816,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642049,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673016,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581686038,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582251814,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582421116,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581255782,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581313048,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581324679,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581400191,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582977,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612490,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625125,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582189383,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582360213,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581303261,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361050,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581374230,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448016,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581633361,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664328,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677350,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582242294,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411596,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pmd_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581367239,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581424939,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581438511,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581513506,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699697,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581730696,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581744013,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582319884,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582491042,
      "name": "set_pmd_at",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1085",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void set_pmd_at(struct mm_struct * mm, long unsigned int addr, pmd_t * pmdp, pmd_t pmd)
```
</details>
</li>
</ul>
