# Function: <code>get_phys_to_machine</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int get_phys_to_machine(long unsigned int pfn)
```

```json
{
  "name": "get_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578994240,
      "name": "get_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:437",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_load_gdt",
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
        "arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
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
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xen_pv_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_pv_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_pv_console_init",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578994240,
      "name": "get_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
long unsigned int get_phys_to_machine(long unsigned int pfn)
```

```json
{
  "name": "get_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578990848,
      "name": "get_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:437",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_load_gdt",
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
        "arch/x86/xen/mmu.c:xen_set_domain_pte",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
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
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578990848,
      "name": "get_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
long unsigned int get_phys_to_machine(long unsigned int pfn)
```

```json
{
  "name": "get_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578992688,
      "name": "get_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:437",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_load_gdt",
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
        "arch/x86/xen/mmu.c:xen_set_domain_pte",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
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
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578992688,
      "name": "get_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
long unsigned int get_phys_to_machine(long unsigned int pfn)
```

```json
{
  "name": "get_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578964512,
      "name": "get_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:437",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:remap_area_mfn_pte_fn",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
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
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
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
        "arch/x86/xen/mmu_pv.c:xen_set_domain_pte",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578964512,
      "name": "get_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
long unsigned int get_phys_to_machine(long unsigned int pfn)
```

```json
{
  "name": "get_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578967792,
      "name": "get_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:430",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:remap_area_mfn_pte_fn",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
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
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
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
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967792,
      "name": "get_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
long unsigned int get_phys_to_machine(long unsigned int pfn)
```

```json
{
  "name": "get_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578970480,
      "name": "get_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:430",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
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
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
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
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578970480,
      "name": "get_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
long unsigned int get_phys_to_machine(long unsigned int pfn)
```

```json
{
  "name": "get_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578968608,
      "name": "get_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:432",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
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
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_batched_set_pte",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/swiotlb-xen.c:check_pages_physically_contiguous",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578968608,
      "name": "get_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
long unsigned int get_phys_to_machine(long unsigned int pfn)
```

```json
{
  "name": "get_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578975648,
      "name": "get_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:439",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
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
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
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
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578975648,
      "name": "get_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
long unsigned int get_phys_to_machine(long unsigned int pfn)
```

```json
{
  "name": "get_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578978048,
      "name": "get_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:439",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
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
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
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
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578978048,
      "name": "get_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
long unsigned int get_phys_to_machine(long unsigned int pfn)
```

```json
{
  "name": "get_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578988432,
      "name": "get_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:439",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
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
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_top_mfn_init",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_alloc",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
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
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/block/xen-blkfront.c:get_indirect_grant",
        "drivers/block/xen-blkfront.c:get_indirect_grant",
        "drivers/block/xen-blkfront.c:get_grant",
        "drivers/block/xen-blkfront.c:get_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578988432,
      "name": "get_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
long unsigned int get_phys_to_machine(long unsigned int pfn)
```

```json
{
  "name": "get_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578989920,
      "name": "get_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:435",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
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
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_top_mfn_init",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_alloc",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
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
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/block/xen-blkfront.c:get_indirect_grant",
        "drivers/block/xen-blkfront.c:get_indirect_grant",
        "drivers/block/xen-blkfront.c:get_grant",
        "drivers/block/xen-blkfront.c:get_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578989920,
      "name": "get_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
long unsigned int get_phys_to_machine(long unsigned int pfn)
```

```json
{
  "name": "get_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578998400,
      "name": "get_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:435",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
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
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
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
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:get_indirect_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578998400,
      "name": "get_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
long unsigned int get_phys_to_machine(long unsigned int pfn)
```

```json
{
  "name": "get_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579016080,
      "name": "get_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:435",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
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
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
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
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579016080,
      "name": "get_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
long unsigned int get_phys_to_machine(long unsigned int pfn)
```

```json
{
  "name": "get_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579034832,
      "name": "get_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:435",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:mfn_to_pfn",
        "arch/x86/xen/p2m.c:mfn_to_pfn",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
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
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn",
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579034832,
      "name": "get_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
long unsigned int get_phys_to_machine(long unsigned int pfn)
```

```json
{
  "name": "get_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579064832,
      "name": "get_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:430",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_remap_memory",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:mfn_to_pfn",
        "arch/x86/xen/p2m.c:mfn_to_pfn",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:convert_pfn_mfn",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
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
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn",
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064832,
      "name": "get_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
long unsigned int get_phys_to_machine(long unsigned int pfn)
```

```json
{
  "name": "get_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579064704,
      "name": "get_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:430",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_remap_memory",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:mfn_to_pfn",
        "arch/x86/xen/p2m.c:mfn_to_pfn",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:convert_pfn_mfn",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
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
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn",
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:get_indirect_grant",
        "drivers/block/xen-blkfront.c:get_indirect_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064704,
      "name": "get_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
long unsigned int get_phys_to_machine(long unsigned int pfn)
```

```json
{
  "name": "get_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579089280,
      "name": "get_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:430",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/setup.c:xen_remap_memory",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn",
        "arch/x86/xen/suspend_pv.c:mfn_to_pfn",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_setup_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/p2m.c:mfn_to_pfn",
        "arch/x86/xen/p2m.c:mfn_to_pfn",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:convert_pfn_mfn",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:__xen_write_cr3",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:__xen_set_pte",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn",
        "arch/x86/xen/mmu_pv.c:mfn_to_pfn",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/grant-table.c:gnttab_add_deferred",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_client.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
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
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn",
        "drivers/xen/swiotlb-xen.c:mfn_to_pfn",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:get_indirect_grant",
        "drivers/block/xen-blkfront.c:get_indirect_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579089280,
      "name": "get_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long unsigned int get_phys_to_machine(long unsigned int pfn)
```

```json
{
  "name": "get_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578978400,
      "name": "get_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:439",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
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
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
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
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578978400,
      "name": "get_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long unsigned int get_phys_to_machine(long unsigned int pfn)
```

```json
{
  "name": "get_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578977984,
      "name": "get_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:439",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
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
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
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
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578977984,
      "name": "get_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
long unsigned int get_phys_to_machine(long unsigned int pfn)
```

```json
{
  "name": "get_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578978576,
      "name": "get_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:439",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_post_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
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
        "arch/x86/xen/p2m.c:xen_build_mfn_list_list",
        "arch/x86/xen/p2m.c:p2m_mid_mfn_init",
        "arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note",
        "arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn",
        "arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_create_contiguous_region",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init",
        "arch/x86/xen/mmu_pv.c:pin_pagetable_pfn",
        "arch/x86/xen/mmu_pv.c:xen_do_pin",
        "arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper",
        "arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte_at",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "arch/x86/xen/mmu_pv.c:xen_set_pte",
        "drivers/xen/grant-table.c:gnttab_foreach_grant",
        "drivers/xen/grant-table.c:gnttab_foreach_grant_in_range",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/manage.c:xen_suspend",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/biomerge.c:xen_biovec_phys_mergeable",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
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
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/xlate_mmu.c:xen_for_each_gfn",
        "drivers/tty/hvc/hvc_xen.c:xencons_connect_backend",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578978576,
      "name": "get_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long unsigned int get_phys_to_machine(long unsigned int pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int get_phys_to_machine(long unsigned int pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int get_phys_to_machine(long unsigned int pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int get_phys_to_machine(long unsigned int pfn)
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
long unsigned int get_phys_to_machine(long unsigned int pfn)
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
