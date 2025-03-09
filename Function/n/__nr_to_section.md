# Function: <code>__nr_to_section</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579278047,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579285780,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_check_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309134,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579698936,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:saveable_page",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_write_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580121538,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587352130,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:reserve_bootmem_region",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:get_pfnblock_flags_mask",
        "mm/page_alloc.c:set_pfnblock_flags_mask",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580602328,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580634067,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:pageblock_pfn_to_page",
        "mm/compaction.c:pageblock_pfn_to_page",
        "mm/compaction.c:__reset_isolation_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580687480,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:vm_insert_pfn",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580789306,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:update_and_free_page",
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:set_max_huge_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595148624,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:__section_nr",
        "mm/sparse.c:node_memmap_size_bytes",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_add_one_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595150010,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node",
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580873117,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:find_smallest_section_pfn",
        "mm/memory_hotplug.c:find_biggest_section_pfn",
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:register_page_bootmem_info_node",
        "mm/memory_hotplug.c:register_page_bootmem_info_node",
        "mm/memory_hotplug.c:test_pages_in_a_zone",
        "mm/memory_hotplug.c:walk_memory_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580884840,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580900391,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580949307,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595156264,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_init_reserved_areas",
        "mm/cma.c:cma_init_reserved_areas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975352,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580977575,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581499021,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpagecount_read",
        "fs/proc/page.c:kpageflags_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583785045,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583910002,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584483922,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_one_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584485198,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1074",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_online",
        "drivers/base/memory.c:show_mem_removable",
        "drivers/base/memory.c:store_soft_offline_page",
        "drivers/base/memory.c:memory_dev_init",
        "drivers/base/memory.c:memory_dev_init"
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
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579277408,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579285492,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_check_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308863,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579725486,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:saveable_page",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580155530,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580542043,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580601015,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:free_hot_cold_page",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:reserve_bootmem_region",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask",
        "mm/page_alloc.c:get_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580705390,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580741202,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:__reset_isolation_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580802913,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vm_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580917969,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587861795,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_one_section",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:__section_nr",
        "mm/sparse.c:node_memmap_size_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595321387,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node",
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581003379,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:walk_memory_range",
        "mm/memory_hotplug.c:test_pages_in_a_zone",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:find_biggest_section_pfn",
        "mm/memory_hotplug.c:find_smallest_section_pfn",
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:register_page_bootmem_info_node",
        "mm/memory_hotplug.c:register_page_bootmem_info_node",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581010415,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581042077,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581103835,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595329820,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_init_reserved_areas",
        "mm/cma.c:cma_init_reserved_areas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581129505,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581131679,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581684189,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584111064,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584241714,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584830505,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_one_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595466043,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1146",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_dev_init",
        "drivers/base/memory.c:memory_dev_init",
        "drivers/base/memory.c:store_soft_offline_page",
        "drivers/base/memory.c:memory_block_action",
        "drivers/base/memory.c:show_mem_removable"
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
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579292736,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579300878,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_check_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324095,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579753007,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:saveable_page",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580195934,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580606091,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580668032,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:free_hot_cold_page",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:reserve_bootmem_region",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask",
        "mm/page_alloc.c:get_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580771239,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580807017,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:__reset_isolation_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580867958,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vm_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580986265,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588076507,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_one_section",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:__section_nr",
        "mm/sparse.c:node_memmap_size_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595569652,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node",
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581077357,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:walk_memory_range",
        "mm/memory_hotplug.c:test_pages_in_a_zone",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:find_biggest_section_pfn",
        "mm/memory_hotplug.c:find_smallest_section_pfn",
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:register_page_bootmem_info_node",
        "mm/memory_hotplug.c:register_page_bootmem_info_node",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581084477,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581117224,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581178987,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595577987,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_init_reserved_areas",
        "mm/cma.c:cma_init_reserved_areas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581204579,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581206735,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581772384,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584259029,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584423154,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585023749,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_one_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595719055,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1124",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_dev_init",
        "drivers/base/memory.c:memory_dev_init",
        "drivers/base/memory.c:store_soft_offline_page",
        "drivers/base/memory.c:memory_block_action",
        "drivers/base/memory.c:show_mem_removable"
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
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579290074,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298650,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_check_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321455,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579749155,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:saveable_page",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580203618,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580635812,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580701391,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:free_hot_cold_page",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:reserve_bootmem_region",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask",
        "mm/page_alloc.c:get_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580807383,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580847097,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:__reset_isolation_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580912724,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vm_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032021,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581070505,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_remove_one_section",
        "mm/sparse.c:sparse_add_one_section",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:next_present_section_nr",
        "mm/sparse.c:section_mark_present",
        "mm/sparse.c:node_memmap_size_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596497193,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node",
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581124648,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:walk_memory_range",
        "mm/memory_hotplug.c:test_pages_in_a_zone",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:find_biggest_section_pfn",
        "mm/memory_hotplug.c:find_smallest_section_pfn",
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:register_page_bootmem_info_node",
        "mm/memory_hotplug.c:register_page_bootmem_info_node",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581132047,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581165289,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581227315,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581233172,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596505626,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_init_reserved_areas",
        "mm/cma.c:cma_init_reserved_areas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581253411,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581255273,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581826787,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584337076,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584506996,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585108486,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:link_mem_sections"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596644182,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_dev_init",
        "drivers/base/memory.c:memory_dev_init",
        "drivers/base/memory.c:store_soft_offline_page",
        "drivers/base/memory.c:memory_subsys_online",
        "drivers/base/memory.c:show_mem_removable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586563475,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586860962,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1145",
      "file": "drivers/ras/cec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_add_elem"
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
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579309623,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319352,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_res_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344911,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579782466,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:saveable_page",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580255006,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580715623,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580786801,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask",
        "mm/page_alloc.c:get_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580896583,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580938213,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:__reset_isolation_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581011884,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vm_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581141566,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588868152,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_one_section",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:__section_nr",
        "mm/sparse.c:node_memmap_size_bytes",
        "mm/sparse.c:present_section_nr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602824526,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node",
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581237322,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:walk_memory_range",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:test_pages_in_a_zone",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:find_biggest_section_pfn",
        "mm/memory_hotplug.c:find_smallest_section_pfn",
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:register_page_bootmem_info_node",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581247329,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581292212,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581358329,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581364613,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379969,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581385425,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581387499,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581976404,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584741366,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_do_proc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584917009,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585534681,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:link_mem_sections"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602974563,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_dev_init",
        "drivers/base/memory.c:store_soft_offline_page",
        "drivers/base/memory.c:memory_block_action",
        "drivers/base/memory.c:show_mem_removable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587030998,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587348803,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1154",
      "file": "drivers/ras/cec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_add_elem"
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
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579321071,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330184,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_res_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579348130,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356623,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579814335,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:clear_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580315454,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580848034,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580920078,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask",
        "mm/page_alloc.c:get_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032433,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581074401,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:__reset_isolation_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581145523,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vm_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581279890,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589247222,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_one_section",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:sparse_early_usemaps_alloc_node",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:__section_nr",
        "mm/sparse.c:present_section_nr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602997860,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node",
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383068,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:walk_memory_range",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:test_pages_in_a_zone",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:find_biggest_section_pfn",
        "mm/memory_hotplug.c:find_smallest_section_pfn",
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581391543,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439250,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581506777,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581514332,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581529949,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535857,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537951,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582157707,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582163801,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584969803,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585148444,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585778355,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:link_mem_sections"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603145966,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_dev_init",
        "drivers/base/memory.c:store_soft_offline_page",
        "drivers/base/memory.c:memory_block_action",
        "drivers/base/memory.c:memory_block_action",
        "drivers/base/memory.c:show_mem_removable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587329097,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587652444,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1153",
      "file": "drivers/ras/cec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_add_elem"
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
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579345375,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356376,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_res_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579375074,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383775,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579861087,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:clear_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580368030,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580916914,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995726,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask",
        "mm/page_alloc.c:get_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581110001,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581152097,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:__reset_isolation_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581225363,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581362418,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589489548,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_one_section",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:__section_nr",
        "mm/sparse.c:present_section_nr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581470684,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:walk_memory_range",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:test_pages_in_a_zone",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:find_biggest_section_pfn",
        "mm/memory_hotplug.c:find_smallest_section_pfn",
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581475005,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581522837,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581592649,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581600188,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581615741,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581621905,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581623999,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582251467,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582258793,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585074123,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585259340,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585908556,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_mem_sect_under_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604950640,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_dev_init",
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:memory_block_action",
        "drivers/base/memory.c:memory_block_action",
        "drivers/base/memory.c:removable_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587507433,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587782444,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1161",
      "file": "drivers/ras/cec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_add_elem"
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
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579360877,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371828,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390556,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579399252,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579895382,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:saveable_page",
        "kernel/power/snapshot.c:clear_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580420728,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581015025,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581174733,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581224667,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299007,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581414523,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask",
        "mm/page_alloc.c:get_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589943278,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581473691,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589950218,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:subsection_map_init",
        "mm/sparse.c:__section_nr",
        "mm/sparse.c:present_section_nr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589929488,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:test_pages_in_a_zone",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:find_biggest_section_pfn",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581589955,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581631780,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581704979,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581711437,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581727389,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581734353,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581736368,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582416056,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582423641,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585278408,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585468296,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586148247,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_mem_sect_under_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586154108,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:memory_block_action",
        "drivers/base/memory.c:memory_block_action",
        "drivers/base/memory.c:removable_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587781305,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588087004,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1228",
      "file": "drivers/ras/cec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_add_elem"
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
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579365117,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579375108,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579393868,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402564,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579945654,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:saveable_page",
        "kernel/power/snapshot.c:clear_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580469480,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581070305,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581232829,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283227,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581357775,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581475563,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask",
        "mm/page_alloc.c:get_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590170833,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581537734,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590177772,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:subsection_map_init",
        "mm/sparse.c:__section_nr",
        "mm/sparse.c:present_section_nr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590156704,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:test_pages_in_a_zone",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:register_page_bootmem_info_node",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581653619,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581702660,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581776451,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581784877,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581800941,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581807873,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581809888,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582515000,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582522561,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585416344,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585609000,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586296739,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_mem_sect_under_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586302684,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:memory_subsys_online",
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587049720,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587986009,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588292812,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/ras/cec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_add_elem"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct mem_section * __nr_to_section(long unsigned int nr)
```

```json
{
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579392042,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579403613,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_check_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408051,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411946,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579991368,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:clear_free_pages",
        "kernel/power/snapshot.c:mark_nosave_pages"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:saveable_page"
      ]
    },
    {
      "addr": 18446744071580553907,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581251158,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:try_ram_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581419303,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581475549,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581554708,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vmf_insert_pfn_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680649,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:pfn_range_valid_contig",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask",
        "mm/page_alloc.c:get_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591189151,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581744376,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:destroy_compound_gigantic_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581799293,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:clear_subsection_map",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:__section_nr"
      ],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_activate",
        "mm/sparse.c:section_activate",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:check_usemap_section_nr",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:subsection_map_init",
        "mm/sparse.c:next_present_section_nr"
      ]
    },
    {
      "addr": 18446744071581862137,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_and_remove_memory",
        "mm/memory_hotplug.c:scan_movable_pages",
        "mm/memory_hotplug.c:test_pages_in_a_zone",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:find_biggest_section_pfn",
        "mm/memory_hotplug.c:find_smallest_section_pfn"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:register_page_bootmem_info_section"
      ]
    },
    {
      "addr": 18446744071581869395,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__copy_gigantic_page",
        "mm/migrate.c:__copy_gigantic_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581918536,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582001233,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582006724,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582028267,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582029758,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582820046,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582827185,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586123622,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_handle_memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586330563,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587066978,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_mem_block_under_node_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587075439,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:add_memory_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587880991,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588838646,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589173314,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1212",
      "file": "drivers/ras/cec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_add_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992346,
      "name": "__nr_to_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071581798960,
      "name": "__nr_to_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071581860448,
      "name": "__nr_to_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct mem_section * __nr_to_section(long unsigned int nr)
```

```json
{
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579396314,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579404189,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_check_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408531,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579412618,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579976072,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "kernel/power/snapshot.c:mark_nosave_pages"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:saveable_page"
      ]
    },
    {
      "addr": 18446744071580120616,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_map_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580541955,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293126,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:try_ram_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581462394,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581516836,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581600761,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581671950,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581729394,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:take_page_off_buddy",
        "mm/page_alloc.c:pfn_range_valid_contig",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask",
        "mm/page_alloc.c:get_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591684741,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581791147,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581847197,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:clear_subsection_map",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:__section_nr"
      ],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_activate",
        "mm/sparse.c:section_activate",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:check_usemap_section_nr",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:subsection_map_init",
        "mm/sparse.c:next_present_section_nr"
      ]
    },
    {
      "addr": 18446744071581907315,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_memory_block",
        "mm/memory_hotplug.c:scan_movable_pages",
        "mm/memory_hotplug.c:test_pages_in_a_zone",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:find_biggest_section_pfn",
        "mm/memory_hotplug.c:find_smallest_section_pfn"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:register_page_bootmem_info_section"
      ]
    },
    {
      "addr": 18446744071581915523,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__copy_gigantic_page",
        "mm/migrate.c:__copy_gigantic_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581965243,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582051055,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582055572,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582077007,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582078414,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582892942,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582899950,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586242886,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_handle_memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586448643,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587151577,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_mem_block_under_node_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612453642,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_dev_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587941983,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588854822,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589170080,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1250",
      "file": "drivers/ras/cec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_add_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591294291,
      "name": "__nr_to_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071581846864,
      "name": "__nr_to_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071581905408,
      "name": "__nr_to_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct mem_section * __nr_to_section(long unsigned int nr)
```

```json
{
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579395945,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579407273,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410601,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579415673,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579970361,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580124057,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580545001,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581310953,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581536992,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581582505,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581694089,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581751788,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:take_page_off_buddy",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask",
        "mm/page_alloc.c:get_pfnblock_flags_mask",
        "mm/page_alloc.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581758841,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:test_pages_in_a_zone",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:pfn_to_online_page",
        "mm/memory_hotplug.c:pfn_valid"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:section_taint_zone_device",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ]
    },
    {
      "addr": 18446744071581818939,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581877846,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:__section_nr"
      ],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:check_usemap_section_nr",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:subsection_map_init",
        "mm/sparse.c:next_present_section_nr"
      ]
    },
    {
      "addr": 18446744071581937161,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581991744,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582067033,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582919833,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586117737,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586331849,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587038969,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_mem_block_under_node_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614595429,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_dev_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587821897,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588741929,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589063001,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1314",
      "file": "drivers/ras/cec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:pfn_valid"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581753056,
      "name": "__nr_to_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071581877696,
      "name": "__nr_to_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct mem_section * __nr_to_section(long unsigned int nr)
```

```json
{
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579458127,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579469879,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579473383,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579478566,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580101999,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580266998,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580716662,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581556150,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581798135,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581847999,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581966263,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582032135,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:take_page_off_buddy",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:set_pfnblock_flags_mask",
        "mm/page_alloc.c:get_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582040832,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:test_pages_in_a_zone",
        "mm/memory_hotplug.c:adjust_present_page_count",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:pfn_to_online_page"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:section_taint_zone_device"
      ]
    },
    {
      "addr": 18446744071582104327,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582169446,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:online_mem_sections"
      ],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:check_usemap_section_nr",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:subsection_map_init",
        "mm/sparse.c:next_present_section_nr"
      ]
    },
    {
      "addr": 18446744071582293928,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582377359,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592228746,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "mm/bootmem_info.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/bootmem_info.c:register_page_bootmem_info_node",
        "mm/bootmem_info.c:register_page_bootmem_info_node"
      ]
    },
    {
      "addr": 18446744071583254471,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586617558,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586851919,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587606671,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_mem_block_under_node_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615552426,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_dev_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588426343,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589432391,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589781238,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1352",
      "file": "drivers/ras/cec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:pfn_valid"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582033904,
      "name": "__nr_to_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071582169296,
      "name": "__nr_to_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071592228746,
      "name": "__nr_to_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct mem_section * __nr_to_section(long unsigned int nr)
```

```json
{
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579538094,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579546869,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_check_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579552382,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579557250,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580249555,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580928640,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581907748,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:try_ram_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582186790,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582288877,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582384904,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582461328,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:put_page_back_buddy",
        "mm/page_alloc.c:take_page_off_buddy",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:split_free_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594687051,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:adjust_present_page_count",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:pfn_to_online_page"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:section_taint_zone_device"
      ]
    },
    {
      "addr": 18446744071582548430,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582627229,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:online_mem_sections"
      ],
      "caller_func": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:check_usemap_section_nr",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:subsection_map_init",
        "mm/sparse.c:next_present_section_nr"
      ]
    },
    {
      "addr": 18446744071582779861,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582896545,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594008228,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "mm/bootmem_info.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/bootmem_info.c:register_page_bootmem_info_node",
        "mm/bootmem_info.c:register_page_bootmem_info_node"
      ]
    },
    {
      "addr": 18446744071583755679,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kclist_add_private"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587882396,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588139252,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588945897,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_mem_block_under_node_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617358701,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:add_boot_memory_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589827781,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590911863,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591293245,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1395",
      "file": "drivers/ras/cec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_add_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582463040,
      "name": "__nr_to_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071582627008,
      "name": "__nr_to_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071594008228,
      "name": "__nr_to_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579654453,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_check_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579659095,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579664329,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580449449,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:saveable_page",
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581221280,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582342500,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:try_ram_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582483094,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582673103,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582767426,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:vmf_insert_pfn_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582893063,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582975248,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:put_page_back_buddy",
        "mm/page_alloc.c:take_page_off_buddy",
        "mm/page_alloc.c:init_unavailable_range",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:reserve_bootmem_region",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:split_free_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596423746,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:adjust_present_page_count",
        "mm/memory_hotplug.c:move_pfn_range_to_zone",
        "mm/memory_hotplug.c:move_pfn_range_to_zone",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:pfn_to_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596452762,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:check_usemap_section_nr",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:subsection_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583449068,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627900428,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "mm/bootmem_info.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/bootmem_info.c:register_page_bootmem_info_node",
        "mm/bootmem_info.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584371791,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kclist_add_private"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589231260,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589528896,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590461273,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_mem_block_under_node_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628096645,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:add_boot_memory_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592609961,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593043731,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1711",
      "file": "drivers/ras/cec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_add_elem"
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
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579668668,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_check_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579673305,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579678469,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580519481,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:saveable_page",
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315712,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582544884,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:try_ram_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582694118,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071619609839,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:init_unavailable_range",
        "mm/mm_init.c:reserve_bootmem_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582890576,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:fast_isolate_freepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582983746,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583108368,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583187104,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:put_page_back_buddy",
        "mm/page_alloc.c:take_page_off_buddy",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:__isolate_free_page",
        "mm/page_alloc.c:free_unref_page_prepare",
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:steal_suitable_fallback",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:split_free_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596963772,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:adjust_present_page_count",
        "mm/memory_hotplug.c:move_pfn_range_to_zone",
        "mm/memory_hotplug.c:move_pfn_range_to_zone",
        "mm/memory_hotplug.c:pfn_to_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583363023,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_remove_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:check_usemap_section_nr",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:subsection_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583668900,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619663467,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "mm/bootmem_info.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/bootmem_info.c:register_page_bootmem_info_node",
        "mm/bootmem_info.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584600111,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kclist_add_private"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589527980,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589829967,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590784137,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_mem_block_under_node_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619862565,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:add_boot_memory_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593040550,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593495827,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1836",
      "file": "drivers/ras/cec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_add_elem"
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
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579700617,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_check_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579707201,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579712868,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580580496,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:saveable_page",
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581421904,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582715255,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:try_ram_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582867974,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071621913917,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:init_unavailable_range",
        "mm/mm_init.c:reserve_bootmem_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583062448,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_migratepages",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:isolate_freepages",
        "mm/compaction.c:fast_isolate_freepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583159106,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:vmf_insert_pfn_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583297322,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583341399,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:unreserve_highatomic_pageblock",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:free_pcppages_bulk",
        "mm/page_alloc.c:set_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597891660,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:adjust_present_page_count",
        "mm/memory_hotplug.c:move_pfn_range_to_zone",
        "mm/memory_hotplug.c:move_pfn_range_to_zone",
        "mm/memory_hotplug.c:pfn_to_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583599503,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_remove_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:check_usemap_section_nr",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:subsection_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583863290,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621969523,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "mm/bootmem_info.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/bootmem_info.c:register_page_bootmem_info_node",
        "mm/bootmem_info.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584831871,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kclist_add_private"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589835532,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590166965,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591126937,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_mem_block_under_node_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622171125,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:add_boot_memory_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593791724,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594242979,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1847",
      "file": "drivers/ras/cec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_add_elem"
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
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490342036,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/arm64/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/init.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492622428,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492685788,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492863672,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask",
        "mm/page_alloc.c:get_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503918836,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492967824,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_gigantic_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503920564,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:subsection_map_init",
        "mm/sparse.c:__section_nr",
        "mm/sparse.c:present_section_nr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503905932,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493233004,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493244304,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494152356,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499129576,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_mem_sect_under_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499136484,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:memory_block_action"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282594108,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/powerpc/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/stacktrace.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282718808,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/powerpc/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/pgtable.c:maybe_pte_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297806652,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/powerpc/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/init_64.c:vmemmap_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282741056,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/powerpc/mm/book3s64/hash_utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/hash_utils.c:hash_page_do_lazy_icache"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283191272,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/powerpc/platforms/pseries/hotplug-memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_remove_memblock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284778032,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285639768,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_prepare_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285701336,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285942972,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286020348,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286126732,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286283968,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask",
        "mm/page_alloc.c:get_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297813808,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286388672,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:prep_compound_gigantic_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297816260,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_activate",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:subsection_map_init",
        "mm/sparse.c:__section_nr",
        "mm/sparse.c:present_section_nr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286557032,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:test_pages_in_a_zone",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:register_page_bootmem_info_node",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286564028,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286635420,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286753568,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286765684,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286790728,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286800232,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286804336,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286805492,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287821568,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287832108,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292319712,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_mem_sect_under_node"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292327432,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:memory_subsys_online",
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293214476,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_map_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294759740,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295120872,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa"
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
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272494550,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_prepare_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272512580,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272647500,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272691432,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272742082,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vmf_insert_pfn_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272808762,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask",
        "mm/page_alloc.c:get_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270890122,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272877496,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270698546,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:subsection_map_init",
        "mm/sparse.c:__section_nr",
        "mm/sparse.c:present_section_nr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272951566,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273003262,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273020084,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273025282,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273026886,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273027642,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273622282,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273625234,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276990778,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_map_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277925664,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
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
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579361021,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371012,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579389772,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398468,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579913430,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:saveable_page",
        "kernel/power/snapshot.c:clear_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580438280,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581039153,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201677,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581252075,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581326623,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581444411,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask",
        "mm/page_alloc.c:get_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589773121,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581506470,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589780060,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:subsection_map_init",
        "mm/sparse.c:__section_nr",
        "mm/sparse.c:present_section_nr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589758992,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:test_pages_in_a_zone",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:register_page_bootmem_info_node",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622355,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581671396,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581745187,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581753613,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581769677,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581776609,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581778624,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582483736,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582491297,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585370648,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586059987,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_mem_sect_under_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586065932,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:memory_subsys_online",
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587616985,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587896572,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/ras/cec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_add_elem"
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
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579292073,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301204,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319324,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327764,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579852662,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:saveable_page",
        "kernel/power/snapshot.c:clear_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580385352,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580986433,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581148429,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581198731,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581270383,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581386779,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask",
        "mm/page_alloc.c:get_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589495944,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581448662,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589502883,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:subsection_map_init",
        "mm/sparse.c:__section_nr",
        "mm/sparse.c:present_section_nr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589483216,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:test_pages_in_a_zone",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:register_page_bootmem_info_node",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563651,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581610868,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581683811,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581692237,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581708301,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581714785,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581716784,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582420968,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582428529,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585905939,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_mem_sect_under_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585911884,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:memory_subsys_online",
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586697640,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587385001,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587615852,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/ras/cec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_add_elem"
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
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579360941,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370932,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579389692,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398388,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579905926,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:saveable_page",
        "kernel/power/snapshot.c:clear_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580429528,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581030353,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581192877,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581243275,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581317823,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581435611,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask",
        "mm/page_alloc.c:get_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590216529,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581497782,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590223468,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:subsection_map_init",
        "mm/sparse.c:__section_nr",
        "mm/sparse.c:present_section_nr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590202400,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:test_pages_in_a_zone",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:register_page_bootmem_info_node",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613667,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581662708,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581736499,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581744925,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581760989,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767921,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581769936,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582474216,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582481777,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585366744,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585559400,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586245635,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_mem_sect_under_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586250652,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:memory_subsys_online",
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587004280,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587942153,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588229868,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/ras/cec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_add_elem"
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
  "name": "__nr_to_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579369373,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579379412,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398220,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406884,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579951990,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:saveable_page",
        "kernel/power/snapshot.c:clear_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580485112,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581091793,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581256157,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306891,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581381798,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581500107,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_one_page",
        "mm/page_alloc.c:set_pfnblock_flags_mask",
        "mm/page_alloc.c:get_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590266892,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581564755,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590273826,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:sparse_add_section",
        "mm/sparse.c:section_deactivate",
        "mm/sparse.c:offline_mem_sections",
        "mm/sparse.c:online_mem_sections",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:memory_present",
        "mm/sparse.c:subsection_map_init",
        "mm/sparse.c:__section_nr",
        "mm/sparse.c:present_section_nr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590252795,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:test_pages_in_a_zone",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:register_page_bootmem_info_node",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581681458,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581729076,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581804755,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581813181,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581829869,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:pfn_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581836785,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581838800,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582554776,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582562331,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585474072,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585667368,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586355651,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_mem_sect_under_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586361596,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:memory_subsys_online",
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587111448,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588057433,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588365196,
      "name": "__nr_to_section",
      "external": false,
      "loc": "include/linux/mmzone.h:1235",
      "file": "drivers/ras/cec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_add_elem"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct mem_section * __nr_to_section(long unsigned int nr)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct mem_section * __nr_to_section(long unsigned int nr)
```
</details>
</li>
</ul>
