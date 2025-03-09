# Function: <code>node_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579064165,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:398",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579116357,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:398",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119326,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:398",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595031789,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:398",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595066985,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:398",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595082607,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:398",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_workqueues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580492714,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:398",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:is_pageblock_removable_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580570842,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:398",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:zone_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580600149,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:398",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580647315,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:398",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:sysfs_compact_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587337509,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:398",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_index_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587360974,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:398",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587338792,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:398",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:try_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580888225,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:398",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SyS_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595153469,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:398",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583283557,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:398",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583609304,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:398",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584297589,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:398",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584483423,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:398",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/node.c:register_one_node",
        "drivers/base/node.c:register_one_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586156038,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:398",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579060581,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579116090,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119159,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595197456,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595234824,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595249945,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_workqueues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580599583,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:is_pageblock_removable_nolock",
        "mm/page_alloc.c:__build_all_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580663731,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580702181,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580752563,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:sysfs_compact_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587836021,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_index_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587861970,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587841415,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581018412,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SyS_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595326774,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583594485,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583932432,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584643094,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584830708,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_one_node",
        "drivers/base/node.c:register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586568982,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579059621,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579114702,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579117849,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595440346,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595477983,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595494031,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580666623,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:is_pageblock_removable_nolock",
        "mm/page_alloc.c:__build_all_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580731011,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580767989,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580817907,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:sysfs_compact_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588051141,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_index_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588076682,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588056222,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581092856,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SYSC_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588057205,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583731672,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584073939,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584829142,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585023968,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_one_node",
        "drivers/base/node.c:register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586750534,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:407",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579051569,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596328582,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106782,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109896,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596361110,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596399562,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596415198,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580699855,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:is_pageblock_removable_nolock",
        "mm/page_alloc.c:__build_all_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580766890,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580808197,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580858291,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:sysfs_compact_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588278309,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_index_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588303153,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588282887,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581139666,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SYSC_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588283936,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583768340,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583774834,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584140371,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584918816,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585108931,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586877814,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579060577,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602646696,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119955,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579123210,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602678985,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602719233,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602739918,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580548722,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580785331,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:is_pageblock_removable_nolock",
        "mm/page_alloc.c:__build_all_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580854234,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897410,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580949299,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:sysfs_compact_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588848039,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581261665,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SYSC_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588849174,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584028148,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584034898,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584414645,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585340203,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585535140,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587366438,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579064689,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602816625,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127675,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579131851,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602850453,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602891940,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579439455,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:store_smt_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602912435,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580635608,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897254,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580991751,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581033285,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581085459,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:sysfs_compact_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581386095,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:is_mem_section_removable",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581407810,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603003454,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584225264,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584232174,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584638033,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585582907,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585778629,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587670138,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579069265,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604611659,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134349,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138498,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141573,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604647274,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604689298,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579473139,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:store_smt_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604710043,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580696894,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580971862,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581068362,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581110853,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581163363,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:sysfs_compact_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581470164,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:is_mem_section_removable",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581491298,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604801995,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584314912,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584321870,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584737121,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585706699,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585911745,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_mem_sect_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587801419,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579077521,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604707219,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145119,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150169,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153220,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604745032,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604789095,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579491832,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604810359,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:queue_work_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580762967,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581131552,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581175557,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581234247,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:sysfs_compact_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581390180,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581585968,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:is_mem_section_removable",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581599157,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604905292,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584509804,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584516782,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584939105,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585934540,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586152754,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_memory_block_under_nodes",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_set_perf_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588106634,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579079521,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604719606,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147375,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152592,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579155774,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604758431,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604814785,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579517768,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579637334,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580813911,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581189296,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581233685,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581292775,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:sysfs_compact_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581451124,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581623722,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581649408,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:is_mem_section_removable",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581669732,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604939251,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584645836,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584652526,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585074897,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585378352,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586078899,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586301234,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_set_perf_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588312330,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579091297,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609066401,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165729,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579167995,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:srat_detect_node",
        "arch/x86/kernel/cpu/amd.c:srat_detect_node",
        "arch/x86/kernel/cpu/amd.c:nearby_node",
        "arch/x86/kernel/cpu/amd.c:nearby_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172923,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:srat_detect_node",
        "arch/x86/kernel/cpu/hygon.c:srat_detect_node",
        "arch/x86/kernel/cpu/hygon.c:nearby_node",
        "arch/x86/kernel/cpu/hygon.c:nearby_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609104445,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609153381,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547128,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609178148,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:queue_work_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580937367,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379869,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423269,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581483133,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:sysfs_compact_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581656836,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581780282,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581840715,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591173061,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581889029,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609252554,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:alloc_mem_cgroup_per_node_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582561681,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:io_wq_manager",
        "fs/io-wq.c:io_wq_manager"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585325117,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_call_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585337742,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586086934,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586827379,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587071660,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_set_perf_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591132185,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579093185,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612129768,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579162977,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579164603,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:srat_detect_node",
        "arch/x86/kernel/cpu/amd.c:srat_detect_node",
        "arch/x86/kernel/cpu/amd.c:nearby_node",
        "arch/x86/kernel/cpu/amd.c:nearby_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579169355,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:srat_detect_node",
        "arch/x86/kernel/cpu/hygon.c:srat_detect_node",
        "arch/x86/kernel/cpu/hygon.c:nearby_node",
        "arch/x86/kernel/cpu/hygon.c:nearby_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612169363,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612224040,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579528824,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612243582,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:queue_work_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580934071,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423453,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581466325,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581524189,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:sysfs_compact_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581704996,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581827802,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581891213,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591668850,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581935474,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612318863,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:alloc_mem_cgroup_per_node_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582631806,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:io_wq_manager",
        "fs/io-wq.c:io_wq_manager"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585478461,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_call_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585490990,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586207936,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:alloc_memory_initiator"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586883907,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587156204,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_set_perf_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591217513,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579099377,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614269680,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579170070,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174776,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579177260,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614309876,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614364909,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579533112,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614384182,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:queue_work_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580936775,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581444733,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581486741,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581546317,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:sysfs_compact_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581725828,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591613078,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581856584,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581960978,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614459071,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582660677,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585362109,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585371214,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586082670,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586764179,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587043516,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_set_perf_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591166873,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579123105,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615191854,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203053,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208357,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211148,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615237734,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615296137,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579605462,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615317357,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:queue_work_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580026586,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_init_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581140615,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698781,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581742261,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581809597,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582027940,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592786749,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582149800,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582265783,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615404126,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582985599,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585821453,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585831134,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586579804,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587319315,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587611911,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_set_perf_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587614048,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_group_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592018777,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:414",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int node_state(int node, enum node_states state)
