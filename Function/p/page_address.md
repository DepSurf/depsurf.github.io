# Function: <code>page_address</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void * page_address(const struct page * page)
```

```json
{
  "name": "page_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226557600,
      "name": "page_address",
      "external": true,
      "loc": "mm/highmem.c:408",
      "file": "mm/highmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "arch/arm/kernel/signal.c:get_signal_page",
        "arch/arm/kernel/machine_kexec.c:machine_kexec",
        "arch/arm/mm/dma-mapping.c:dma_cache_maint_page",
        "arch/arm/mm/dma-mapping.c:simple_allocator_alloc",
        "arch/arm/mm/dma-mapping.c:__alloc_from_contiguous",
        "arch/arm/mm/dma-mapping.c:__dma_remap",
        "arch/arm/mm/dma-mapping.c:__dma_clear_buffer",
        "arch/arm/mm/flush.c:__flush_anon_page",
        "arch/arm/mm/highmem.c:kmap_atomic_pfn",
        "arch/arm/mm/highmem.c:kmap",
        "kernel/fork.c:copy_process",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_end_io",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/virt.c:dma_virt_map_page",
        "kernel/profile.c:profile_prepare_cpu",
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_add_entry",
        "kernel/kexec_core.c:kimage_alloc_control_pages",
        "kernel/kexec_core.c:kimage_free_pages",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/trace/trace.c:trace_buffered_event_enable",
        "kernel/trace/trace_uprobe.c:probe_event_enable",
        "kernel/events/ring_buffer.c:rb_alloc_aux",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/slab_common.c:kmalloc_order",
        "mm/highmem.c:kunmap_high",
        "mm/memory.c:do_fault",
        "mm/memory.c:__do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:__vunmap",
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:__get_free_pages",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:alloc_pages_exact_nid",
        "mm/slub.c:process_slab",
        "mm/slub.c:validate_slab_slab",
        "mm/slub.c:__check_heap_object",
        "mm/slub.c:__check_heap_object",
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:on_freelist",
        "mm/slub.c:check_object",
        "mm/slub.c:print_trailer",
        "mm/slub.c:get_map",
        "mm/swap_cgroup.c:swap_cgroup_record",
        "mm/swap_cgroup.c:lookup_swap_cgroup",
        "mm/zbud.c:zbud_alloc",
        "fs/namei.c:__page_symlink",
        "fs/namei.c:page_get_link",
        "fs/splice.c:default_file_splice_read",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/dir.c:fuse_readlink_page",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "security/selinux/ss/status.c:selinux_status_update_policyload",
        "security/selinux/ss/status.c:selinux_status_update_setenforce",
        "security/selinux/ss/status.c:selinux_kernel_status_page",
        "crypto/skcipher.c:skcipher_walk_next",
        "crypto/skcipher.c:skcipher_walk_next",
        "crypto/skcipher.c:skcipher_walk_next",
        "crypto/skcipher.c:skcipher_walk_done",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_kern_endio_read",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq.c:blk_mq_free_rqs",
        "block/partition-generic.c:read_dev_sector",
        "block/bounce.c:__blk_queue_bounce",
        "block/bounce.c:copy_to_high_bio_irq",
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_free",
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity",
        "drivers/irqchip/irq-gic-v3-its.c:its_alloc_table_entry",
        "drivers/irqchip/irq-gic-v3-its.c:its_free_pending_table",
        "drivers/irqchip/irq-gic-v3-its.c:its_allocate_pending_table",
        "drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables",
        "drivers/irqchip/irq-gic-v3-its.c:its_free_prop_table",
        "drivers/irqchip/irq-gic-v3-its.c:its_allocate_prop_table",
        "drivers/irqchip/irq-gic-v3-its.c:lpi_write_config",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_vmapp_cmd",
        "drivers/dma/mv_xor.c:mv_chan_xor_self_test",
        "drivers/dma/mv_xor.c:mv_chan_xor_self_test",
        "drivers/dma/mv_xor.c:mv_chan_xor_self_test",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:return_free_pages_to_mm",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_unmap",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_map",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_map",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_pte_lookup",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_pte_lookup",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_set_pde",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_fill_rx_channels",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/devio.c:processcompl",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:free_async",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:super_1_rdev_size_change",
        "drivers/md/md.c:super_1_sync",
        "drivers/md/md.c:super_1_sync",
        "drivers/md/md.c:super_1_validate",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_90_sync",
        "drivers/md/md.c:super_90_validate",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/dev.c:skb_gro_reset_offset",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data",
        "net/core/filter.c:bpf_msg_pull_data",
        "net/core/filter.c:bpf_msg_pull_data",
        "net/core/tso.c:tso_start",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_msg_memcopy_from_iter",
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_clone",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv6/ip6_output.c:__ip6_append_data",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226557600,
      "name": "page_address",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void * page_address(const struct page * page)
```
</details>
</li>
</ul>
