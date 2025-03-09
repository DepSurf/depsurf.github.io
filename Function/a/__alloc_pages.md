# Function: <code>__alloc_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578927801,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579059692,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579061867,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
      "file": "arch/x86/kernel/pci-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587336283,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/profile.c:profile_cpu_callback",
        "kernel/profile.c:profile_cpu_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580182784,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
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
      "addr": 18446744071580350141,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580438921,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580472879,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580513073,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_kmem_pages_node",
        "mm/page_alloc.c:__alloc_page_frag",
        "mm/page_alloc.c:__alloc_page_frag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580617442,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580741993,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580790522,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__alloc_buddy_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580811038,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_page_interleave",
        "mm/mempolicy.c:alloc_pages_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587361108,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580849967,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580878987,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:new_page_node",
        "mm/migrate.c:alloc_misplaced_dst_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580896668,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580950253,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:new_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582792693,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_rq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584305360,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584307180,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
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
      "addr": 18446744071586139424,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:419",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578926345,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579056054,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579058248,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "arch/x86/kernel/pci-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370518,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579833527,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580217680,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
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
      "addr": 18446744071580252744,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580405156,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580512234,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580549663,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580595162,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_page_frag",
        "mm/page_alloc.c:__alloc_page_frag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580720400,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580861185,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580913781,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__alloc_buddy_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580945310,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_page_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587862011,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580969653,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581003201,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020194,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:alloc_misplaced_dst_page",
        "mm/migrate.c:new_page_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581046006,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581098669,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:new_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583072109,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_rq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584651648,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584666388,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
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
      "addr": 18446744071584688183,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:430",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578926729,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579055078,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579057272,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "arch/x86/kernel/pci-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579862013,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580259056,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
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
      "addr": 18446744071580298366,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580453304,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580576250,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580612191,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580662196,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:page_frag_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580786181,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580931489,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_node_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580982373,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__alloc_buddy_huge_page",
        "mm/hugetlb.c:alloc_fresh_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581017533,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_page_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588076723,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581042821,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581077181,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581094802,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:alloc_misplaced_dst_page",
        "mm/migrate.c:new_page_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581121142,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581173885,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:new_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583181849,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_rq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584837692,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595711438,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
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
      "addr": 18446744071584874743,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:423",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578920154,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579047351,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579049373,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
      "file": "arch/x86/kernel/pci-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579870249,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580281080,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580311841,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580464879,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580606952,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580640555,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580695689,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
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
      "addr": 18446744071580824768,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975724,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581031120,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581063407,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_page_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588303199,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581090932,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581141623,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:alloc_misplaced_dst_page",
        "mm/migrate.c:new_page_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581174756,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583246266,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584927282,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596636302,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
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
      "addr": 18446744071584963611,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:469",
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
  "name": "__alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578902231,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:dsalloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578920362,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579056123,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579058388,
      "name": "__alloc_pages",
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
      "addr": 18446744071579370406,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:sev_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579913645,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580334328,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580364980,
      "name": "__alloc_pages",
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
      "addr": 18446744071580520858,
      "name": "__alloc_pages",
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
      "addr": 18446744071580687960,
      "name": "__alloc_pages",
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
      "addr": 18446744071580723343,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580781097,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
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
      "addr": 18446744071580913035,
      "name": "__alloc_pages",
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
      "addr": 18446744071581078323,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581140736,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581174495,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_page_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588868433,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581203156,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263859,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:alloc_misplaced_dst_page",
        "mm/migrate.c:new_page_node",
        "mm/migrate.c:new_page_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305490,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583425418,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585348658,
      "name": "__alloc_pages",
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
      "addr": 18446744071602966383,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
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
      "addr": 18446744071585384907,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
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
  "name": "__alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578904215,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:dsalloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578922874,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579061108,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579946460,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:dma_direct_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579958093,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580396901,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580426388,
      "name": "__alloc_pages",
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
      "addr": 18446744071580608633,
      "name": "__alloc_pages",
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
      "addr": 18446744071580819992,
      "name": "__alloc_pages",
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
      "addr": 18446744071580858591,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580916685,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
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
      "addr": 18446744071581050760,
      "name": "__alloc_pages",
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
      "addr": 18446744071581217267,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581319147,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_page_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589247437,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581348164,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581410812,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:alloc_misplaced_dst_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581444261,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583636673,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585590730,
      "name": "__alloc_pages",
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
      "addr": 18446744071603137667,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
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
      "addr": 18446744071585627673,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588009727,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:454",
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
  "name": "__alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578905447,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:dsalloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578925386,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579065684,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579994846,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580004925,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580448725,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580482132,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580667661,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580886664,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580927071,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580992093,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
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
      "addr": 18446744071581128504,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581300990,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581403307,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_page_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589489744,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581432276,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581494264,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:alloc_misplaced_dst_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581527717,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583741742,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583874361,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585714981,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585727095,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:alloc_pgtable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585742990,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585754873,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588158415,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588170461,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
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
  "name": "__alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578913319,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:dsalloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578930618,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579074228,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580036955,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580047623,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580503301,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580537954,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580730800,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580984152,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581023027,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581193317,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581247138,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:new_non_cma_page",
        "mm/gup.c:new_non_cma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581378128,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581410512,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
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
      "addr": 18446744071581500741,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_page_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589950706,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581548834,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602200,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:alloc_misplaced_dst_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581641025,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583930654,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585942831,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585956887,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:alloc_pgtable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585974686,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585986667,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588480599,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588496083,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:471",
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
  "name": "__alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578915079,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:dsalloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578933002,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579076228,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580087195,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580096727,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580551109,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580585507,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580781435,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581038136,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581078275,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581251765,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305714,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:new_non_cma_page",
        "mm/gup.c:new_non_cma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439329,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581471536,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "addr": 18446744071581578776,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_page_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590178260,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581615015,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672872,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:alloc_misplaced_dst_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581712095,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584034014,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586085983,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586100167,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:alloc_pgtable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586120155,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586133675,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588685751,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588704003,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
  "name": "__alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578914254,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:dsalloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578938378,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579087055,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580147072,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580159047,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580642725,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580684547,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897153,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:uprobe_buffer_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581066053,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581216488,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581262655,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581440086,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581647795,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677575,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
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
      "addr": 18446744071581790614,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_page_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591196566,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581824561,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581891400,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:alloc_misplaced_dst_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581930454,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584428707,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586783642,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586834335,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609374826,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
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
      "addr": 18446744071586871486,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888011,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589549831,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589570083,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
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
  "name": "__alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578911783,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:dsalloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578939562,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579089119,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580124612,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580130293,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580143479,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580633436,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580675379,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580891409,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:uprobe_buffer_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581077713,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "kernel/bpf/ringbuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581259144,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581304656,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581483206,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581694277,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581725409,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
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
      "addr": 18446744071581838358,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_page_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591691466,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581879144,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581937461,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:alloc_misplaced_dst_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581981012,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584545075,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586890991,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612446086,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
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
      "addr": 18446744071586920286,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586938155,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586965878,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589558951,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589579588,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:509",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct page * __alloc_pages(gfp_t gfp, unsigned int order, int preferred_nid, nodemask_t * nodemask)
