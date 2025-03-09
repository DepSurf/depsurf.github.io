# Function: <code>__next_mem_pfn_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587359594,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1079",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:memblock_find_dma_reserve",
        "arch/x86/kernel/e820.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587359594,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587860537,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1080",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:memblock_find_dma_reserve",
        "arch/x86/kernel/e820.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587860537,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588075233,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1080",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:memblock_find_dma_reserve",
        "arch/x86/kernel/e820.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588075233,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588301628,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1076",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588301628,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588866885,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1076",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588866885,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589245991,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1084",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589245991,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589488287,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1199",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589488287,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589949009,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1196",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589949009,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590176449,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1196",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590176449,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591194792,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1203",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:memmap_init",
        "mm/page_alloc.c:memmap_init",
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591194792,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591689674,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1162",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:memmap_init",
        "mm/page_alloc.c:memmap_init",
        "mm/sparse.c:sparse_init",
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591689674,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591632524,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1163",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:memmap_init",
        "mm/page_alloc.c:memmap_init",
        "mm/sparse.c:sparse_init",
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591632524,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592806550,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1198",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:memmap_init",
        "mm/page_alloc.c:memmap_init",
        "mm/sparse.c:sparse_init",
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592806550,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594707467,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1203",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:memmap_init",
        "mm/page_alloc.c:memmap_init",
        "mm/sparse.c:sparse_init",
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594707467,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596450496,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1221",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:memmap_init",
        "mm/page_alloc.c:memmap_init",
        "mm/sparse.c:sparse_init",
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596450496,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596991824,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1234",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/mm_init.c:node_map_pfn_alignment",
        "mm/mm_init.c:node_map_pfn_alignment",
        "mm/mm_init.c:free_area_init",
        "mm/mm_init.c:get_pfn_range_for_nid",
        "mm/mm_init.c:get_pfn_range_for_nid",
        "mm/mm_init.c:__absent_pages_in_range",
        "mm/mm_init.c:__absent_pages_in_range",
        "mm/mm_init.c:memmap_init",
        "mm/mm_init.c:memmap_init",
        "mm/mm_init.c:find_zone_movable_pfns_for_nodes",
        "mm/mm_init.c:find_zone_movable_pfns_for_nodes",
        "mm/mm_init.c:find_zone_movable_pfns_for_nodes",
        "mm/mm_init.c:find_zone_movable_pfns_for_nodes",
        "mm/sparse.c:sparse_init",
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596991824,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597920960,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1292",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/mm_init.c:node_map_pfn_alignment",
        "mm/mm_init.c:node_map_pfn_alignment",
        "mm/mm_init.c:free_area_init",
        "mm/mm_init.c:get_pfn_range_for_nid",
        "mm/mm_init.c:get_pfn_range_for_nid",
        "mm/mm_init.c:__absent_pages_in_range",
        "mm/mm_init.c:__absent_pages_in_range",
        "mm/mm_init.c:memmap_init",
        "mm/mm_init.c:memmap_init",
        "mm/mm_init.c:find_zone_movable_pfns_for_nodes",
        "mm/mm_init.c:find_zone_movable_pfns_for_nodes",
        "mm/mm_init.c:find_zone_movable_pfns_for_nodes",
        "mm/mm_init.c:find_zone_movable_pfns_for_nodes",
        "mm/memblock.c:memblock_validate_numa_coverage",
        "mm/memblock.c:memblock_validate_numa_coverage",
        "mm/sparse.c:sparse_init",
        "drivers/iommu/intel/iommu.c:si_domain_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597920960,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492895672,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1196",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492895672,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286295536,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1196",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286295536,
      "name": "__next_mem_pfn_range",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270895218,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1196",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270895218,
      "name": "__next_mem_pfn_range",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 122
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589778737,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1196",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589778737,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589501560,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1196",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589501560,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590222145,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1196",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590222145,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```

```json
{
  "name": "__next_mem_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590272503,
      "name": "__next_mem_pfn_range",
      "external": true,
      "loc": "mm/memblock.c:1196",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:memblock_find_dma_reserve",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "arch/x86/mm/init.c:init_range_memory_mapping",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:find_min_pfn_for_node",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:node_map_pfn_alignment",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:__absent_pages_in_range",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:get_pfn_range_for_nid",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:sparse_memory_present_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590272503,
      "name": "__next_mem_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __next_mem_pfn_range(int * idx, int nid, long unsigned int * out_start_pfn, long unsigned int * out_end_pfn, int * out_nid)
```
</details>
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
