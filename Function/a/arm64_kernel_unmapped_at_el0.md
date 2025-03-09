# Function: <code>arm64_kernel_unmapped_at_el0</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool arm64_kernel_unmapped_at_el0()
```

```json
{
  "name": "arm64_kernel_unmapped_at_el0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510813972,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "arch/arm64/kernel/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/irq.c:init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490194296,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "arch/arm64/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/process.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490219256,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "arch/arm64/kernel/setup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/setup.c:setup_arch",
        "arch/arm64/kernel/setup.c:setup_arch"
      ]
    },
    {
      "addr": 18446603336503948892,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "arch/arm64/kernel/insn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/insn.c:__aarch64_insn_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490266956,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "arch/arm64/kernel/cpufeature.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/cpufeature.c:cpu_show_meltdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490295052,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "arch/arm64/kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/module.c:module_alloc",
        "arch/arm64/kernel/module.c:module_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490317928,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "arch/arm64/kernel/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/efi.c:efi_create_mapping",
        "arch/arm64/kernel/efi.c:efi_create_mapping",
        "arch/arm64/kernel/efi.c:efi_create_mapping",
        "arch/arm64/kernel/efi.c:efi_create_mapping",
        "arch/arm64/kernel/efi.c:efi_create_mapping"
      ]
    },
    {
      "addr": 18446603336490324300,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "arch/arm64/kernel/acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute",
        "arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute",
        "arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute",
        "arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490325596,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "arch/arm64/kernel/acpi_parking_protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/acpi_parking_protocol.c:acpi_parking_protocol_cpu_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510827760,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "arch/arm64/kernel/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/kaslr.c:kaslr_early_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503950672,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "arch/arm64/kernel/sdei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/sdei.c:__sdei_handler",
        "arch/arm64/kernel/sdei.c:sdei_arch_get_entry_point",
        "arch/arm64/kernel/sdei.c:_init_sdei_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490341032,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "arch/arm64/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/fault.c:ptep_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490344356,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "arch/arm64/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490350080,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "arch/arm64/mm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/mmu.c:arch_add_memory",
        "arch/arm64/mm/mmu.c:mark_rodata_ro",
        "arch/arm64/mm/mmu.c:alloc_init_pud",
        "arch/arm64/mm/mmu.c:init_pmd",
        "arch/arm64/mm/mmu.c:init_pmd",
        "arch/arm64/mm/mmu.c:set_swapper_pgd"
      ],
      "caller_func": [
        "arch/arm64/mm/mmu.c:vmemmap_populate",
        "arch/arm64/mm/mmu.c:paging_init",
        "arch/arm64/mm/mmu.c:paging_init",
        "arch/arm64/mm/mmu.c:paging_init",
        "arch/arm64/mm/mmu.c:paging_init",
        "arch/arm64/mm/mmu.c:paging_init",
        "arch/arm64/mm/mmu.c:paging_init",
        "arch/arm64/mm/mmu.c:paging_init",
        "arch/arm64/mm/mmu.c:paging_init",
        "arch/arm64/mm/mmu.c:paging_init",
        "arch/arm64/mm/mmu.c:map_entry_trampoline",
        "arch/arm64/mm/mmu.c:map_entry_trampoline",
        "arch/arm64/mm/mmu.c:map_entry_trampoline",
        "arch/arm64/mm/mmu.c:mark_linear_text_alias_ro",
        "arch/arm64/mm/mmu.c:early_pgtable_alloc"
      ]
    },
    {
      "addr": 18446603336490358812,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "arch/arm64/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/hugetlbpage.c:huge_ptep_clear_flush",
        "arch/arm64/mm/hugetlbpage.c:huge_ptep_clear_flush",
        "arch/arm64/mm/hugetlbpage.c:set_huge_pte_at",
        "arch/arm64/mm/hugetlbpage.c:set_huge_pte_at",
        "arch/arm64/mm/hugetlbpage.c:get_clear_flush",
        "arch/arm64/mm/hugetlbpage.c:get_clear_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490372736,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "arch/arm64/net/bpf_jit_comp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/net/bpf_jit_comp.c:bpf_jit_alloc_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490465316,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "virt/kvm/arm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/mmu.c:create_hyp_io_mappings",
        "virt/kvm/arm/mmu.c:create_hyp_io_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490627596,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490879932,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "kernel/groups.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/groups.c:groups_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491300512,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "kernel/dma/remap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/remap.c:arch_dma_alloc"
      ],
      "caller_func": [
        "kernel/dma/remap.c:dma_atomic_pool_init"
      ]
    },
    {
      "addr": 18446603336491489572,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:__do_sys_init_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491504384,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491776740,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492117064,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc",
        "kernel/bpf/core.c:bpf_prog_alloc_no_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492432292,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "kernel/iomem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:ioremap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492653808,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492752868,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492796344,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492799564,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492802924,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492811476,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pmdp_huge_clear_flush",
        "mm/pgtable-generic.c:pmdp_huge_clear_flush",
        "mm/pgtable-generic.c:pmdp_clear_flush_young",
        "mm/pgtable-generic.c:pmdp_clear_flush_young",
        "mm/pgtable-generic.c:ptep_clear_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492818748,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492845288,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_32_user",
        "mm/vmalloc.c:vmalloc_32",
        "mm/vmalloc.c:vmalloc_exec",
        "mm/vmalloc.c:vzalloc_node",
        "mm/vmalloc.c:vmalloc_node",
        "mm/vmalloc.c:vmalloc_user",
        "mm/vmalloc.c:vzalloc",
        "mm/vmalloc.c:vmalloc",
        "mm/vmalloc.c:__vmalloc_node_flags_caller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510964188,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_large_system_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492899040,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:tlb_flush_mmu_tlbonly",
        "mm/madvise.c:tlb_flush_mmu_tlbonly",
        "mm/madvise.c:tlb_flush_mmu_tlbonly",
        "mm/madvise.c:tlb_flush_mmu_tlbonly"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492997188,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503921992,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493137980,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493257768,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493262984,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/early_ioremap.c:early_memremap_ro",
        "mm/early_ioremap.c:early_memremap",
        "mm/early_ioremap.c:early_ioremap"
      ]
    },
    {
      "addr": 18446603336494581640,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_kvzalloc"
      ],
      "caller_func": [
        "fs/ext4/super.c:ext4_kvmalloc"
      ]
    },
    {
      "addr": 18446603336495111020,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_alloc_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496174800,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "lib/pci_iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/pci_iomap.c:pci_iomap_wc_range",
        "lib/pci_iomap.c:pci_iomap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496176476,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "lib/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/devres.c:__devm_ioremap",
        "lib/devres.c:__devm_ioremap",
        "lib/devres.c:__devm_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511065132,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/irqchip/irq-dw-apb-ictl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496368828,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/irqchip/irq-gic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic.c:gic_v2_acpi_init",
        "drivers/irqchip/irq-gic.c:gic_v2_acpi_init",
        "drivers/irqchip/irq-gic.c:gic_of_init",
        "drivers/irqchip/irq-gic.c:gic_of_init"
      ]
    },
    {
      "addr": 18446603336511069972,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/irqchip/irq-gic-v2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_init_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496379864,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3.c:gic_acpi_init",
        "drivers/irqchip/irq-gic-v3.c:gic_acpi_parse_madt_gicc",
        "drivers/irqchip/irq-gic-v3.c:gic_acpi_parse_madt_redist"
      ]
    },
    {
      "addr": 18446603336511076980,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_probe_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511083220,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/irqchip/irq-bcm7038-l1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_of_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496431380,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/irqchip/irq-sni-exiu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-sni-exiu.c:exiu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496443068,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/bus/arm-cci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496863868,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_remap_iospace",
        "drivers/pci/pci.c:pci_ioremap_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496904000,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496967380,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_e100_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497040980,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497057604,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497076696,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/pci/ecam.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/ecam.c:pci_ecam_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497089840,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497168184,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497343064,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/video/fbdev/imsttfb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe"
      ]
    },
    {
      "addr": 18446603336497350592,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/video/fbdev/amba-clcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/amba-clcd.c:clcdfb_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497353936,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/video/fbdev/asiliantfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497357628,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/video/fbdev/efifb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497366720,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/video/fbdev/mx3fb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497369636,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/video/fbdev/simplefb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/simplefb.c:simplefb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497664924,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497683264,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497731268,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/amba/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/amba/bus.c:amba_device_try_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511143328,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/clk/clk-qoriq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-qoriq.c:clockgen_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498030176,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/dma/amba-pl08x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/amba-pl08x.c:pl08x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498075672,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/dma/ipu/ipu_idmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe"
      ]
    },
    {
      "addr": 18446603336498089660,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/soc/fsl/qbman/bman_portal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498091156,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/soc/fsl/qbman/qman_portal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511196284,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/soc/renesas/renesas-soc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498238456,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511202212,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511203656,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/reset/reset-sunxi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/reset-sunxi.c:sun6i_reset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511208500,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/tty/serial/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498572928,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498609072,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498681888,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/tty/serial/msm_serial.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/msm_serial.c:msm_request_port"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498848704,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499122076,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499390380,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/mfd/syscon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/syscon.c:of_syscon_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499396380,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500042944,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/net/ethernet/freescale/fman/fman_muram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fman/fman_muram.c:fman_muram_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500101964,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/net/ethernet/smsc/smc91x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_enable_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500448620,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/usb/host/pci-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501259616,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/edac/altera_edac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/altera_edac.c:altr_sdram_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503916140,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/firmware/efi/earlycon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/earlycon.c:efi_earlycon_map",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501576440,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/clocksource/sh_cmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501581260,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/clocksource/sh_tmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_tmu.c:sh_tmu_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501591668,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/clocksource/arm_arch_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_frame_register",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_find_best_frame",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_frame_get_cntfrq"
      ]
    },
    {
      "addr": 18446603336501640796,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/of/address.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/address.c:of_io_request_and_map",
        "drivers/of/address.c:of_iomap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501669032,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "drivers/mailbox/pl320-ipc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pl320-ipc.c:pl320_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arm64_kernel_unmapped_at_el0",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu.h:32",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496368828,
      "name": "arm64_kernel_unmapped_at_el0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446603336496379864,
      "name": "arm64_kernel_unmapped_at_el0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446603336490219256,
      "name": "arm64_kernel_unmapped_at_el0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446603336490317928,
      "name": "arm64_kernel_unmapped_at_el0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446603336490344864,
      "name": "arm64_kernel_unmapped_at_el0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446603336491299216,
      "name": "arm64_kernel_unmapped_at_el0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446603336493262984,
      "name": "arm64_kernel_unmapped_at_el0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446603336494532352,
      "name": "arm64_kernel_unmapped_at_el0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446603336497343064,
      "name": "arm64_kernel_unmapped_at_el0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446603336497357628,
      "name": "arm64_kernel_unmapped_at_el0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446603336498075672,
      "name": "arm64_kernel_unmapped_at_el0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446603336501591668,
      "name": "arm64_kernel_unmapped_at_el0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
bool arm64_kernel_unmapped_at_el0()
```
</details>
</li>
</ul>
