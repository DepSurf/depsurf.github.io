# Function: <code>__pfn_to_mfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn)
```

```json
{
  "name": "__pfn_to_mfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578958640,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_load_gdt"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071579355643,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup"
      ]
    },
    {
      "addr": 18446744071594976199,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:remap_area_mfn_pte_fn",
        "arch/x86/xen/mmu.c:xen_set_domain_pte",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu.c:__xen_set_pgd_hyper",
        "arch/x86/xen/mmu.c:xen_do_pin",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_alloc_pte",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578992454,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578994512,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579002530,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579024033,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583848001,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_foreach_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583851972,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583855937,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/manage.c:xen_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595248187,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583869825,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583875984,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586136646,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071583894985,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/xenbus/xenbus_dev_backend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583901673,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/biomerge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583908453,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583919930,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584084032,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xen_pv_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_pv_console_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584566480,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585116661,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578958640,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071579355643,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071586136646,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
long unsigned int __pfn_to_mfn(long unsigned int pfn)
```

```json
{
  "name": "__pfn_to_mfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578959107,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_load_gdt"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071579362411,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ]
    },
    {
      "addr": 18446744071578967555,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:remap_area_mfn_pte_fn",
        "arch/x86/xen/mmu.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_alloc_pte",
        "arch/x86/xen/mmu.c:xen_do_pin",
        "arch/x86/xen/mmu.c:__xen_set_pgd_hyper",
        "arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_domain_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578989900,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578993131,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578999617,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579020177,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584180754,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584181477,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584185797,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/manage.c:xen_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595429885,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584201408,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584207367,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586550434,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn"
      ]
    },
    {
      "addr": 18446744071584225841,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/xenbus/xenbus_dev_backend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584232798,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/biomerge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584239801,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584251097,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584413551,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584925472,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585509686,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578955632,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071579362411,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071586550434,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
long unsigned int __pfn_to_mfn(long unsigned int pfn)
```

```json
{
  "name": "__pfn_to_mfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578961171,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_load_gdt"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071579380350,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ]
    },
    {
      "addr": 18446744071578969331,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:remap_area_mfn_pte_fn",
        "arch/x86/xen/mmu.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_alloc_pte",
        "arch/x86/xen/mmu.c:xen_do_pin",
        "arch/x86/xen/mmu.c:__xen_set_pgd_hyper",
        "arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte_at",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_pte",
        "arch/x86/xen/mmu.c:xen_set_domain_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578991748,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578994971,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579001459,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579020577,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584362118,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584362847,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584366773,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/manage.c:xen_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595682165,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584382864,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584388951,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586732060,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn"
      ]
    },
    {
      "addr": 18446744071584407297,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/xenbus/xenbus_dev_backend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584414259,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/biomerge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584421241,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584432714,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584595951,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585108721,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585697350,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:85",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578957472,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071579380350,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071586732060,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn)
```

```json
{
  "name": "__pfn_to_mfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578954250,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:remap_area_mfn_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578959100,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ]
    },
    {
      "addr": 18446744071578962930,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578964184,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578966686,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578973138,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071578995234,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_domain_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579015091,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584443702,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584444393,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584448301,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "drivers/xen/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/manage.c:xen_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596606501,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584463504,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584470590,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584484680,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn"
      ]
    },
    {
      "addr": 18446744071584490385,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "drivers/xen/xenbus/xenbus_dev_backend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584497989,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "drivers/xen/biomerge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584505146,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584517590,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584678491,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585191016,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585785493,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:105",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578959100,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071578970688,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071584484680,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn)
```

```json
{
  "name": "__pfn_to_mfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578956554,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:remap_area_mfn_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578962424,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ]
    },
    {
      "addr": 18446744071578966178,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578967464,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578969821,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578975876,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot"
      ]
    },
    {
      "addr": 18446744071578998210,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579015637,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584853353,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584854005,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584858280,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/manage.c:xen_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602936879,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584873904,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584880977,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584895016,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn"
      ]
    },
    {
      "addr": 18446744071584900753,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/xenbus/xenbus_dev_backend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584907925,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/biomerge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584915162,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584927622,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585090907,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585619176,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586224181,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578962424,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071578973728,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071584895016,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
long unsigned int __pfn_to_mfn(long unsigned int pfn)
```

```json
{
  "name": "__pfn_to_mfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578959070,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:remap_area_pfn_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578965004,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ]
    },
    {
      "addr": 18446744071578968465,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970018,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578972847,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602786851,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579001612,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579018260,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585084105,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585085192,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585088936,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/manage.c:xen_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603109827,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585105030,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585110489,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585126046,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn"
      ]
    },
    {
      "addr": 18446744071585132354,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/xenbus/xenbus_dev_backend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585139461,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/biomerge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585147642,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585158825,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585324733,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585862627,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586480927,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:115",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578965004,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071585126046,
      "name": "__pfn_to_mfn",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn)
