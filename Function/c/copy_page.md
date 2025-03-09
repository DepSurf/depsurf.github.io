# Function: <code>copy_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "kernel/power/swap.c:write_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_replace_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "fs/dax.c:__dax_fault",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582998224,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "kernel/power/swap.c:write_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_replace_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:wp_page_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "fs/dax.c:dax_fault",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583287856,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "kernel/power/swap.c:write_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_replace_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:wp_page_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:dax_iomap_fault",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583406608,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "kernel/power/swap.c:write_page",
        "kernel/power/swap.c:write_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_replace_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:wp_page_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "fs/dax.c:dax_iomap_fault",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588263280,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "kernel/power/swap.c:write_page",
        "kernel/power/swap.c:write_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_replace_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:wp_page_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:dax_iomap_fault",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588815808,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "kernel/power/swap.c:write_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_replace_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:wp_page_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589193936,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "kernel/power/swap.c:write_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_replace_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:wp_page_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589435392,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "kernel/power/swap.c:write_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/khugepaged.c:collapse_shmem",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589893392,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "kernel/power/swap.c:write_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/khugepaged.c:collapse_file",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590119344,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_replace_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:wp_page_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:copy_huge_page",
        "mm/migrate.c:__copy_gigantic_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_copy",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585122976,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "kernel/power/swap.c:write_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_replace_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:copy_huge_page",
        "mm/migrate.c:__copy_gigantic_page",
        "mm/khugepaged.c:collapse_file",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585273888,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "kernel/power/swap.c:write_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_replace_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585157408,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "kernel/power/swap.c:write_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_replace_page",
        "mm/util.c:copy_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_pte_range",
        "mm/sparse-vmemmap.c:vmemmap_restore_pte",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_fault_cow_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585610256,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void copy_page()
```

```json
{
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586766944,
      "name": "copy_page",
      "external": true,
      "loc": "arch/x86/lib/copy_page_64.S",
      "file": "arch/x86/lib/copy_page_64.S",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "kernel/power/swap.c:write_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_replace_page",
        "mm/util.c:folio_copy",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_present_pte",
        "mm/sparse-vmemmap.c:vmemmap_restore_pte",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_fault_cow_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586766944,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void copy_page()
```

```json
{
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595931840,
      "name": "copy_page",
      "external": true,
      "loc": "arch/x86/lib/copy_page_64.S",
      "file": "arch/x86/lib/copy_page_64.S",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/util.c:folio_copy",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:copy_present_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free",
        "mm/hugetlb_vmemmap.c:vmemmap_restore_pte",
        "mm/migrate_device.c:migrate_device_coherent_page",
        "mm/khugepaged.c:collapse_file",
        "fs/dax.c:dax_fault_cow_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595931840,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void copy_page()
```

```json
{
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596450224,
      "name": "copy_page",
      "external": true,
      "loc": "arch/x86/lib/copy_page_64.S",
      "file": "arch/x86/lib/copy_page_64.S",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/util.c:folio_copy",
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:copy_present_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free",
        "mm/hugetlb_vmemmap.c:vmemmap_restore_pte",
        "mm/migrate_device.c:migrate_device_coherent_page",
        "fs/dax.c:dax_fault_cow_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596450224,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void copy_page()
```

```json
{
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597345552,
      "name": "copy_page",
      "external": true,
      "loc": "arch/x86/lib/copy_page_64.S",
      "file": "arch/x86/lib/copy_page_64.S",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:alloc_p2m_pmd",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/util.c:folio_copy",
        "mm/memory.c:do_fault",
        "mm/memory.c:copy_present_pte",
        "mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_optimize_folio",
        "mm/hugetlb_vmemmap.c:vmemmap_restore_pte",
        "mm/migrate_device.c:migrate_device_coherent_page",
        "mm/zsmalloc.c:zs_page_migrate",
        "fs/dax.c:dax_fault_cow_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597345552,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/copypage.c:__cpu_copy_user_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_swapin_page",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/khugepaged.c:collapse_file",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503796888,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/hibernate.c:arch_restore_image",
        "arch/arm/mm/copypage-v6.c:v6_copy_user_highpage_nonaliasing",
        "kernel/power/snapshot.c:restore_highmem",
        "kernel/power/snapshot.c:restore_highmem",
        "kernel/power/snapshot.c:restore_highmem",
        "kernel/power/snapshot.c:copy_last_highmem_page",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/swap.c:write_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_swapin_page",
        "mm/migrate.c:__buffer_migrate_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236414560,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/machine_kexec_64.c:kexec_copy_flush",
        "arch/powerpc/mm/mem.c:copy_user_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_swapin_page",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/khugepaged.c:collapse_file",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282897516,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 0
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
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "kernel/power/swap.c:write_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/khugepaged.c:collapse_file",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589721600,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:write_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589447376,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "kernel/power/swap.c:write_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/khugepaged.c:collapse_file",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590164976,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "kernel/power/swap.c:write_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/khugepaged.c:collapse_file",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590215488,
      "name": "copy_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void copy_page()
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