```

```json
{
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579156248,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253203,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579259725,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579262028,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593859266,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ]
    },
    {
      "addr": 18446744071579698272,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617099381,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:queue_work_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580020931,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_placement"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580199524,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_domains_numa_masks_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581414912,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582074237,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582127833,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617161591,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582198403,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582335137,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617177205,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:__build_all_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594685505,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617184945,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugepages_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582620358,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582736560,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582768157,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617196190,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582871701,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586035936,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587007761,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_call_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587021637,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587839876,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588634047,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588951680,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:register_cpu_under_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_set_perf_attrs"
      ],
      "caller_func": [
        "drivers/base/node.c:node_dev_init"
      ]
    },
    {
      "addr": 18446744071588954086,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_group_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593784443,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593859266,
      "name": "node_state.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071593880769,
      "name": "node_state.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071594286092,
      "name": "node_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071594364271,
      "name": "node_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579206136,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314899,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321917,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324300,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627729157,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579823293,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627760938,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:queue_work_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580189787,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_placement"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580390372,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_domains_numa_masks_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580688168,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580694830,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/profile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581769056,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582359869,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582549693,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:run_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582602969,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627848025,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582651275,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:__kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582685075,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582919515,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627868145,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596422065,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627879989,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugepages_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583120488,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583139967,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583201831,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583246642,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:alloc_misplaced_dst_page",
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583262345,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:set_node_memory_tier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627894776,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583420149,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586871737,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588177425,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_call_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588193608,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589182013,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590103288,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590201540,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071628096407,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_dev_init",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:register_cpu_under_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_set_perf_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590469574,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_group_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593149931,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__napi_alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593591471,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_page_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595725579,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579210648,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322094,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329882,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579332860,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619488357,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579872365,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619521770,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:queue_work_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580254970,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_placement"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580458958,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_domains_numa_masks_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580764754,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580771451,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/profile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581930852,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582563219,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582754893,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:run_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582810873,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619618140,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:free_area_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619624871,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582860807,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:__kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582894691,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583135492,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583181439,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:__page_frag_cache_refill",
        "mm/page_alloc.c:__page_frag_cache_refill",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596962193,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:__try_online_node",
        "mm/memory_hotplug.c:__try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619643157,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugepages_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583331176,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583350226,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583420305,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583461347,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:alloc_misplaced_dst_folio",
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583482697,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:set_node_memory_tier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583641413,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588453457,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_call_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588469592,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589476075,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590407312,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590411871,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/iommu/amd/io_pgtable_v2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590416872,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590441252,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:alloc_pgtable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590523025,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071619862327,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_dev_init",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:register_cpu_under_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_set_perf_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590792502,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_group_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593603645,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__napi_alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594064723,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_page_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596251531,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579239864,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579352001,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579359586,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362921,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621784709,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579910285,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580072210,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_work_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580518606,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_domains_numa_masks_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580850498,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580857515,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/profile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582057364,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582734083,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582923117,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:run_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582985449,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621922397,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:free_area_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621929015,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583066547,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:compact_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583318548,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583365235,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597889771,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:__try_online_node",
        "mm/memory_hotplug.c:__try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583387547,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_large_node",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621950629,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugepages_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583586875,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_mpol",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583654432,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:alloc_misplaced_dst_folio",
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583675545,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:set_node_memory_tier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583836493,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588750417,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_call_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588766936,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589783039,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target",
        "drivers/acpi/numa/hmat.c:hmat_update_target_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590751334,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590755983,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/iommu/amd/io_pgtable_v2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590760968,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590787604,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:alloc_pgtable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590877697,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071622170887,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_dev_init",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:register_cpu_under_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_set_perf_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591135846,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_group_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594378237,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__napi_alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594852244,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_page_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597133963,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:421",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510815812,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/arm64/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/setup.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510877580,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_numa_init",
        "kernel/workqueue.c:queue_work_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492134504,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492570192,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492623888,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492699076,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:sysfs_compact_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492858104,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493070672,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503906064,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493113612,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510979244,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496891604,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496899880,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497478176,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497652472,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336511133532,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/acpi/arm64/iort.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/arm64/iort.c:arm_smmu_v3_set_proximity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499134904,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_set_perf_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501660520,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/of/of_numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/of_numa.c:of_node_to_nid"
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:464",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:464",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:464",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:464",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:464",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:464",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:464",
      "file": "drivers/pci/pci-driver.c",
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302383684,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/powerpc/kernel/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/sysfs.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282610352,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/powerpc/kernel/pci-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/pci-common.c:pcibios_alloc_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282832036,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/powerpc/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/numa.c:find_and_online_cpu_nid",
        "arch/powerpc/mm/numa.c:hot_add_scn_to_nid",
        "arch/powerpc/mm/numa.c:mem_topology_setup",
        "arch/powerpc/mm/numa.c:numa_setup_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283628152,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285342780,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285878992,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285944412,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286032648,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:sysfs_compact_node"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286278468,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286512140,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286550140,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:is_mem_section_removable",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286589724,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302637364,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290979280,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290990184,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292325388,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:register_memory_node_under_compute_node"
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:464",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:464",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:464",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:464",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:464",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:464",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:464",
      "file": "drivers/pci/pci-driver.c",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579079873,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604645896,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147743,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152960,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156142,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604684710,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604728727,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579491432,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579613638,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580782711,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581158144,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581202533,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581261623,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:sysfs_compact_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581419972,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581592458,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618144,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:is_mem_section_removable",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638468,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604844711,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584596316,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584603006,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585004385,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585170320,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585840019,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586064482,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_set_perf_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587915978,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579012561,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604613830,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579078967,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579084529,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579087011,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604652264,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604696457,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579420296,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579542604,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580728887,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581105008,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581149285,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581208279,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:sysfs_compact_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581362484,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581533898,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581559472,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:is_mem_section_removable",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581579428,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604813772,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584526124,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584532814,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584919969,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585113312,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585699059,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585910434,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_set_perf_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587632122,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579079457,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604723688,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147295,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152512,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579155694,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604762294,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604806294,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579491352,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579610918,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580773959,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581149344,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581193733,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581252823,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:sysfs_compact_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581411172,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583770,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581609456,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:is_mem_section_removable",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581629780,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604921895,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584595996,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584602686,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585026481,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586028915,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586249314,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:register_memory_node_under_compute_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588249386,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
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
  "name": "node_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579083553,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/quirks.c:quirk_amd_nb_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604723718,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152431,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157648,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160830,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604762551,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/kernel/setup_percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604818913,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579523848,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:cpuhp_smt_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579641814,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:workqueue_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580832183,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581212000,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:node_reclaim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581257013,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581316583,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:sysfs_compact_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474964,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__build_all_zonelists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581649357,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581675643,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:is_mem_section_removable",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581696084,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604943422,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_init",
        "mm/memcontrol.c:mem_cgroup_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584703692,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584710382,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/pci/pci-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-sysfs.c:numa_node_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585132641,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/acpi/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585436080,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586136867,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586360146,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:__register_one_node",
        "drivers/base/node.c:node_hugetlb_work",
        "drivers/base/node.c:unregister_cpu_under_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:register_memory_node_under_compute_node",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_set_perf_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588384810,
      "name": "node_state",
      "external": false,
      "loc": "include/linux/nodemask.h:413",
      "file": "arch/x86/pci/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/acpi.c:pci_acpi_scan_root"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int node_state(int node, enum node_states state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int node_state(int node, enum node_states state)
```
</details>
</li>
</ul>