```

```json
{
  "name": "__pfn_to_mfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578958209,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578963100,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ]
    },
    {
      "addr": 18446744071578966545,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578968145,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578971022,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604580867,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579000508,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_batched_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_batched_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579019508,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585194793,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585195876,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585199112,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/manage.c:xen_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604912540,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585216486,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585221268,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585236862,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn"
      ]
    },
    {
      "addr": 18446744071585243154,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xenbus/xenbus_dev_backend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585250261,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/biomerge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585257498,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585269641,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585448141,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585994531,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586628575,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578963100,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071585236862,
      "name": "__pfn_to_mfn",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn)
```

```json
{
  "name": "__pfn_to_mfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578965185,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578970076,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ]
    },
    {
      "addr": 18446744071578973619,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578975271,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578978030,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604676171,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579007932,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579027265,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585407036,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585408237,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585411587,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/manage.c:xen_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605021333,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585428982,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585433460,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585449023,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn"
      ]
    },
    {
      "addr": 18446744071585455567,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xenbus/xenbus_dev_backend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585462357,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/biomerge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585466954,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585479948,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585664697,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586238895,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586882048,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578970076,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071585449023,
      "name": "__pfn_to_mfn",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn)
```

```json
{
  "name": "__pfn_to_mfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578967649,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578972508,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ]
    },
    {
      "addr": 18446744071578976019,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977671,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980430,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604688639,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010300,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579029521,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585547772,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585548982,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585552291,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/manage.c:xen_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605058284,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585569430,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585573908,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585589455,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn"
      ]
    },
    {
      "addr": 18446744071585596079,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xenbus/xenbus_dev_backend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585603077,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/biomerge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585607626,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585620652,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585805673,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586387119,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587028064,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578972508,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071585589455,
      "name": "__pfn_to_mfn",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn)
```

```json
{
  "name": "__pfn_to_mfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578976801,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578982236,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk"
      ]
    },
    {
      "addr": 18446744071578986035,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578987501,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578990658,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_top_mfn_init",
        "arch/x86/xen/p2m.c:p2m_top_mfn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578995532,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579018255,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579037592,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586266012,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586268799,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586270819,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/manage.c:xen_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609347733,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586289741,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586295396,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586311196,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenstored_local_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn"
      ]
    },
    {
      "addr": 18446744071586318255,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/xenbus/xenbus_dev_backend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586325717,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/biomerge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586330393,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586344476,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586536143,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587158755,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:get_indirect_grant",
        "drivers/block/xen-blkfront.c:get_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587856754,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578982236,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071586311196,
      "name": "__pfn_to_mfn",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn)
```

```json
{
  "name": "__pfn_to_mfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578979409,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591242186,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk"
      ]
    },
    {
      "addr": 18446744071578987795,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578988989,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578992146,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_top_mfn_init",
        "arch/x86/xen/p2m.c:p2m_top_mfn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578997452,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579020783,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579041192,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586384524,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586385247,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586388563,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/manage.c:xen_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612418693,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586409115,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586414548,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591450136,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenstored_local_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn"
      ]
    },
    {
      "addr": 18446744071586436879,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/xenbus/xenbus_dev_backend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586443573,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/biomerge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586448398,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586460540,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586647359,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587243027,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:get_indirect_grant",
        "drivers/block/xen-blkfront.c:get_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587915063,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591242186,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071591450136,
      "name": "__pfn_to_mfn",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn)
```

```json
{
  "name": "__pfn_to_mfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578988529,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591185256,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk"
      ]
    },
    {
      "addr": 18446744071578996581,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578997965,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579003641,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579006029,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579023839,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579044293,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586268700,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586269419,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586272578,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/manage.c:xen_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614559546,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586293077,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586297988,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591391890,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn"
      ]
    },
    {
      "addr": 18446744071586321119,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/xenbus/xenbus_dev_backend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586327430,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/biomerge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586332355,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586344316,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586531289,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587137854,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:get_indirect_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587797319,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591185256,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071591391890,
      "name": "__pfn_to_mfn",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn)
```

```json
{
  "name": "__pfn_to_mfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579005281,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592047181,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk"
      ]
    },
    {
      "addr": 18446744071579014149,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579015645,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579021337,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579023981,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579042111,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579064483,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586780092,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_add_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586780984,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586784594,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/manage.c:xen_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615513825,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586811013,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586817204,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592436113,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn"
      ]
    },
    {
      "addr": 18446744071586840831,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/xenbus/xenbus_dev_backend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586847190,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/biomerge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586852175,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586864556,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587069596,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587712570,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588398164,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:141",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592047181,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071592436113,
      "name": "__pfn_to_mfn",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn)
