# Function: <code>pfn_valid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579277641,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
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
      "addr": 18446744071579285765,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_check_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309116,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579698917,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
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
      "addr": 18446744071580121509,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587352114,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:reserve_bootmem_region",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580602313,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580634037,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
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
      "addr": 18446744071580687465,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
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
      "addr": 18446744071580789290,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
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
      "addr": 18446744071587338210,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:register_page_bootmem_info_node",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580884821,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580900372,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580949269,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595156249,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_init_reserved_areas",
        "mm/cma.c:cma_init_reserved_areas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975333,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580977550,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581499003,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
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
      "addr": 18446744071583784946,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583909987,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584485178,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1127",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_online",
        "drivers/base/memory.c:store_soft_offline_page"
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
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579276997,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
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
      "addr": 18446744071579285477,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_check_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308845,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579725471,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
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
      "addr": 18446744071580155509,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580541891,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580601000,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:reserve_bootmem_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580705375,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580741187,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:__reset_isolation_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580802897,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
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
      "addr": 18446744071580917949,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
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
      "addr": 18446744071587836890,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:register_page_bootmem_info_node",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581010396,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581042062,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581103797,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595329805,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_init_reserved_areas",
        "mm/cma.c:cma_init_reserved_areas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581129477,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581131663,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581684171,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
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
      "addr": 18446744071584111048,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584241685,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584832651,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1199",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:store_soft_offline_page",
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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579292325,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
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
      "addr": 18446744071579300863,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_check_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324077,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579752992,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
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
      "addr": 18446744071580195909,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580605939,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580668016,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:reserve_bootmem_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580771224,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580807002,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:__reset_isolation_suitable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580867942,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
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
      "addr": 18446744071580986245,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
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
      "addr": 18446744071588052007,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:register_page_bootmem_info_node",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581084457,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581117209,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581178949,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595577972,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_init_reserved_areas",
        "mm/cma.c:cma_init_reserved_areas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581204549,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581206719,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581772366,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
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
      "addr": 18446744071584259013,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584423125,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585025959,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1177",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:store_soft_offline_page",
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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579289833,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298635,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_check_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321437,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579749136,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
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
      "addr": 18446744071580203589,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580635797,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580701376,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:reserve_bootmem_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580912704,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
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
      "addr": 18446744071581032002,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
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
      "addr": 18446744071588278783,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:register_page_bootmem_info_node",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581132027,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581165274,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581227285,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596505607,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_init_reserved_areas",
        "mm/cma.c:cma_init_reserved_areas"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581253381,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581255258,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581826769,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
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
      "addr": 18446744071584337061,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584506967,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585110673,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:store_soft_offline_page",
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586563453,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586860939,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1218",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pfn_valid(long unsigned int pfn)
```

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579309177,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
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
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_res_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344893,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579782447,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
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
      "addr": 18446744071580254981,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580715608,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580786801,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page"
      ],
      "caller_func": [
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:reserve_bootmem_region"
      ]
    },
    {
      "addr": 18446744071581011865,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
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
      "addr": 18446744071581141551,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
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
      "addr": 18446744071588846427,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:register_page_bootmem_info_node",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ]
    },
    {
      "addr": 18446744071581247309,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581292197,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581358293,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379947,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
      "file": "mm/cma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/cma.c:cma_init_reserved_areas",
        "mm/cma.c:cma_init_reserved_areas"
      ]
    },
    {
      "addr": 18446744071581385397,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581387483,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581976386,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
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
      "addr": 18446744071584741350,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_do_proc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584916980,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585536392,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:store_soft_offline_page",
        "drivers/base/memory.c:memory_block_action"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587030976,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587348780,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1231",
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
      "addr": 18446744071580757584,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071581235296,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071581379947,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pfn_valid(long unsigned int pfn)
```

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579321051,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
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
      "addr": 18446744071579330168,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_res_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579348114,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356605,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579814320,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:clear_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:saveable_page"
      ]
    },
    {
      "addr": 18446744071580315429,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580848019,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580920059,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page"
      ],
      "caller_func": [
        "mm/page_alloc.c:zero_resv_unavail",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:reserve_bootmem_region"
      ]
    },
    {
      "addr": 18446744071581145483,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
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
      "addr": 18446744071581279870,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
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
      "addr": 18446744071589225813,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ]
    },
    {
      "addr": 18446744071581391513,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439235,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581506741,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581529931,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
      "file": "mm/cma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/cma.c:cma_init_reserved_areas",
        "mm/cma.c:cma_init_reserved_areas"
      ]
    },
    {
      "addr": 18446744071581535829,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537930,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582157669,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582163783,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
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
      "addr": 18446744071584969787,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585148418,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585780666,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:store_soft_offline_page",
        "drivers/base/memory.c:memory_block_action"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587329075,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587652388,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1238",
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
      "addr": 18446744071579816100,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071580893680,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071581381456,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071581529931,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
int pfn_valid(long unsigned int pfn)
```

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579345355,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
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
      "addr": 18446744071579356360,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_res_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579375058,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383757,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579861072,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:clear_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:saveable_page"
      ]
    },
    {
      "addr": 18446744071580368005,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580916899,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995707,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page"
      ],
      "caller_func": [
        "mm/page_alloc.c:zero_pfn_range",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:reserve_bootmem_region"
      ]
    },
    {
      "addr": 18446744071581225323,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
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
      "addr": 18446744071581362398,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
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
      "addr": 18446744071589468361,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:__add_pages",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ]
    },
    {
      "addr": 18446744071581474975,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581522822,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581592613,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581615723,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
      "file": "mm/cma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/cma.c:cma_init_reserved_areas",
        "mm/cma.c:cma_init_reserved_areas"
      ]
    },
    {
      "addr": 18446744071581621877,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581623978,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582251429,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582258775,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
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
      "addr": 18446744071585074107,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585259314,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585912666,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:memory_block_action"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587507411,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587782388,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1246",
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
      "addr": 18446744071579854448,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071580968320,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071581465568,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071581615723,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pfn_valid(long unsigned int pfn)
```

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579360861,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
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
      "addr": 18446744071579371813,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390541,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579399233,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579895363,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:clear_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:saveable_page"
      ]
    },
    {
      "addr": 18446744071580420709,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581015010,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581224647,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581298991,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
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
      "addr": 18446744071581414504,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page"
      ],
      "caller_func": [
        "mm/page_alloc.c:zero_pfn_range",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:reserve_bootmem_region"
      ]
    },
    {
      "addr": 18446744071581473672,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
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
      "addr": 18446744071589929469,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:__remove_pages",
        "mm/memory_hotplug.c:find_biggest_section_pfn"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ]
    },
    {
      "addr": 18446744071581589936,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581631765,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581704949,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581727371,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
      "file": "mm/cma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/cma.c:cma_activate_area",
        "mm/cma.c:cma_activate_area"
      ]
    },
    {
      "addr": 18446744071581734325,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581736353,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582416021,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582423626,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
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
      "addr": 18446744071585278389,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585468277,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586154099,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:memory_block_action"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587781286,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588086991,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1338",
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
      "addr": 18446744071579888656,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071581386560,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071581580096,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071581727371,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pfn_valid(long unsigned int pfn)
```

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579365101,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "addr": 18446744071579375093,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579393853,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402545,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579945635,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:clear_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:saveable_page"
      ]
    },
    {
      "addr": 18446744071580469461,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581070290,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283207,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581357759,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "addr": 18446744071581475544,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page"
      ],
      "caller_func": [
        "mm/page_alloc.c:zero_pfn_range",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:reserve_bootmem_region"
      ]
    },
    {
      "addr": 18446744071581535067,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590156685,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581653600,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581702645,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581776421,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581800923,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/cma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/cma.c:cma_activate_area",
        "mm/cma.c:cma_activate_area"
      ]
    },
    {
      "addr": 18446744071581807845,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581809873,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582514965,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585416325,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585608981,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586302547,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587049701,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587985990,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588292799,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "addr": 18446744071579938912,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071581447504,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071581800923,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pfn_valid(long unsigned int pfn)
```

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579392016,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
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
      "addr": 18446744071579403591,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_check_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408029,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411921,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579991342,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
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
      "addr": 18446744071580553877,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581251125,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:try_ram_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581475526,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581554686,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vmf_insert_pfn_prot"
      ],
      "caller_func": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:vm_normal_page_pmd"
      ]
    },
    {
      "addr": 18446744071581680623,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page"
      ],
      "caller_func": [
        "mm/page_alloc.c:init_unavailable_range",
        "mm/page_alloc.c:reserve_bootmem_region"
      ]
    },
    {
      "addr": 18446744071581744353,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:destroy_compound_gigantic_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581863264,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:scan_movable_pages"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ]
    },
    {
      "addr": 18446744071581869369,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__copy_gigantic_page",
        "mm/migrate.c:__copy_gigantic_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581918510,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582001109,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
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
      "addr": 18446744071582029736,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582820021,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586123599,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_handle_memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586330544,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587880965,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588838613,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589173291,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1322",
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
      "addr": 18446744071579992682,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071581514048,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071581655968,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071581862944,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int pfn_valid(long unsigned int pfn)
```

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579396288,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
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
      "addr": 18446744071579404167,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_check_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408509,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579412593,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579976046,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
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
      "addr": 18446744071580120593,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_map_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580541925,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293093,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:try_ram_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581516809,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581600739,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user"
      ],
      "caller_func": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd"
      ]
    },
    {
      "addr": 18446744071581671928,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581715625,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page"
      ],
      "caller_func": [
        "mm/page_alloc.c:init_unavailable_range",
        "mm/page_alloc.c:reserve_bootmem_region"
      ]
    },
    {
      "addr": 18446744071581791125,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581907808,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:scan_movable_pages"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ]
    },
    {
      "addr": 18446744071581915497,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__copy_gigantic_page",
        "mm/migrate.c:__copy_gigantic_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581965217,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582051033,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
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
      "addr": 18446744071582078392,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582892923,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586242863,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_handle_memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586448624,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587941957,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588854789,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589170057,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1360",
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
      "addr": 18446744071591294721,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071581559024,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071581704128,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071581907488,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int pfn_valid(long unsigned int pfn)
```

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579395920,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ]
    },
    {
      "addr": 18446744071579407248,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags"
      ]
    },
    {
      "addr": 18446744071579410576,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ]
    },
    {
      "addr": 18446744071579415648,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ]
    },
    {
      "addr": 18446744071579970336,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:saveable_page",
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ]
    },
    {
      "addr": 18446744071580124032,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_map_resource"
      ]
    },
    {
      "addr": 18446744071580544976,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ]
    },
    {
      "addr": 18446744071581310928,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap"
      ]
    },
    {
      "addr": 18446744071581536965,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581582480,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd"
      ]
    },
    {
      "addr": 18446744071581694064,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap_pfn_apply"
      ]
    },
    {
      "addr": 18446744071581725328,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:init_unavailable_range",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:reserve_bootmem_region"
      ]
    },
    {
      "addr": 18446744071581754128,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ]
    },
    {
      "addr": 18446744071581818917,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581937136,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ]
    },
    {
      "addr": 18446744071581991718,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582067008,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ]
    },
    {
      "addr": 18446744071582919808,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "fs/proc/kcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586117712,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586331824,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587821872,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns",
        "drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin"
      ]
    },
    {
      "addr": 18446744071588741904,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_ce_error"
      ]
    },
    {
      "addr": 18446744071589062976,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1430",
      "file": "drivers/ras/cec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ras/cec.c:cec_add_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579395920,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071579407248,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071579410576,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071579415648,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071579970336,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071580124032,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071580544976,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071581310928,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071581582480,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071581694064,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071581725328,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071581754128,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071581937136,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071582067008,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071582919808,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071586117712,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071586331824,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071587821872,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071588741904,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071589062976,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int pfn_valid(long unsigned int pfn)
```

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579461983,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ]
    },
    {
      "addr": 18446744071579469824,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags"
      ]
    },
    {
      "addr": 18446744071579473328,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ]
    },
    {
      "addr": 18446744071579478528,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ]
    },
    {
      "addr": 18446744071580109737,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "kernel/power/snapshot.c:mark_nosave_pages"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "kernel/power/snapshot.c:mark_nosave_pages"
      ]
    },
    {
      "addr": 18446744071580266960,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_map_resource"
      ]
    },
    {
      "addr": 18446744071580716624,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ]
    },
    {
      "addr": 18446744071581556112,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/iomem.c:memremap"
      ]
    },
    {
      "addr": 18446744071581798080,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581891040,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd"
      ]
    },
    {
      "addr": 18446744071581966208,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vmap_pfn_apply"
      ]
    },
    {
      "addr": 18446744071615383320,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:init_unavailable_range",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:reserve_bootmem_region"
      ],
      "caller_func": [
        "mm/page_alloc.c:init_unavailable_range",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:reserve_bootmem_region"
      ]
    },
    {
      "addr": 18446744071592788142,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    },
    {
      "addr": 18446744071582104272,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:prep_compound_gigantic_page"
      ]
    },
    {
      "addr": 18446744071582293881,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582388277,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure"
      ]
    },
    {
      "addr": 18446744071615408053,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "mm/bootmem_info.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/bootmem_info.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583254416,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "fs/proc/kcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586617520,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586852403,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ]
    },
    {
      "addr": 18446744071588426288,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns",
        "drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin"
      ]
    },
    {
      "addr": 18446744071589432336,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_ce_error"
      ]
    },
    {
      "addr": 18446744071589781200,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1478",
      "file": "drivers/ras/cec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ras/cec.c:cec_add_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579458096,
      "name": "pfn_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071579469824,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071579473328,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071579478528,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071580101968,
      "name": "pfn_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071580266960,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071580716624,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071581556112,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071581798080,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071581847968,
      "name": "pfn_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071581966208,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071581998032,
      "name": "pfn_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071582035440,
      "name": "pfn_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071582104272,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071582377328,
      "name": "pfn_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071583254416,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071586617520,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071586851888,
      "name": "pfn_valid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071588426288,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071589432336,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071589781200,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int pfn_valid(long unsigned int pfn)
```

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579538055,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
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
      "addr": 18446744071579546832,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_check_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579552340,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579557217,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580249514,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:saveable_page"
      ]
    },
    {
      "addr": 18446744071580928581,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581907693,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:try_ram_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582186740,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582288836,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user"
      ],
      "caller_func": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd"
      ]
    },
    {
      "addr": 18446744071582384859,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582438682,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page"
      ],
      "caller_func": [
        "mm/page_alloc.c:init_unavailable_range",
        "mm/page_alloc.c:reserve_bootmem_region"
      ]
    },
    {
      "addr": 18446744071594687010,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582548389,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582779820,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582896485,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
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
      "addr": 18446744071617200292,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
      "file": "mm/bootmem_info.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/bootmem_info.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583755598,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kclist_add_private"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587882301,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588139194,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589827733,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590911813,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591293213,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1524",
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
      "addr": 18446744071593895241,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    },
    {
      "addr": 18446744071582239888,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071582424656,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pfn_valid(long unsigned int pfn)
```

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579654416,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1863",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_check_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579659032,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1863",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579664289,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1863",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580449088,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1863",
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
      "addr": 18446744071581221221,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1863",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582342445,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1863",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:try_ram_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582483055,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1863",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582673057,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1863",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582767224,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1863",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:vmf_insert_pfn_prot"
      ],
      "caller_func": [
        "mm/memory.c:vm_normal_page_pmd"
      ]
    },
    {
      "addr": 18446744071582892795,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1863",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627859798,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1863",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:init_unavailable_range",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:reserve_bootmem_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596423713,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1863",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583448885,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1863",
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
      "addr": 18446744071627900385,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1863",
      "file": "mm/bootmem_info.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/bootmem_info.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584371710,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1863",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kclist_add_private"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589231165,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1863",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589528838,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1863",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592609669,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1863",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593043696,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1863",
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
      "addr": 18446744071582731728,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579668631,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1988",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_check_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579673257,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1988",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579678429,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1988",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580519120,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1988",
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
      "addr": 18446744071581315653,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1988",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582544829,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1988",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:try_ram_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582694079,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1988",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071619609798,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1988",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:init_unavailable_range",
        "mm/mm_init.c:reserve_bootmem_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582884079,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1988",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582983544,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1988",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583108125,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1988",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583156038,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1988",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__pageblock_pfn_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596963731,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1988",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583668725,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1988",
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
      "addr": 18446744071619663434,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1988",
      "file": "mm/bootmem_info.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/bootmem_info.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584600030,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1988",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kclist_add_private"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589527885,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1988",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589829909,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1988",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593040229,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1988",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593495792,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1988",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pfn_valid(long unsigned int pfn)
```

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579700580,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1999",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_check_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579707145,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1999",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579712829,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1999",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580580258,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1999",
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
      "addr": 18446744071581421845,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1999",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582715213,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1999",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:try_ram_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582867935,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1999",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071621913876,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1999",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:init_unavailable_range",
        "mm/mm_init.c:reserve_bootmem_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583055359,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1999",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583158904,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1999",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:vmf_insert_pfn_prot"
      ],
      "caller_func": [
        "mm/memory.c:vm_normal_page_pmd"
      ]
    },
    {
      "addr": 18446744071583297162,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1999",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583338982,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1999",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__pageblock_pfn_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597891627,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1999",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583863189,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1999",
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
      "addr": 18446744071621969482,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1999",
      "file": "mm/bootmem_info.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/bootmem_info.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584831790,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1999",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:kclist_add_private"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589835437,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1999",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590166921,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1999",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593791656,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1999",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594242944,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1999",
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
      "addr": 18446744071583122368,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int pfn_valid(long unsigned int pfn)
```

```json
{
  "name": "pfn_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490341976,
      "name": "pfn_valid",
      "external": true,
      "loc": "arch/arm64/mm/init.c:241",
      "file": "arch/arm64/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/ioremap.c:__ioremap_caller",
        "arch/arm64/mm/mmu.c:kern_addr_valid",
        "arch/arm64/mm/mmu.c:kern_addr_valid",
        "arch/arm64/mm/mmu.c:kern_addr_valid",
        "arch/arm64/mm/mmu.c:phys_mem_access_prot",
        "virt/kvm/kvm_main.c:__kvm_map_gfn",
        "virt/kvm/arm/mmu.c:user_mem_abort",
        "virt/kvm/arm/mmu.c:create_hyp_mappings",
        "virt/kvm/arm/mmu.c:unmap_stage2_range",
        "arch/arm/xen/mm.c:xen_dma_sync_for_device",
        "arch/arm/xen/mm.c:xen_dma_sync_for_cpu",
        "kernel/dma/mapping.c:dma_common_mmap",
        "kernel/dma/mapping.c:dma_common_get_sgtable",
        "kernel/debug/kdb/kdb_support.c:kdb_getphys",
        "kernel/events/core.c:perf_prepare_sample",
        "kernel/iomem.c:memremap",
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/page_alloc.c:zero_pfn_range",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:move_freepages_block",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:reserve_bootmem_region",
        "mm/page_alloc.c:__free_one_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/page_alloc.c:__free_one_page",
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:update_and_free_page",
        "mm/hugetlb.c:alloc_gigantic_page",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:unset_migratetype_isolate",
        "mm/cma.c:cma_init_reserved_areas",
        "mm/cma.c:cma_init_reserved_areas",
        "mm/page_idle.c:page_idle_get_page",
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/base/node.c:get_nid_for_pfn",
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:memory_block_action",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error",
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490341976,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int pfn_valid(long unsigned int pfn)
```

```json
{
  "name": "pfn_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224479480,
      "name": "pfn_valid",
      "external": true,
      "loc": "arch/arm/mm/init.c:176",
      "file": "arch/arm/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/flush.c:__sync_icache_dcache",
        "arch/arm/mm/ioremap.c:__arm_ioremap_pfn_caller",
        "kernel/power/snapshot.c:restore_highmem",
        "kernel/power/snapshot.c:snapshot_write_finalize",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:saveable_page",
        "kernel/power/snapshot.c:saveable_page",
        "kernel/power/snapshot.c:saveable_highmem_page",
        "kernel/power/snapshot.c:saveable_highmem_page",
        "kernel/power/snapshot.c:clear_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/debug/kdb/kdb_support.c:kdb_getphys",
        "kernel/events/core.c:perf_prepare_sample",
        "kernel/iomem.c:memremap",
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/compaction.c:fast_isolate_freepages",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/memory.c:__vm_insert_mixed",
        "mm/memory.c:vmf_insert_pfn_prot",
        "mm/memory.c:vm_normal_page",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:reserve_bootmem_region",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/cma.c:cma_activate_area",
        "mm/cma.c:cma_activate_area",
        "mm/page_idle.c:page_idle_get_page",
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read",
        "fs/pstore/ram_core.c:persistent_ram_new",
        "fs/pstore/ram_core.c:persistent_ram_free",
        "drivers/mtd/nand/raw/nand_base.c:nand_do_write_ops",
        "drivers/mtd/nand/raw/nand_base.c:nand_do_read_ops",
        "drivers/mtd/nand/raw/omap2.c:omap_write_buf_dma_pref",
        "drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error",
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224479480,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
int pfn_valid(long unsigned int pfn)
```

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282594080,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "arch/powerpc/kernel/stacktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055282718800,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "arch/powerpc/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/pgtable.c:maybe_pte_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297806640,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "arch/powerpc/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/init_64.c:vmemmap_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282741048,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "arch/powerpc/mm/book3s64/hash_utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/hash_utils.c:hash_page_do_lazy_icache"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283191256,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "arch/powerpc/platforms/pseries/hotplug-memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_remove_memblock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284778016,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285639760,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_prepare_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285701320,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286020332,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286126712,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page"
      ],
      "caller_func": [
        "mm/page_alloc.c:zero_pfn_range",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:reserve_bootmem_region"
      ]
    },
    {
      "addr": 13835058055286385724,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:prep_compound_gigantic_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286557020,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286564008,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286635408,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286753552,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286790700,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/cma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/cma.c:cma_activate_area",
        "mm/cma.c:cma_activate_area"
      ]
    },
    {
      "addr": 13835058055286800216,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286804344,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286805484,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287821544,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292327428,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293214464,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_map_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294759724,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295120864,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282594080,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 13835058055286241360,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 13835058055286790700,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pfn_valid(long unsigned int pfn)
```

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272494538,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_prepare_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272512568,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272647496,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272691420,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "addr": 18446743936272741948,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "addr": 18446743936272808890,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page"
      ],
      "caller_func": [
        "mm/page_alloc.c:zero_pfn_range",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:reserve_bootmem_region"
      ]
    },
    {
      "addr": 18446743936272877090,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "addr": 18446743936272951558,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273003244,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "addr": 18446743936273020066,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/cma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/cma.c:cma_init_reserved_areas",
        "mm/cma.c:cma_init_reserved_areas"
      ]
    },
    {
      "addr": 18446743936273025270,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273026886,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273027630,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273622270,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273625228,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "addr": 18446743936276990766,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_map_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277925652,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272800964,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446743936273020066,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pfn_valid(long unsigned int pfn)
```

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579361005,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "addr": 18446744071579370997,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579389757,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398449,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579913411,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:clear_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:saveable_page"
      ]
    },
    {
      "addr": 18446744071580438261,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581039138,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581252055,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581326607,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "addr": 18446744071581444392,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page"
      ],
      "caller_func": [
        "mm/page_alloc.c:zero_pfn_range",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:reserve_bootmem_region"
      ]
    },
    {
      "addr": 18446744071581503803,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589758973,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622336,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581671381,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581745157,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581769659,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/cma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/cma.c:cma_activate_area",
        "mm/cma.c:cma_activate_area"
      ]
    },
    {
      "addr": 18446744071581776581,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581778609,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582483701,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585370629,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586065795,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587616966,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587896559,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "addr": 18446744071579906688,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071581416352,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071581769659,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pfn_valid(long unsigned int pfn)
```

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579292057,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "addr": 18446744071579301189,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319309,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327745,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579852643,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:clear_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:saveable_page"
      ]
    },
    {
      "addr": 18446744071580385333,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580986418,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581198711,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581270367,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "addr": 18446744071581386760,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page"
      ],
      "caller_func": [
        "mm/page_alloc.c:zero_pfn_range",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:reserve_bootmem_region"
      ]
    },
    {
      "addr": 18446744071581446107,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589483197,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563632,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581610853,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581683781,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581708283,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/cma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/cma.c:cma_activate_area",
        "mm/cma.c:cma_activate_area"
      ]
    },
    {
      "addr": 18446744071581714757,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581716769,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582420933,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585911747,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586697621,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587384982,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587615839,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "addr": 18446744071579845920,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071581358864,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071581708283,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pfn_valid(long unsigned int pfn)
```

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579360925,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "addr": 18446744071579370917,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579389677,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398369,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579905907,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:clear_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:saveable_page"
      ]
    },
    {
      "addr": 18446744071580429509,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581030338,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581243255,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581317807,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "addr": 18446744071581435592,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page"
      ],
      "caller_func": [
        "mm/page_alloc.c:zero_pfn_range",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:reserve_bootmem_region"
      ]
    },
    {
      "addr": 18446744071581495115,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590202381,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613648,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581662693,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581736469,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581760971,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/cma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/cma.c:cma_activate_area",
        "mm/cma.c:cma_activate_area"
      ]
    },
    {
      "addr": 18446744071581767893,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581769921,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582474181,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585366725,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585559381,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586250515,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587004261,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587942134,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588229855,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "addr": 18446744071579899184,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071581407552,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071581760971,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int pfn_valid(long unsigned int pfn)
```

```json
{
  "name": "pfn_valid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579369357,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "addr": 18446744071579379397,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398205,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "arch/x86/mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:pfn_modify_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406865,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/physaddr.c:__virt_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579951971,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/snapshot.c:clear_free_pages",
        "kernel/power/snapshot.c:create_basic_memory_bitmaps"
      ],
      "caller_func": [
        "kernel/power/snapshot.c:saveable_page"
      ]
    },
    {
      "addr": 18446744071580485093,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581091778,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306871,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:fast_isolate_freepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581381778,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "addr": 18446744071581500088,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:__offline_isolated_pages",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/page_alloc.c:__pageblock_pfn_to_page"
      ],
      "caller_func": [
        "mm/page_alloc.c:zero_pfn_range",
        "mm/page_alloc.c:memmap_init_zone",
        "mm/page_alloc.c:reserve_bootmem_region"
      ]
    },
    {
      "addr": 18446744071581562395,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:prep_compound_gigantic_page",
        "mm/hugetlb.c:update_and_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590252776,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:register_page_bootmem_info_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581681438,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581729061,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581804725,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581829851,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/cma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/cma.c:cma_activate_area",
        "mm/cma.c:cma_activate_area"
      ]
    },
    {
      "addr": 18446744071581836757,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581838785,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582554741,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585474053,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585667349,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586361459,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:soft_offline_page_store",
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587111429,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588057414,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588365183,
      "name": "pfn_valid",
      "external": false,
      "loc": "include/linux/mmzone.h:1345",
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
      "addr": 18446744071579945216,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071581471648,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071581829851,
      "name": "pfn_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int pfn_valid(long unsigned int pfn)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int pfn_valid(long unsigned int pfn)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int pfn_valid(long unsigned int pfn)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
