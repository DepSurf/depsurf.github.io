# Function: <code>alloc_pages_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct page * alloc_pages_node(int nid, gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578927790,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:443",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579059679,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:443",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579061865,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:443",
      "file": "arch/x86/kernel/pci-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580182777,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:443",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580350139,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:443",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580438914,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:443",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580513056,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:443",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_kmem_pages_node",
        "mm/page_alloc.c:__alloc_page_frag",
        "mm/page_alloc.c:__alloc_page_frag"
      ],
      "caller_func": [
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ]
    },
    {
      "addr": 18446744071580617440,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:443",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580741953,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:443",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580790522,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:443",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__alloc_buddy_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587361093,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:443",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580889690,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:443",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582792691,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:443",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_rq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584305349,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:443",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584307169,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:443",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586139410,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:443",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580513056,
      "name": "alloc_pages_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct page * alloc_pages_node(int nid, gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578926334,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579056041,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579058246,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "arch/x86/kernel/pci-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370514,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580217673,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580252733,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580405154,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580512227,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580595156,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_page_frag",
        "mm/page_alloc.c:__alloc_page_frag"
      ],
      "caller_func": [
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ]
    },
    {
      "addr": 18446744071580720391,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580861133,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580913775,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__alloc_buddy_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587861997,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580969642,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020176,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583072107,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_rq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584651637,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584666377,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584688172,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580594944,
      "name": "alloc_pages_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct page * alloc_pages_node(int nid, gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578926718,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:447",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579055065,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:447",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579057270,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:447",
      "file": "arch/x86/kernel/pci-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580259049,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:447",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580298355,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:447",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580453302,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:447",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580576243,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:447",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580662190,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:447",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:page_frag_alloc"
      ],
      "caller_func": [
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ]
    },
    {
      "addr": 18446744071580786172,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:447",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580931437,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:447",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_node_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580982367,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:447",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__alloc_buddy_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588076709,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:447",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581042810,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:447",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581094784,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:447",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583181847,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:447",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_rq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584837685,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:447",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595711424,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:447",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584874732,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:447",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580661984,
      "name": "alloc_pages_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578920142,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:492",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579047337,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:492",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579049361,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:492",
      "file": "arch/x86/kernel/pci-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580281068,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:492",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580311829,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:492",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580464867,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:492",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580606947,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:492",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580695689,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:492",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580824756,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:492",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975724,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:492",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588303184,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:492",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581090917,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:492",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581141613,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:492",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583246250,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:492",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584927270,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:492",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596636290,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:492",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584963599,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:492",
      "file": "drivers/iommu/intel_irq_remapping.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578920350,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579056106,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579058376,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "arch/x86/kernel/pci-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370394,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:sev_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580334316,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580364968,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580520846,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580687955,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580781097,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580913023,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581078323,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581162993,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588868415,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581203141,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263849,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:new_page_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583425402,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585348646,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602966371,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585384895,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "drivers/iommu/intel_irq_remapping.c",
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
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578922859,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579061094,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579946448,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580396892,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580426376,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580608621,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580819987,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580916662,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050737,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581217267,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581306474,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589247423,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581348152,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581410802,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583636659,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585590725,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603137655,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel-iommu.c:pfn_to_dma_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585627661,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588009715,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:477",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
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
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578925371,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579065670,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579994834,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580448716,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580482120,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580667649,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580886659,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580992086,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581128481,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581300990,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581389404,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589489730,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581432264,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581494252,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583741728,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583874345,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585714969,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585727077,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:alloc_pgtable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585742978,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585754861,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588158408,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588170449,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
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
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578930603,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579074214,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580036938,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580503292,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580537942,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580730788,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580984147,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581193294,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581378128,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581410489,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581501961,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589950692,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581548822,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602188,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583930640,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585942819,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585956869,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:alloc_pgtable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585974674,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585986655,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588480583,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588496071,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:494",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
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
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578932987,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579076214,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580087178,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580551100,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580585495,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580781423,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581038131,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581251742,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439329,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581471513,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581566329,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590178246,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581615003,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672860,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584034000,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586085971,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586100149,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:alloc_pgtable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586120143,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586133663,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588685735,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588703991,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
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
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578938363,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579087043,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580147055,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580642716,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580684535,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897141,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:uprobe_buffer_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581066037,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581216483,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440074,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581647795,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677562,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581777129,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591196552,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581824547,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581891388,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584428691,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586783630,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586834323,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609374814,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586871474,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586887999,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589549815,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589570071,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:530",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
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
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578939547,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579089107,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580124596,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580130275,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580633427,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580675367,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580891397,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:uprobe_buffer_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581077697,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581259139,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581483194,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581694277,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581725386,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591691452,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581879132,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581937451,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584545059,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586890986,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612446074,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586920274,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586938143,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586965860,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589558935,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589579576,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:532",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
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
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578943883,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579058411,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579095661,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580128978,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580134659,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580630291,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580677623,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580896895,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581092725,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581277891,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581502714,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581717285,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581746033,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591634276,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581911020,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581962924,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584577491,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586771898,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614586639,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586801794,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586819726,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586846724,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589456935,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589480246,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:557",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
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
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578950255,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579079563,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579119018,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580272288,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580277811,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580802279,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580851932,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581102268,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581321909,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581521744,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581763466,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581989499,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582024237,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592808615,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "mm/sparse-vmemmap.c:vmemmap_remap_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582208286,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582243589,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:alloc_misplaced_dst_page_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584990451,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587327194,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587341191,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587358738,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587379646,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587409524,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590198509,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdpf_clone",
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590219182,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:578",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
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
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578959743,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579107839,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579152062,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap",
        "arch/x86/kernel/espfix_64.c:init_espfix_ap",
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580443691,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580449779,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581027889,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581080859,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363203,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581624642,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581869296,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582146873,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582385953,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vm_area_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582450991,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594709712,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "mm/sparse-vmemmap.c:vmemmap_remap_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582664792,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585701460,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588642016,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588658537,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc",
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588670345,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588687406,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588725393,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591764093,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdpf_clone",
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591796205,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:604",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
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
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578976975,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579145321,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579199798,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap",
        "arch/x86/kernel/espfix_64.c:init_espfix_ap",
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580687915,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580694638,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581328625,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581387938,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698185,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:uprobe_buffer_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582010882,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582297184,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582632092,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582651119,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:__kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582918808,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582962866,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583120481,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596454254,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586481111,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590112416,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590131077,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/iommu.c:iommu_context_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590143524,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590166172,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590201394,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593149824,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__napi_alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593554701,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdpf_clone",
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593591173,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_page_order"
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
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578976287,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579145922,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579203846,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap",
        "arch/x86/kernel/espfix_64.c:init_espfix_ap",
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580764515,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580771262,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423313,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581482546,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581843145,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:uprobe_buffer_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582201746,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582497936,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582841212,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582860655,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:__kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583134809,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583179468,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__page_frag_cache_refill",
        "mm/page_alloc.c:__page_frag_cache_refill",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583330818,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_remap_alloc",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596995582,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586728676,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590407280,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590410968,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "drivers/iommu/amd/io_pgtable_v2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable",
        "drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590426176,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590441156,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:alloc_pgtable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590457878,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590480412,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590522882,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593603540,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__napi_alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594023709,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdpf_clone",
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594064421,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:254",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_page_order"
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
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579001103,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579175594,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579233190,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap",
        "arch/x86/kernel/espfix_64.c:init_espfix_ap",
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580850259,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580857326,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531531,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581593026,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581966249,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:uprobe_buffer_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582350978,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582666448,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583016316,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583317865,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583363475,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583387403,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
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
      "addr": 18446744071583565787,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_optimize_folio",
        "mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_restore_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597925070,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587000308,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590737235,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:protection_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590751302,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590755080,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "drivers/iommu/amd/io_pgtable_v2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable",
        "drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590770399,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590787508,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:alloc_pgtable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590805061,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590830987,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590877554,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594378132,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__napi_alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594810429,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdpf_clone",
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594851909,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:255",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_page_order"
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
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491290104,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491835300,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491883380,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492096456,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492392548,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492653444,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492842944,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492879828,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493009168,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503921108,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493062040,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493116900,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495867176,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496387008,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3-its.c:its_probe_one",
        "drivers/irqchip/irq-gic-v3-its.c:its_probe_one"
      ]
    },
    {
      "addr": 18446603336498849156,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498852804,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/io-pgtable-arm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502243524,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502267640,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496387008,
      "name": "alloc_pages_node.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243251472,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 3224431768,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "arch/arm/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/signal.c:get_signal_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3224494668,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "arch/arm/mm/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/dma-mapping.c:arm_iommu_alloc_attrs",
        "arch/arm/mm/dma-mapping.c:arm_iommu_alloc_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 3243277736,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "arch/arm/mm/fault-armv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/fault-armv.c:check_writebuffer_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 3224707772,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3225156532,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:alloc_image_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3225295868,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3225483020,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3225725728,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225777296,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 3225834036,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3225992024,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3226281620,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 3226298028,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__create_xol_area",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 3226329668,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226346132,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3226382328,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:__do_page_cache_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 3226446068,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226492228,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 3226508476,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 3226580744,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226649700,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226679996,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:__get_free_pages",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 3226706696,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__read_swap_cache_async"
      ],
      "caller_func": []
    },
    {
      "addr": 3226729884,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 3226762620,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 3226768892,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226852604,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 3226859888,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226864524,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226874216,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226877172,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 3226955452,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3228260972,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3228301712,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 3228314124,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 3228335220,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 3228367808,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 3228500048,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_alloc_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 3228691836,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "security/selinux/ss/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3229133280,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 3229214216,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 3229431428,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 3229434720,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:push_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 3229727420,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_alloc_table_entry",
        "drivers/irqchip/irq-gic-v3-its.c:its_allocate_pending_table",
        "drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables",
        "drivers/irqchip/irq-gic-v3-its.c:its_allocate_prop_table"
      ],
      "caller_func": []
    },
    {
      "addr": 3230366860,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3230815096,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/dma/mv_xor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mv_xor.c:mv_chan_xor_self_test",
        "drivers/dma/mv_xor.c:mv_chan_xor_self_test"
      ],
      "caller_func": []
    },
    {
      "addr": 3230955696,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3231379592,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 3231399672,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts"
      ],
      "caller_func": []
    },
    {
      "addr": 3231408992,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3231410864,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3231415608,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 3231448840,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/io-pgtable-arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3231484032,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/tegra-smmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/tegra-smmu.c:tegra_smmu_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3231505848,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 3231670340,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 3231747856,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 3232117584,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_build_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 3233598796,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load"
      ],
      "caller_func": []
    },
    {
      "addr": 3233652532,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 3233715208,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:alloc_pl"
      ],
      "caller_func": []
    },
    {
      "addr": 3234060028,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3243936532,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3234631592,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234671260,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs"
      ],
      "caller_func": []
    },
    {
      "addr": 3234963364,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ],
      "caller_func": []
    },
    {
      "addr": 3234988716,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 3235007496,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282503424,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "arch/powerpc/kernel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/iommu.c:iommu_alloc_coherent",
        "arch/powerpc/kernel/iommu.c:iommu_init_table"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282946236,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "arch/powerpc/sysdev/xive/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/sysdev/xive/common.c:xive_queue_page_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283041032,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "arch/powerpc/platforms/powernv/pci-ioda.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda1_setup_dma_pe",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_iommu_bypass_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283060184,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "arch/powerpc/platforms/powernv/pci-ioda-tce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_alloc_tce_level"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283393084,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "arch/powerpc/perf/imc-pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/perf/imc-pmu.c:trace_imc_mem_alloc",
        "arch/powerpc/perf/imc-pmu.c:thread_imc_mem_alloc",
        "arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284216020,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284899988,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284962072,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285298248,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285652944,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285971452,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286231796,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286274576,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286429500,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297816520,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286499748,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286593896,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290066912,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295736168,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295761332,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
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
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270603228,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271383930,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271805630,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272094174,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272137500,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272180402,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272504444,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272527228,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272539470,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272570084,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:__do_page_cache_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272619480,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272664800,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272677204,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272732864,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272794792,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272821802,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:__get_free_pages",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272837930,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__read_swap_cache_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272860922,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270896514,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272917148,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272924766,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272997476,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273006652,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273016982,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273020890,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273022828,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273087646,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274164564,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274198818,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274213652,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274231384,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274261270,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274366796,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_alloc_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274530264,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "security/selinux/ss/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274925132,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274992550,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275172390,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275174808,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:push_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275745658,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275973030,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276256764,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276280596,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276295762,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276298356,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276303678,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276320018,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276438026,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276505670,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276843714,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_build_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277799294,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277852640,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277908762,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:alloc_pl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278191628,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278223278,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278450820,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278484134,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278501794,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
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
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578932987,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579076566,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580056213,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580519900,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580554295,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580750223,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581006979,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581220590,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581408177,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581440361,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535065,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589780534,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583739,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581641596,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584002736,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585847091,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585860837,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:alloc_pgtable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585880511,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585894031,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588292471,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588310727,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
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
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578929611,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579009445,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580001226,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580468764,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580500999,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580696415,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953107,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581167294,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581350689,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581382745,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581476825,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589503357,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581525259,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582553,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583938560,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585706131,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585720293,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:alloc_pgtable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585740287,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585753807,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587565273,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/hv/channel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/channel.c:vmbus_alloc_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588005287,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588023511,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
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
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578932923,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579076150,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580047450,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580511148,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580545543,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580741471,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580998179,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581211790,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581399377,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581431561,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581526377,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590223942,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581575051,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581632908,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583986496,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586035987,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586050165,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:alloc_pgtable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586070159,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586083679,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588624295,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588642551,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
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
  "name": "alloc_pages_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578933499,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579080246,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580098202,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580567484,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580602198,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580799471,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581059283,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581275182,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581463379,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581496057,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581591657,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590274300,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581640299,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699244,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584088800,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586143971,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586158213,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:alloc_pgtable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586178389,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586191967,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588762311,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588782055,
      "name": "alloc_pages_node",
      "external": false,
      "loc": "include/linux/gfp.h:523",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
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
struct page * alloc_pages_node(int nid, gfp_t gfp_mask, unsigned int order)
```
</details>
</li>
</ul>
