# Function: <code>alloc_pages_current</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct page * alloc_pages_current(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages_current",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580813248,
      "name": "alloc_pages_current",
      "external": true,
      "loc": "mm/mempolicy.c:2036",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/power/snapshot.c:alloc_image_page",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/page_alloc.c:get_zeroed_page",
        "mm/page_alloc.c:alloc_pages_exact",
        "mm/page_alloc.c:alloc_kmem_pages",
        "mm/memory.c:__pmd_alloc",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab",
        "mm/huge_memory.c:get_huge_zero_page",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/page_isolation.c:alloc_migrate_target",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:zs_malloc",
        "mm/balloon_compaction.c:balloon_page_enqueue",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:default_file_splice_read",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepages_fill",
        "security/selinux/ss/status.c:selinux_kernel_status_page",
        "block/bio.c:bio_alloc_pages",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_copy_kern",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/intel-iommu.c:intel_alloc_coherent",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/base/firmware_class.c:firmware_data_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/scsi/sd.c:sd_setup_discard_cmnd",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/md/md.c:super_1_load",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/dm-kcopyd.c:alloc_pl",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580813248,
      "name": "alloc_pages_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
struct page * alloc_pages_current(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages_current",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580936832,
      "name": "alloc_pages_current",
      "external": true,
      "loc": "mm/mempolicy.c:2053",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/power/snapshot.c:alloc_image_page",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/page_alloc.c:alloc_pages_exact",
        "mm/page_alloc.c:get_zeroed_page",
        "mm/slab_common.c:kmalloc_order_trace",
        "mm/memory.c:__pmd_alloc",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab",
        "mm/huge_memory.c:get_huge_zero_page",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/page_isolation.c:alloc_migrate_target",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:zs_malloc",
        "mm/balloon_compaction.c:balloon_page_enqueue",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:default_file_splice_read",
        "fs/dax.c:read_dax_sector",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "security/selinux/ss/status.c:selinux_kernel_status_page",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/intel-iommu.c:intel_alloc_coherent",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/base/firmware_class.c:firmware_data_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/md/md.c:super_1_load",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/dm-kcopyd.c:alloc_pl",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580936832,
      "name": "alloc_pages_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
struct page * alloc_pages_current(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages_current",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581008576,
      "name": "alloc_pages_current",
      "external": true,
      "loc": "mm/mempolicy.c:2047",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/power/snapshot.c:alloc_image_page",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/page_alloc.c:__get_free_pages",
        "mm/slab_common.c:kmalloc_order",
        "mm/memory.c:__pmd_alloc",
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/page_isolation.c:alloc_migrate_target",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:zs_malloc",
        "mm/balloon_compaction.c:balloon_page_enqueue",
        "fs/pipe.c:pipe_write",
        "fs/dax.c:read_dax_sector",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "security/selinux/ss/status.c:selinux_kernel_status_page",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_alloc_pages",
        "block/blk-zoned.c:blkdev_report_zones",
        "lib/iov_iter.c:push_pipe",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/intel-iommu.c:intel_alloc_coherent",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/base/firmware_class.c:firmware_data_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/dm-kcopyd.c:alloc_pl",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581008576,
      "name": "alloc_pages_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
struct page * alloc_pages_current(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages_current",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581052512,
      "name": "alloc_pages_current",
      "external": true,
      "loc": "mm/mempolicy.c:1959",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/power/snapshot.c:alloc_image_page",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/page_alloc.c:__get_free_pages",
        "mm/slab_common.c:kmalloc_order",
        "mm/memory.c:__pmd_alloc",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:zs_malloc",
        "mm/balloon_compaction.c:balloon_page_enqueue",
        "fs/pipe.c:pipe_write",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "security/selinux/ss/status.c:selinux_kernel_status_page",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_alloc_pages",
        "block/blk-zoned.c:blkdev_report_zones",
        "lib/iov_iter.c:push_pipe",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_getcap",
        "drivers/char/tpm/tpm-interface.c:tpm_startup",
        "drivers/char/tpm/tpm-interface.c:tpm_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/intel-iommu.c:intel_alloc_coherent",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/base/firmware_class.c:firmware_data_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/dm-kcopyd.c:alloc_pl",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581052512,
      "name": "alloc_pages_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct page * alloc_pages_current(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages_current",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581163648,
      "name": "alloc_pages_current",
      "external": true,
      "loc": "mm/mempolicy.c:2021",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/power/snapshot.c:alloc_image_page",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/page_alloc.c:__get_free_pages",
        "mm/slab_common.c:kmalloc_order",
        "mm/memory.c:__pmd_alloc",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:zs_malloc",
        "mm/balloon_compaction.c:balloon_page_alloc",
        "fs/pipe.c:pipe_write",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "security/selinux/ss/status.c:selinux_kernel_status_page",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_alloc_pages",
        "block/blk-zoned.c:blkdev_report_zones",
        "lib/iov_iter.c:push_pipe",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_getcap",
        "drivers/char/tpm/tpm-interface.c:tpm_startup",
        "drivers/char/tpm/tpm-interface.c:tpm_startup",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/intel-iommu.c:intel_alloc_coherent",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/base/firmware_class.c:firmware_data_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md-bitmap.c:bitmap_resize",
        "drivers/md/md-bitmap.c:bitmap_resize",
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/dm-kcopyd.c:alloc_pl",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581163648,
      "name": "alloc_pages_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct page * alloc_pages_current(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages_current",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581306976,
      "name": "alloc_pages_current",
      "external": true,
      "loc": "mm/mempolicy.c:2078",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/power/snapshot.c:alloc_image_page",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/page_alloc.c:__get_free_pages",
        "mm/slab_common.c:kmalloc_order",
        "mm/memory.c:__pmd_alloc",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:zs_malloc",
        "mm/balloon_compaction.c:balloon_page_alloc",
        "fs/pipe.c:pipe_write",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "security/selinux/ss/status.c:selinux_kernel_status_page",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov",
        "block/blk-zoned.c:blkdev_report_zones",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/iov_iter.c:push_pipe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_getcap",
        "drivers/char/tpm/tpm-interface.c:tpm_startup",
        "drivers/char/tpm/tpm-interface.c:tpm_startup",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/intel-iommu.c:intel_alloc_coherent",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md-bitmap.c:bitmap_resize",
        "drivers/md/md-bitmap.c:bitmap_resize",
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/dm-kcopyd.c:alloc_pl",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/filter.c:bpf_msg_pull_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581306976,
      "name": "alloc_pages_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
struct page * alloc_pages_current(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages_current",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581389920,
      "name": "alloc_pages_current",
      "external": true,
      "loc": "mm/mempolicy.c:2117",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/power/snapshot.c:alloc_image_page",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/page_alloc.c:__get_free_pages",
        "mm/slab_common.c:kmalloc_order",
        "mm/memory.c:__pmd_alloc",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:zs_malloc",
        "mm/balloon_compaction.c:balloon_page_alloc",
        "fs/pipe.c:pipe_write",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/readdir.c:fuse_readdir",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "security/selinux/ss/status.c:selinux_kernel_status_page",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/iov_iter.c:push_pipe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/virtio/virtio_balloon.c:report_free_page_func",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/intel-iommu.c:intel_alloc_coherent",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/dm-kcopyd.c:alloc_pl",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581389920,
      "name": "alloc_pages_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
struct page * alloc_pages_current(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages_current",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581501632,
      "name": "alloc_pages_current",
      "external": true,
      "loc": "mm/mempolicy.c:2138",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/power/snapshot.c:alloc_image_page",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/slab_common.c:kmalloc_order",
        "mm/memory.c:__pmd_alloc",
        "mm/page_alloc.c:__get_free_pages",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/slub.c:alloc_slab_page",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:zs_malloc",
        "mm/balloon_compaction.c:balloon_page_alloc",
        "fs/pipe.c:pipe_write",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "security/selinux/ss/status.c:selinux_kernel_status_page",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/iov_iter.c:push_pipe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
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
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/dm-kcopyd.c:alloc_pl",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/memmap.c:__efi_memmap_alloc_late",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581501632,
      "name": "alloc_pages_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
struct page * alloc_pages_current(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages_current",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581566000,
      "name": "alloc_pages_current",
      "external": true,
      "loc": "mm/mempolicy.c:2177",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/power/snapshot.c:alloc_image_page",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/slab_common.c:kmalloc_order",
        "mm/memory.c:__pmd_alloc",
        "mm/page_alloc.c:__get_free_pages",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/slub.c:alloc_slab_page",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:zs_malloc",
        "mm/balloon_compaction.c:balloon_page_alloc",
        "fs/pipe.c:pipe_write",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "security/selinux/ss/status.c:selinux_kernel_status_page",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/iov_iter.c:push_pipe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
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
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/dm-kcopyd.c:alloc_pl",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/memmap.c:__efi_memmap_alloc_late",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581566000,
      "name": "alloc_pages_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
struct page * alloc_pages_current(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages_current",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581780992,
      "name": "alloc_pages_current",
      "external": true,
      "loc": "mm/mempolicy.c:2277",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "init/do_mounts.c:mount_block_root",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/power/snapshot.c:alloc_image_page",
        "kernel/dma/pool.c:atomic_pool_expand",
        "kernel/time/namespace.c:clone_time_ns",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "kernel/watch_queue.c:watch_queue_set_size",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/slab_common.c:kmalloc_order",
        "mm/memory.c:__pmd_alloc",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/page_alloc.c:alloc_pages_exact",
        "mm/page_alloc.c:get_zeroed_page",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/slub.c:alloc_slab_page",
        "mm/huge_memory.c:get_huge_zero_page",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:alloc_zspage",
        "mm/balloon_compaction.c:balloon_page_alloc",
        "fs/pipe.c:pipe_write",
        "fs/squashfs/block.c:squashfs_bio_read",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "security/selinux/status.c:selinux_kernel_status_page",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:bio_copy_user_iov",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/iov_iter.c:push_pipe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/virtio/virtio_balloon.c:get_free_page_and_send",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_gtt_setup_scratch_page",
        "drivers/iommu/intel/iommu.c:intel_alloc_coherent",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf",
        "drivers/block/loop.c:lo_read_transfer",
        "drivers/block/loop.c:lo_write_transfer",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:fill_grant_buffer",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/scsi/sg.c:sg_build_indirect",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/vfio/vfio_iommu_type1.c:vfio_test_domain_fgsp",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md-bitmap.c:md_bitmap_storage_alloc",
        "drivers/md/md-bitmap.c:md_bitmap_storage_alloc",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581780992,
      "name": "alloc_pages_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
struct page * alloc_pages_current(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages_current",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581838816,
      "name": "alloc_pages_current",
      "external": true,
      "loc": "mm/mempolicy.c:2252",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "init/do_mounts.c:mount_block_root",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/power/snapshot.c:alloc_image_page",
        "kernel/dma/pool.c:atomic_pool_expand",
        "kernel/time/namespace.c:clone_time_ns",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "kernel/watch_queue.c:watch_queue_set_size",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read_get_pages",
        "mm/filemap.c:pagecache_get_page",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/slab_common.c:kmalloc_order",
        "mm/memory.c:__pmd_alloc",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/page_alloc.c:alloc_pages_exact",
        "mm/page_alloc.c:get_zeroed_page",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/huge_memory.c:get_huge_zero_page",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:alloc_zspage",
        "mm/balloon_compaction.c:balloon_page_alloc",
        "fs/pipe.c:pipe_write",
        "fs/squashfs/block.c:squashfs_bio_read",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "security/selinux/status.c:selinux_kernel_status_page",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:bio_copy_user_iov",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/iov_iter.c:push_pipe",
        "drivers/virtio/virtio_balloon.c:get_free_page_and_send",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_gtt_setup_scratch_page",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf",
        "drivers/block/loop.c:lo_read_transfer",
        "drivers/block/loop.c:lo_write_transfer",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:fill_grant_buffer",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/scsi/sg.c:sg_build_indirect",
        "drivers/vfio/vfio_iommu_type1.c:vfio_test_domain_fgsp",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md-bitmap.c:md_bitmap_storage_alloc",
        "drivers/md/md-bitmap.c:md_bitmap_storage_alloc",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581838816,
      "name": "alloc_pages_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct page * alloc_pages_current(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages_current",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493007888,
      "name": "alloc_pages_current",
      "external": true,
      "loc": "mm/mempolicy.c:2177",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "virt/kvm/kvm_main.c:kvm_vcpu_init",
        "virt/kvm/coalesced_mmio.c:kvm_coalesced_mmio_init",
        "virt/kvm/arm/mmu.c:__create_hyp_mappings",
        "kernel/dma/remap.c:dma_atomic_pool_init",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/slab_common.c:kmalloc_order",
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:do_fault",
        "mm/memory.c:__do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/page_alloc.c:alloc_pages_exact",
        "mm/page_alloc.c:get_zeroed_page",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/slub.c:alloc_slab_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:zs_malloc",
        "mm/balloon_compaction.c:balloon_page_alloc",
        "fs/pipe.c:pipe_write",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "security/selinux/ss/status.c:selinux_kernel_status_page",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/iov_iter.c:push_pipe",
        "drivers/irqchip/irq-gic-v3-its.c:its_allocate_pending_table",
        "drivers/irqchip/irq-gic-v3-its.c:its_allocate_prop_table",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
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
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/dm-kcopyd.c:alloc_pl",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493007888,
      "name": "alloc_pages_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct page * alloc_pages_current(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages_current",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286430016,
      "name": "alloc_pages_current",
      "external": true,
      "loc": "mm/mempolicy.c:2177",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "arch/powerpc/mm/pgtable-frag.c:pte_fragment_alloc",
        "arch/powerpc/mm/pgtable-frag.c:pte_fragment_alloc",
        "arch/powerpc/mm/book3s64/pgtable.c:pmd_fragment_alloc",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/slab_common.c:kmalloc_order",
        "mm/page_alloc.c:__get_free_pages",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/slub.c:alloc_slab_page",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:zs_malloc",
        "mm/balloon_compaction.c:balloon_page_alloc",
        "fs/pipe.c:pipe_write",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "security/selinux/ss/status.c:selinux_kernel_status_page",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/iov_iter.c:push_pipe",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
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
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/scsi/sg.c:sg_build_indirect",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/dm-kcopyd.c:alloc_pl",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286430016,
      "name": "alloc_pages_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
    }
  ]
}
```
</details>
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
struct page * alloc_pages_current(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages_current",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581534736,
      "name": "alloc_pages_current",
      "external": true,
      "loc": "mm/mempolicy.c:2177",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/power/snapshot.c:alloc_image_page",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/slab_common.c:kmalloc_order",
        "mm/memory.c:__pmd_alloc",
        "mm/page_alloc.c:__get_free_pages",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/slub.c:alloc_slab_page",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:zs_malloc",
        "mm/balloon_compaction.c:balloon_page_alloc",
        "fs/pipe.c:pipe_write",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "security/selinux/ss/status.c:selinux_kernel_status_page",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/iov_iter.c:push_pipe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
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
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/intel-iommu.c:intel_alloc_coherent",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/nvme/host/core.c:nvme_init_ctrl",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/dm-kcopyd.c:alloc_pl",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/memmap.c:__efi_memmap_alloc_late",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581534736,
      "name": "alloc_pages_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
struct page * alloc_pages_current(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages_current",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581476496,
      "name": "alloc_pages_current",
      "external": true,
      "loc": "mm/mempolicy.c:2177",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/power/snapshot.c:alloc_image_page",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/slab_common.c:kmalloc_order",
        "mm/memory.c:__pmd_alloc",
        "mm/page_alloc.c:__get_free_pages",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/slub.c:alloc_slab_page",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:zs_malloc",
        "mm/balloon_compaction.c:balloon_page_alloc",
        "fs/pipe.c:pipe_write",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "security/selinux/ss/status.c:selinux_kernel_status_page",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/iov_iter.c:push_pipe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
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
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/nvme/host/core.c:nvme_init_ctrl",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/dm-kcopyd.c:alloc_pl",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/memmap.c:__efi_memmap_alloc_late",
        "drivers/hv/channel.c:vmbus_alloc_ring",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581476496,
      "name": "alloc_pages_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
struct page * alloc_pages_current(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages_current",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581526048,
      "name": "alloc_pages_current",
      "external": true,
      "loc": "mm/mempolicy.c:2177",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/power/snapshot.c:alloc_image_page",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/slab_common.c:kmalloc_order",
        "mm/memory.c:__pmd_alloc",
        "mm/page_alloc.c:__get_free_pages",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/slub.c:alloc_slab_page",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:zs_malloc",
        "mm/balloon_compaction.c:balloon_page_alloc",
        "fs/pipe.c:pipe_write",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "security/selinux/ss/status.c:selinux_kernel_status_page",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/iov_iter.c:push_pipe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
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
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/dm-kcopyd.c:alloc_pl",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/memmap.c:__efi_memmap_alloc_late",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581526048,
      "name": "alloc_pages_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
struct page * alloc_pages_current(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages_current",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581591328,
      "name": "alloc_pages_current",
      "external": true,
      "loc": "mm/mempolicy.c:2177",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/power/snapshot.c:alloc_image_page",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/slab_common.c:kmalloc_order",
        "mm/memory.c:__pmd_alloc",
        "mm/page_alloc.c:__get_free_pages",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/slub.c:alloc_slab_page",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:zs_malloc",
        "mm/balloon_compaction.c:balloon_page_alloc",
        "fs/pipe.c:pipe_write",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "security/selinux/ss/status.c:selinux_kernel_status_page",
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/iov_iter.c:push_pipe",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
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
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/dm-kcopyd.c:alloc_pl",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "drivers/firmware/efi/memmap.c:__efi_memmap_alloc_late",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581591328,
      "name": "alloc_pages_current",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct page * alloc_pages_current(gfp_t gfp, unsigned int order)
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
struct page * alloc_pages_current(gfp_t gfp, unsigned int order)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct page * alloc_pages_current(gfp_t gfp, unsigned int order)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