```

```json
{
  "name": "__alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581745104,
      "name": "__alloc_pages",
      "external": true,
      "loc": "mm/page_alloc.c:5156",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:dsalloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages",
        "kernel/profile.c:profile_prepare_cpu",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:alloc_pages_exact_nid",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_page_interleave",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:alloc_misplaced_dst_page",
        "mm/migrate.c:alloc_migration_target",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "drivers/iommu/intel/dmar.c:dmar_enable_qi",
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581745104,
      "name": "__alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 806
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
struct page * __alloc_pages(gfp_t gfp, unsigned int order, int preferred_nid, nodemask_t * nodemask)
```

```json
{
  "name": "__alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582023296,
      "name": "__alloc_pages",
      "external": true,
      "loc": "mm/page_alloc.c:5345",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:dsalloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages",
        "kernel/profile.c:profile_prepare_cpu",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:alloc_pages_exact_nid",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_page_interleave",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "mm/sparse-vmemmap.c:vmemmap_remap_alloc",
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/migrate.c:alloc_misplaced_dst_page_thp",
        "mm/migrate.c:alloc_misplaced_dst_page",
        "mm/migrate.c:alloc_migration_target",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "drivers/iommu/intel/dmar.c:dmar_enable_qi",
        "drivers/iommu/intel/iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "net/core/xdp.c:xdpf_clone",
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582023296,
      "name": "__alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 800
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * __alloc_pages(gfp_t gfp, unsigned int order, int preferred_nid, nodemask_t * nodemask)
```

```json
{
  "name": "__alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_pages",
      "external": true,
      "loc": "mm/page_alloc.c:5390",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:dsalloc_pages",
        "arch/x86/kernel/espfix_64.c:init_espfix_ap",
        "arch/x86/kernel/espfix_64.c:init_espfix_ap",
        "arch/x86/kernel/espfix_64.c:init_espfix_ap",
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages",
        "kernel/profile.c:profile_prepare_cpu",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "mm/vmalloc.c:vm_area_alloc_pages",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:__folio_alloc",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:alloc_pages_exact_nid",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:alloc_page_interleave",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "mm/sparse-vmemmap.c:vmemmap_remap_alloc",
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "drivers/iommu/intel/dmar.c:dmar_enable_qi",
        "drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc",
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:iommu_alloc_root_entry",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "net/core/xdp.c:xdpf_clone",
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593982143,
      "name": "__alloc_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582449984,
      "name": "__alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 834
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * __alloc_pages(gfp_t gfp, unsigned int order, int preferred_nid, nodemask_t * nodemask)
```

```json
{
  "name": "__alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_pages",
      "external": true,
      "loc": "mm/page_alloc.c:5513",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:dsalloc_pages",
        "arch/x86/kernel/espfix_64.c:init_espfix_ap",
        "arch/x86/kernel/espfix_64.c:init_espfix_ap",
        "arch/x86/kernel/espfix_64.c:init_espfix_ap",
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages",
        "kernel/profile.c:profile_prepare_cpu",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:uprobe_buffer_init",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "mm/slab_common.c:__kmalloc_large_node",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:__folio_alloc",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:alloc_pages_exact_nid",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:alloc_page_interleave",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/khugepaged.c:alloc_charge_hpage",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "drivers/iommu/intel/dmar.c:dmar_enable_qi",
        "drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc",
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:si_domain_init",
        "drivers/iommu/intel/iommu.c:pfn_to_dma_pte",
        "drivers/iommu/intel/iommu.c:iommu_context_addr",
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/xdp.c:xdpf_clone",
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/page_pool.c:__page_pool_alloc_page_order"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596037676,
      "name": "__alloc_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582959584,
      "name": "__alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 834
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * __alloc_pages(gfp_t gfp, unsigned int order, int preferred_nid, nodemask_t * nodemask)
```

```json
{
  "name": "__alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_pages",
      "external": true,
      "loc": "mm/page_alloc.c:4441",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:dsalloc_pages",
        "arch/x86/kernel/espfix_64.c:init_espfix_ap",
        "arch/x86/kernel/espfix_64.c:init_espfix_ap",
        "arch/x86/kernel/espfix_64.c:init_espfix_ap",
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages",
        "kernel/profile.c:profile_prepare_cpu",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:uprobe_buffer_init",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "mm/slab_common.c:__kmalloc_large_node",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/page_alloc.c:__page_frag_cache_refill",
        "mm/page_alloc.c:__page_frag_cache_refill",
        "mm/page_alloc.c:__folio_alloc",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:alloc_pages_exact_nid",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_alloc",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:alloc_page_interleave",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/khugepaged.c:alloc_charge_hpage",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable",
        "drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte",
        "drivers/iommu/intel/dmar.c:dmar_enable_qi",
        "drivers/iommu/intel/iommu.c:alloc_pgtable_page",
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/xdp.c:xdpf_clone",
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/page_pool.c:__page_pool_alloc_page_order"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596559909,
      "name": "__alloc_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583176528,
      "name": "__alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 836
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * __alloc_pages(gfp_t gfp, unsigned int order, int preferred_nid, nodemask_t * nodemask)
```

```json
{
  "name": "__alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_pages",
      "external": true,
      "loc": "mm/page_alloc.c:4533",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/ds.c:dsalloc_pages",
        "arch/x86/kernel/espfix_64.c:init_espfix_ap",
        "arch/x86/kernel/espfix_64.c:init_espfix_ap",
        "arch/x86/kernel/espfix_64.c:init_espfix_ap",
        "kernel/dma/ops_helpers.c:dma_common_alloc_pages",
        "kernel/profile.c:profile_prepare_cpu",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:uprobe_buffer_init",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:page_frag_alloc_align",
        "mm/page_alloc.c:__folio_alloc",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:alloc_pages_exact_nid",
        "mm/slub.c:__kmalloc_large_node",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_optimize_folio",
        "mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_restore_folio",
        "mm/mempolicy.c:alloc_pages_mpol",
        "mm/mempolicy.c:alloc_pages_mpol",
        "mm/mempolicy.c:alloc_pages_mpol",
        "mm/mempolicy.c:alloc_pages_mpol",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "drivers/iommu/amd/iommu.c:protection_domain_alloc",
        "drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable",
        "drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte",
        "drivers/iommu/intel/dmar.c:dmar_enable_qi",
        "drivers/iommu/intel/iommu.c:alloc_pgtable_page",
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/xdp.c:xdpf_clone",
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/page_pool.c:__page_pool_alloc_page_order"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597464324,
      "name": "__alloc_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583360384,
      "name": "__alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 836
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
  "name": "__alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491290112,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491305512,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491835308,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491883324,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492096472,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492392556,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492441536,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492653396,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492715160,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:new_non_cma_page",
        "mm/gup.c:new_non_cma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492842944,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492879848,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "addr": 18446603336493016400,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_page_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503921128,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493062060,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493116920,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:alloc_misplaced_dst_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493156188,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495867176,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496387044,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498849176,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498852812,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/io-pgtable-arm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502243536,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502267664,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243251472,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 3224431768,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/arm/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/signal.c:get_signal_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3224494668,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/arm/mm/fault-armv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/fault-armv.c:check_writebuffer_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 3224706384,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3225156532,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:alloc_image_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3225295868,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3225303996,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3225483020,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3225725728,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225777296,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 3225834036,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3226281620,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 3226298028,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3226382328,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:__do_page_cache_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 3226446068,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226492228,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 3226508476,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 3226550440,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:new_non_cma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226580744,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226679996,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__read_swap_cache_async"
      ],
      "caller_func": []
    },
    {
      "addr": 3226729884,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 3226762620,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 3226768892,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226852604,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 3226859888,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226864524,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226874216,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226877172,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 3226955452,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3228260972,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 3228314124,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 3228335220,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 3228500048,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_alloc_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 3228691836,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "security/selinux/ss/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3229133280,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 3229431428,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 3229434720,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:push_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 3229727420,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3230815096,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3231379592,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 3231399672,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3231415608,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 3231448840,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/io-pgtable-arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3231484032,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/tegra-smmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/tegra-smmu.c:tegra_smmu_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3231505848,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 3231670340,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 3231747856,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_build_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 3233598796,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:alloc_pl"
      ],
      "caller_func": []
    },
    {
      "addr": 3234060028,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3243936532,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3234631592,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234671260,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 3235007496,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
  "name": "__alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282503448,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/powerpc/kernel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/iommu.c:iommu_alloc_coherent",
        "arch/powerpc/kernel/iommu.c:iommu_init_table"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282946260,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/powerpc/sysdev/xive/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/sysdev/xive/common.c:xive_queue_page_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283041064,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/powerpc/platforms/powernv/pci-ioda.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda1_setup_dma_pe",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_iommu_bypass_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283060204,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/powerpc/platforms/powernv/pci-ioda-tce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_alloc_tce_level"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283393088,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "addr": 13835058055284216040,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284232288,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284899996,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284962012,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285298372,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285652952,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285715108,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285971400,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286052860,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:new_non_cma_page",
        "mm/gup.c:new_non_cma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286231796,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286274600,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:alloc_pages_exact_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286443280,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_page_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297816540,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286499768,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286593916,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:alloc_misplaced_dst_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286643908,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290066848,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295736196,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295761356,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
  "name": "__alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270603228,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271383932,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271805630,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271817136,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272094174,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272137500,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272180402,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272527228,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272570084,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:__do_page_cache_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272619480,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272664800,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272677204,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272712732,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272732864,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272821802,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__read_swap_cache_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272860922,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270896528,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272917148,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272924766,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272997476,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273006652,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273016982,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273020890,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273022828,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273087646,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274164564,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274213652,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274231384,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274366796,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_alloc_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274530264,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "security/selinux/ss/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274925132,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275172390,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275174808,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:push_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275745658,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275973030,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276256764,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276280596,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276303678,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276320018,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276438026,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276505670,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_build_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277799294,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:alloc_pl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278191628,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278223278,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278501802,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
  "name": "__alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578915079,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:dsalloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578933002,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579076580,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580056220,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580065927,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580519909,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580554307,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580750235,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581006984,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581047123,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581220613,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581274562,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:new_non_cma_page",
        "mm/gup.c:new_non_cma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581408177,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581440384,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "addr": 18446744071581547512,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_page_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589780548,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583751,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581641608,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:alloc_misplaced_dst_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680831,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584002750,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585847103,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585860855,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:alloc_pgtable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585880523,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585894043,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588292487,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588310739,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
  "name": "__alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578910375,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:dsalloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578929626,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579009478,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580001243,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580010775,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580468773,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580501011,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580696427,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953112,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580994403,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581167317,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581221042,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:new_non_cma_page",
        "mm/gup.c:new_non_cma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581350689,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581382768,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "addr": 18446744071581489160,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_page_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589503371,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581525271,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582565,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:alloc_misplaced_dst_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619519,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583938574,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585706143,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585720311,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:alloc_pgtable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585740299,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585753819,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587565285,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/hv/channel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/channel.c:vmbus_alloc_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588005303,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588023523,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
  "name": "__alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578915015,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:dsalloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578932938,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579076164,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580047467,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580056999,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580511157,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580545555,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580741483,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580998184,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581038323,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581211813,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581265762,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:new_non_cma_page",
        "mm/gup.c:new_non_cma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581399377,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581431584,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "addr": 18446744071581538824,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_page_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590223956,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581575063,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581632920,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:alloc_misplaced_dst_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672143,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583986510,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586035999,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586050183,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:alloc_pgtable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586070171,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586083691,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588624311,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588642563,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
  "name": "__alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578915543,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:dsalloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578933514,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579080260,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580098219,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/dma/direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/direct.c:__dma_direct_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580107815,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_prepare_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580567493,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580602210,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580799483,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581059288,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_mmap_alloc_page",
        "kernel/events/ring_buffer.c:rb_alloc_aux"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581099939,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581275205,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329618,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:new_non_cma_page",
        "mm/gup.c:new_non_cma_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581463379,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581496080,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
      "addr": 18446744071581603864,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:alloc_page_interleave"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590274314,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581640311,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_large_node",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699256,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:alloc_misplaced_dst_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581738703,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584088814,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_rqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586143983,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_enable_qi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586158231,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:alloc_pgtable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586178401,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586191979,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588762327,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588782067,
      "name": "__alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:500",
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
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct page * __alloc_pages(gfp_t gfp, unsigned int order, int preferred_nid, nodemask_t * nodemask)
```
</details>
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