```

```json
{
  "name": "__pfn_to_mfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579022135,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593813759,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk"
      ]
    },
    {
      "addr": 18446744071579032912,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579034281,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579039923,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:mfn_to_pfn",
        "arch/x86/xen/p2m.c:mfn_to_pfn",
        "arch/x86/xen/p2m.c:mfn_to_pfn",
        "arch/x86/xen/p2m.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579042580,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579064220,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579088583,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588059834,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_add_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588061728,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588064663,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/manage.c:xen_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617318175,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588093670,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588101535,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594304096,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn"
      ]
    },
    {
      "addr": 18446744071588125666,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/xenbus/xenbus_dev_backend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588133392,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/biomerge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588138968,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn",
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn",
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn",
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588150573,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/grant-dma-ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588372697,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589056744,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589796322,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593813759,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071594304096,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
  "name": "__pfn_to_mfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579050071,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627523882,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_remap_memory",
        "arch/x86/xen/setup.c:xen_remap_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579062349,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579064009,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579069555,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:mfn_to_pfn",
        "arch/x86/xen/p2m.c:mfn_to_pfn",
        "arch/x86/xen/p2m.c:mfn_to_pfn",
        "arch/x86/xen/p2m.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627533022,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579096076,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:convert_pfn_mfn",
        "arch/x86/xen/mmu_pv.c:convert_pfn_mfn",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579123351,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589439946,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_add_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589440992,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589445465,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/manage.c:xen_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628041208,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589478489,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589486505,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628042751,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589512914,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/xenbus/xenbus_dev_backend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589522256,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/biomerge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589528600,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn",
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn",
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn",
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589544349,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589548569,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/grant-dma-ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589795833,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590586280,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591458594,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
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
  "name": "__pfn_to_mfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579050071,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619269197,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_remap_memory",
        "arch/x86/xen/setup.c:xen_remap_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579062221,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579063881,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579069411,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:mfn_to_pfn",
        "arch/x86/xen/p2m.c:mfn_to_pfn",
        "arch/x86/xen/p2m.c:mfn_to_pfn",
        "arch/x86/xen/p2m.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619277918,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579095772,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:convert_pfn_mfn",
        "arch/x86/xen/mmu_pv.c:convert_pfn_mfn",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579123627,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589739386,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_add_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589740432,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589744889,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/manage.c:xen_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619806696,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589778835,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589786969,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619808271,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589813890,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/xenbus/xenbus_dev_backend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589823248,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/biomerge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589829672,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn",
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn",
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn",
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589845949,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589850153,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/grant-dma-ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590101161,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590927552,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:get_indirect_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591874091,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
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
  "name": "__pfn_to_mfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579075399,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621561869,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_remap_memory",
        "arch/x86/xen/setup.c:xen_remap_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579087309,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579088969,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579094499,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:mfn_to_pfn",
        "arch/x86/xen/p2m.c:mfn_to_pfn",
        "arch/x86/xen/p2m.c:mfn_to_pfn",
        "arch/x86/xen/p2m.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621570254,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121564,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:convert_pfn_mfn",
        "arch/x86/xen/mmu_pv.c:convert_pfn_mfn",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149530,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590077370,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_add_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590078416,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590082905,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/manage.c:xen_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622115176,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590114819,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590123097,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622116751,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590150258,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/xenbus/xenbus_dev_backend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590159920,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/biomerge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590166678,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn",
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn",
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn",
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590183005,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590187417,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/xen/grant-dma-ops.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590440390,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591271376,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:get_indirect_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592613757,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:133",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn)
```

```json
{
  "name": "__pfn_to_mfn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490615744,
      "name": "__pfn_to_mfn",
      "external": true,
      "loc": "arch/arm/xen/p2m.c:63",
      "file": "arch/arm/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490615744,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn)
```

```json
{
  "name": "__pfn_to_mfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578967649,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578972860,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ]
    },
    {
      "addr": 18446744071578976371,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578978023,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980782,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604614920,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010652,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579029873,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585309804,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585311014,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585313603,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/manage.c:xen_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604957961,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585331462,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585335940,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585351909,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn"
      ]
    },
    {
      "addr": 18446744071585358703,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xenbus/xenbus_dev_backend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585365701,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/biomerge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585369274,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585382300,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585566665,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586149263,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586785408,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578972860,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071585351909,
      "name": "__pfn_to_mfn",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn)
```

```json
{
  "name": "__pfn_to_mfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578967585,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578972444,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ]
    },
    {
      "addr": 18446744071578975955,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977607,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980366,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604692735,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010236,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579029457,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585498172,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585499382,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585502691,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/manage.c:xen_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605038607,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585519830,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585524308,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585539855,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn"
      ]
    },
    {
      "addr": 18446744071585546479,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xenbus/xenbus_dev_backend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585553477,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/biomerge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585558026,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585571052,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585756073,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586335087,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586982624,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578972444,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071585539855,
      "name": "__pfn_to_mfn",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn)
```

```json
{
  "name": "__pfn_to_mfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578968177,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578973036,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ]
    },
    {
      "addr": 18446744071578976547,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578978199,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980958,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604692691,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579013452,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579033025,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585606204,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585607434,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585610723,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/manage.c:xen_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605062464,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_IRQ"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585627878,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585633684,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585647839,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn"
      ]
    },
    {
      "addr": 18446744071585654447,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xenbus/xenbus_dev_backend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585661429,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/biomerge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585665978,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585679020,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585864025,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586448951,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587089824,
      "name": "__pfn_to_mfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:142",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578973036,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071585647839,
      "name": "__pfn_to_mfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int __pfn_to_mfn(long unsigned int pfn)
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
long unsigned int __pfn_to_mfn(long unsigned int pfn)
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
