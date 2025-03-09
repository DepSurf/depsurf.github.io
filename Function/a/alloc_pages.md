# Function: <code>alloc_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594943365,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266666,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579293014,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579306982,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pte_alloc_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595077299,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579698022,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:alloc_image_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579944060,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580144953,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580226944,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580447091,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__create_xol_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580472948,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580483161,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580490569,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_zeroed_page",
        "mm/page_alloc.c:alloc_pages_exact",
        "mm/page_alloc.c:alloc_kmem_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580674741,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580742062,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580774885,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587361003,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580850711,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580899887,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:get_huge_zero_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580945571,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580959065,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:alloc_migrate_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580961049,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580965671,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580972134,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581028368,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581200519,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582014506,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582048191,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582069924,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582079887,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepages_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582370532,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "security/selinux/ss/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582713192,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_alloc_pages",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_copy_kern"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583851815,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584183726,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584208822,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584226501,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584245063,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584289408,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584329730,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584334910,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584475408,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "drivers/base/firmware_class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:firmware_data_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584534447,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "drivers/block/brd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584548641,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584574675,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584871158,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_setup_discard_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584893391,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585082154,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:try_fill_recv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585116450,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585734518,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585783919,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585840000,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:alloc_pl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586191118,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586211437,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:456",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags"
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
  "name": "alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595107120,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266104,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579292503,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579306470,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pte_alloc_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595243844,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579717366,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:alloc_image_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579974908,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580179734,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580263936,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580522131,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__create_xol_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580549741,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580565513,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580586182,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_pages_exact",
        "mm/page_alloc.c:get_zeroed_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580729904,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order_trace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580789004,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580861242,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580898151,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587862085,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580976461,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581024352,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:get_huge_zero_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581094928,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581110516,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:alloc_migrate_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581112469,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581118352,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581126118,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581187699,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581365155,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581496900,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:read_dax_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582230710,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582262671,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582284321,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582295278,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
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
      "addr": 18446744071582591668,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "security/selinux/ss/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582999239,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584181339,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584522842,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584548214,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584568549,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584587165,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584632300,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584676562,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584682262,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584821017,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "drivers/base/firmware_class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:firmware_data_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584884687,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "drivers/block/brd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584899880,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584928977,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585222409,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585255912,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585474454,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:try_fill_recv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585509487,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586138742,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:super_1_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586181868,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586234512,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:alloc_pl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586403178,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586613623,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586636348,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:467",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs"
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
  "name": "alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595353041,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579281535,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579307924,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321974,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pte_alloc_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595487821,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579744934,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:alloc_image_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580005388,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580219964,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580306973,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580591811,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__create_xol_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580612269,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580631913,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580641945,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__get_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580795608,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580853372,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580931546,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_node_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580966554,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588076791,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581050297,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581099170,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581170160,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581185684,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "mm/page_isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_isolation.c:alloc_migrate_target"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581187637,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581193460,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201158,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264884,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581577732,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:read_dax_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582320214,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582352319,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582372718,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582383359,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
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
      "addr": 18446744071582684900,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "security/selinux/ss/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583017959,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "crypto/scompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:scomp_acomp_comp_decomp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583104183,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583337652,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blkdev_report_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583430791,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:push_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584362681,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584704922,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584730166,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584750453,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584768736,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584816846,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584862995,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584868838,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585014554,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "drivers/base/firmware_class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:firmware_data_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585089724,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585112209,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585417207,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585455592,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585697479,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586346914,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
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
      "addr": 18446744071586385710,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586439360,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:alloc_pl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586612458,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595762938,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586797703,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586821756,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:460",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs"
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
  "name": "alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596270863,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579278175,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579305690,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319238,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pte_alloc_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596409247,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579742214,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:alloc_image_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580013260,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580230034,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580320113,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580621843,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__create_xol_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580640623,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580659545,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580674361,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__get_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580836344,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580898556,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975794,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581013514,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588303219,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581098074,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147985,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581218347,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581235864,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581240963,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581248598,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581313774,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582404966,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437297,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582457165,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582468332,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
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
      "addr": 18446744071582777508,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "security/selinux/ss/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583069697,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "crypto/scompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:scomp_acomp_comp_decomp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583159896,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583396404,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blkdev_report_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583452023,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:push_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584444328,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584786323,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584812294,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584831324,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584838120,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_getcap",
        "drivers/char/tpm/tpm-interface.c:tpm_startup",
        "drivers/char/tpm/tpm-interface.c:tpm_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584852991,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584858488,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584906075,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584952131,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584957958,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585099811,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "drivers/base/firmware_class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:firmware_data_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585172270,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585194438,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585507407,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585539829,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585785295,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586447458,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
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
      "addr": 18446744071586487932,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586544586,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:alloc_pl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586737597,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596692014,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586919746,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586959829,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:505",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs"
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
  "name": "alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602586845,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579018980,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296783,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579327898,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342310,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pte_alloc_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602733910,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579775094,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:alloc_image_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580060148,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580280898,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580373268,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580702755,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__create_xol_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580723418,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580744521,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580759721,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__get_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580927032,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581000652,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581078385,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581122391,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581217249,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581268497,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581348987,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581367368,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581372595,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581380294,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581453966,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582555702,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582587655,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582607949,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582619038,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
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
      "addr": 18446744071582933572,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "security/selinux/ss/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583235867,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "crypto/scompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:scomp_acomp_comp_decomp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583335656,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov",
        "block/bio.c:bio_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583575865,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blkdev_report_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583632119,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:push_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584853940,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585206553,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585233062,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585253289,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585259096,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_getcap",
        "drivers/char/tpm/tpm-interface.c:tpm_startup",
        "drivers/char/tpm/tpm-interface.c:tpm_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585264182,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585272531,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585277528,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585327147,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585373251,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585379222,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585525587,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/base/firmware_class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:firmware_data_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585600471,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585622598,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585937941,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585971525,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586223983,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586916114,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
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
      "addr": 18446744071586955612,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:bitmap_resize",
        "drivers/md/md-bitmap.c:bitmap_resize",
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/md-bitmap.c:bitmap_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587012154,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:alloc_pl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587222093,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603022071,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587412239,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587445685,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs"
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
  "name": "alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602755079,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579020815,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338976,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579353509,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pte_alloc_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602905747,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579816478,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:alloc_image_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580117605,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580342055,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580434594,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580835199,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__create_xol_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580858643,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580880325,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580895589,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__get_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581062549,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581134280,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581217327,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581262869,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581354562,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581417323,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581497178,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581517224,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581524097,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530293,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613600,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582747819,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582778784,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582800930,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582810494,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
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
      "addr": 18446744071582961420,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_alloc_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583133511,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "security/selinux/ss/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544876,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583792060,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blkdev_report_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583845113,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583848662,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:push_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584388375,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585085028,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585442713,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585469349,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585489922,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585495893,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_getcap",
        "drivers/char/tpm/tpm-interface.c:tpm_startup",
        "drivers/char/tpm/tpm-interface.c:tpm_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585501194,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585509519,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585514517,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585568011,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585615283,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585622197,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585773049,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_data_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585845497,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585866403,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586184105,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586219665,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586480725,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587191943,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
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
      "addr": 18446744071587250724,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:bitmap_resize",
        "drivers/md/md-bitmap.c:bitmap_resize",
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/md-bitmap.c:bitmap_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587310362,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:alloc_pl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587523196,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603194819,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587721776,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587749936,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
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
      "addr": 18446744071587969528,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:490",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pull_data"
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
  "name": "alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604549086,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579022655,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604668192,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365580,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579380533,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pte_alloc_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604703900,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579863168,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:alloc_image_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580164293,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580397933,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580490258,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580903631,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__create_xol_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580927123,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580953637,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580970405,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__get_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581140357,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581210712,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581301042,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581345749,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581438424,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581503371,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581583018,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581603112,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612465,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616085,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699950,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582851611,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582883216,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582899826,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582913462,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
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
      "addr": 18446744071582949584,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583072492,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_alloc_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583249495,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "security/selinux/ss/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583668124,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583928809,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583932534,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:push_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584480281,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585184174,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585195614,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585566297,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585592693,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585612421,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585626375,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
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
      "addr": 18446744071585632323,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585634181,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585638122,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585693035,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585739747,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585749541,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585762482,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585906297,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_data_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585977381,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586000291,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586360221,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586628373,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587372039,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
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
      "addr": 18446744071587431460,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587490458,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:alloc_pl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587704028,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605005167,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587850080,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587884015,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
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
      "addr": 18446744071588124086,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
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
  "name": "alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604643323,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579030188,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604766906,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579381601,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579395925,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pte_alloc_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604804229,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579897555,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:alloc_image_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580210293,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580451088,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580546084,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581001349,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__create_xol_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581023067,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581048885,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581205925,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581286872,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581378190,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581388245,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__get_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581456085,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581548385,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613120,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581694039,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581714597,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581724093,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581728085,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581817714,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583026302,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583062304,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583080032,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583092868,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
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
      "addr": 18446744071583130567,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583256876,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_alloc_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583436408,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "security/selinux/ss/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583856892,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584108677,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584110725,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:push_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584677591,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585396348,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585407968,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585785801,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585812661,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585833519,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585843137,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585846645,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
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
      "addr": 18446744071585855445,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
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
      "addr": 18446744071585856968,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585861779,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585925930,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585970179,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585981221,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585994498,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586141436,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586223740,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586230859,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586603726,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586881845,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587645303,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
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
      "addr": 18446744071587703665,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
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
      "addr": 18446744071587764207,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:alloc_pl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587983036,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605117770,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:__efi_memmap_alloc_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588154151,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588189233,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
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
      "addr": 18446744071588460410,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:507",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
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
  "name": "alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604655584,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579032508,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604792744,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385905,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579399237,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pte_alloc_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604829950,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579947827,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:alloc_image_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580258667,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580500048,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580593636,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581056197,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__create_xol_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581078315,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581104549,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264661,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581345592,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439392,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581449189,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__get_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581520245,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613265,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581684032,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581767479,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581788053,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581797661,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581801637,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581890274,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583132510,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583168736,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583184032,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583204619,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071583236811,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583362732,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_alloc_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583542312,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "security/selinux/ss/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583959538,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584230037,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584233525,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:push_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584816887,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585536668,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585548720,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585929337,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585955301,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585976175,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585989205,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071585998023,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071585999560,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586004371,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586069338,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586114467,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586128229,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586141874,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586289916,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586372132,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586379083,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586751166,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587027861,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587057950,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587849399,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071587907953,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071587968655,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:alloc_pl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588190236,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605157219,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:__efi_memmap_alloc_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588359415,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588394385,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071588666029,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
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
  "name": "alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609007221,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root",
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579041451,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609135259,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408629,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pte_alloc_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427021,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609167156,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579992809,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:alloc_image_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580153520,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "kernel/dma/pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:atomic_pool_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580261392,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "kernel/time/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/namespace.c:clone_time_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580327846,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582075,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_alloc_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580692675,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581238177,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__create_xol_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581257764,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:watch_queue_set_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281829,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
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
      "addr": 18446744071581287205,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581453781,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581541944,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581647856,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581670419,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_pages_exact",
        "mm/page_alloc.c:get_zeroed_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581727765,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581833241,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581894423,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:get_huge_zero_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581986204,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582009961,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582013773,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:alloc_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582021861,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582119654,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583339497,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583453517,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583492464,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583509008,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583523255,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
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
      "addr": 18446744071583565791,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583818904,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "security/selinux/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584391220,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584638442,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584640802,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:push_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585510615,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586249229,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:get_free_page_and_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586268464,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586663925,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586694533,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586717519,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gtt_setup_scratch_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586865642,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586881461,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586897682,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587060284,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587139232,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_read_transfer",
        "drivers/block/loop.c:lo_write_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587157555,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:fill_grant_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587408078,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587555893,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_build_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587856554,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587880677,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_test_domain_fgsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588691495,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
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
      "addr": 18446744071588751877,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_storage_alloc",
        "drivers/md/md-bitmap.c:md_bitmap_storage_alloc",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588822331,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589056322,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609426554,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589218460,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589258235,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
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
      "addr": 18446744071589514207,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:543",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
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
  "name": "alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612071331,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root",
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579044571,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267609,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612203924,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409125,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pte_alloc_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426717,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612237266,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591294848,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:alloc_image_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580134558,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "kernel/dma/pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:atomic_pool_expand"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580245025,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "kernel/time/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/namespace.c:clone_time_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580313318,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580571195,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_alloc_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580683475,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581280945,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__create_xol_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299844,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:watch_queue_set_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581325810,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_buffered_read_get_pages",
        "mm/filemap.c:pagecache_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330677,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581502591,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581585131,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581694330,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581717901,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_pages_exact",
        "mm/page_alloc.c:get_zeroed_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581775813,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581880294,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581940263,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:get_huge_zero_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582036188,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582058437,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582062253,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:alloc_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582070293,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582166006,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583456092,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_bio_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583566323,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583600880,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583617959,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583632412,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
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
      "addr": 18446744071583678143,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583940280,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "security/selinux/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584505316,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584757969,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584761602,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:push_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586367501,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:get_free_page_and_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586384912,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586773829,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586797269,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591468767,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gtt_setup_scratch_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586931797,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586982546,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587144780,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587218653,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_read_transfer",
        "drivers/block/loop.c:lo_write_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587241827,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:fill_grant_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587476095,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587623860,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_build_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587941493,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_test_domain_fgsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588718359,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
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
      "addr": 18446744071588772837,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_storage_alloc",
        "drivers/md/md-bitmap.c:md_bitmap_storage_alloc",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588838987,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071612500362,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589063934,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589216471,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589257371,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
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
      "addr": 18446744071589519767,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:545",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
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
struct page * alloc_pages(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581869632,
      "name": "alloc_pages",
      "external": true,
      "loc": "mm/mempolicy.c:2257",
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
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/relay.c:relay_create_buf",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "kernel/watch_queue.c:watch_queue_set_size",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/slab_common.c:kmalloc_order",
        "mm/memory.c:__pmd_alloc",
        "mm/page_alloc.c:alloc_pages_exact",
        "mm/page_alloc.c:get_zeroed_page",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
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
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "security/selinux/status.c:selinux_kernel_status_page",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:bio_copy_user_iov",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/iov_iter.c:push_pipe",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf",
        "drivers/block/loop.c:lo_read_transfer",
        "drivers/block/loop.c:lo_write_transfer",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/scsi/sg.c:sg_build_indirect",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/md/dm-kcopyd.c:alloc_pl",
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
      "addr": 18446744071581869632,
      "name": "alloc_pages",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct page * alloc_pages(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582161008,
      "name": "alloc_pages",
      "external": true,
      "loc": "mm/mempolicy.c:2172",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "init/do_mounts.c:do_mount_root",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/power/snapshot.c:alloc_image_page",
        "kernel/dma/pool.c:atomic_pool_expand",
        "kernel/dma/pool.c:atomic_pool_expand",
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/relay.c:relay_create_buf",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "kernel/watch_queue.c:watch_queue_set_size",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/slab_common.c:kmalloc_order",
        "mm/memory.c:__pmd_alloc",
        "mm/page_alloc.c:alloc_pages_exact",
        "mm/page_alloc.c:get_zeroed_page",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:alloc_zspage",
        "mm/balloon_compaction.c:balloon_page_alloc",
        "mm/secretmem.c:secretmem_fault",
        "fs/pipe.c:pipe_write",
        "fs/squashfs/block.c:squashfs_bio_read",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "security/selinux/status.c:selinux_kernel_status_page",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:bio_copy_user_iov",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/iov_iter.c:push_pipe",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf",
        "drivers/block/loop.c:lo_read_transfer",
        "drivers/block/loop.c:lo_write_transfer",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/scsi/sg.c:sg_build_indirect",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/md/dm-kcopyd.c:alloc_pl",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "net/core/skbuff.c:alloc_skb_with_frags",
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
      "addr": 18446744071582161008,
      "name": "alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
struct page * alloc_pages(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582616672,
      "name": "alloc_pages",
      "external": true,
      "loc": "mm/mempolicy.c:2254",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "init/do_mounts.c:do_mount_root",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/power/snapshot.c:alloc_image_page",
        "kernel/dma/pool.c:atomic_pool_expand",
        "kernel/dma/pool.c:atomic_pool_expand",
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "kernel/watch_queue.c:watch_queue_set_size",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/slab_common.c:kmalloc_order",
        "mm/memory.c:__pmd_alloc",
        "mm/vmalloc.c:vm_area_alloc_pages",
        "mm/page_alloc.c:alloc_pages_exact",
        "mm/page_alloc.c:get_zeroed_page",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/mempolicy.c:folio_alloc",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:alloc_zspage",
        "mm/balloon_compaction.c:balloon_page_alloc",
        "mm/secretmem.c:secretmem_fault",
        "fs/pipe.c:pipe_write",
        "fs/squashfs/block.c:squashfs_bio_read",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "security/selinux/status.c:selinux_kernel_status_page",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:bio_copy_user_iov",
        "io_uring/io_uring.c:io_add_buffers",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/iov_iter.c:push_pipe",
        "lib/stackdepot.c:__stack_depot_save",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_alloc_by_type",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/scsi/sg.c:sg_build_indirect",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/md/dm-kcopyd.c:alloc_pl",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "net/core/sock.c:skb_page_frag_refill",
        "net/core/sock.c:skb_page_frag_refill",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data",
        "net/bpf/test_run.c:bpf_prog_test_run_xdp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582616672,
      "name": "alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
struct page * alloc_pages(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583140560,
      "name": "alloc_pages",
      "external": true,
      "loc": "mm/mempolicy.c:2269",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "init/do_mounts.c:do_mount_root",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/platform/efi/memmap.c:efi_memmap_alloc",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:preallocate_image_memory",
        "kernel/dma/pool.c:atomic_pool_expand",
        "kernel/dma/pool.c:atomic_pool_expand",
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "kernel/watch_queue.c:watch_queue_set_size",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/memory.c:__pmd_alloc",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/page_alloc.c:alloc_pages_exact",
        "mm/page_alloc.c:get_zeroed_page",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/mempolicy.c:folio_alloc",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/migrate_device.c:migrate_device_coherent_page",
        "mm/huge_memory.c:mm_get_huge_zero_page",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:alloc_zspage",
        "mm/balloon_compaction.c:balloon_page_alloc",
        "mm/secretmem.c:secretmem_fault",
        "fs/pipe.c:pipe_write",
        "fs/squashfs/block.c:squashfs_bio_read",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "security/selinux/status.c:selinux_kernel_status_page",
        "block/blk-map.c:blk_rq_map_kern",
        "block/blk-map.c:bio_copy_user_iov",
        "io_uring/kbuf.c:io_add_buffers",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/iov_iter.c:append_pipe",
        "lib/stackdepot.c:__stack_depot_save",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_alloc_by_type",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/scsi/sg.c:sg_build_indirect",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "net/core/sock.c:skb_page_frag_refill",
        "net/core/sock.c:skb_page_frag_refill",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data",
        "net/bpf/test_run.c:bpf_prog_test_run_xdp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583140560,
      "name": "alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
struct page * alloc_pages(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583350688,
      "name": "alloc_pages",
      "external": true,
      "loc": "mm/mempolicy.c:2280",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_root_generic",
        "init/do_mounts.c:do_mount_root",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/platform/efi/memmap.c:efi_memmap_alloc",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:preallocate_image_memory",
        "kernel/dma/pool.c:atomic_pool_expand",
        "kernel/dma/pool.c:atomic_pool_expand",
        "kernel/module/decompress.c:module_zstd_decompress",
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/events/uprobes.c:__create_xol_area",
        "kernel/watch_queue.c:watch_queue_set_size",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/memory.c:__pmd_alloc",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/page_alloc.c:alloc_pages_exact",
        "mm/page_alloc.c:get_zeroed_page",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/mempolicy.c:folio_alloc",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/migrate_device.c:migrate_device_coherent_page",
        "mm/huge_memory.c:mm_get_huge_zero_page",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:alloc_zspage",
        "mm/balloon_compaction.c:balloon_page_alloc",
        "mm/secretmem.c:secretmem_fault",
        "fs/pipe.c:pipe_write",
        "fs/squashfs/block.c:squashfs_bio_read",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "security/selinux/status.c:selinux_kernel_status_page",
        "block/blk-map.c:bio_copy_kern",
        "block/blk-map.c:bio_copy_user_iov",
        "io_uring/kbuf.c:io_add_buffers",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/stackdepot.c:__stack_depot_save",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_alloc_by_type",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/scsi/sg.c:sg_build_indirect",
        "drivers/net/virtio_net.c:add_recvbuf_big",
        "drivers/net/virtio_net.c:add_recvbuf_big",
        "drivers/net/virtio_net.c:xdp_linearize_page",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_create",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "net/core/sock.c:skb_page_frag_refill",
        "net/core/sock.c:skb_page_frag_refill",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data",
        "net/bpf/test_run.c:bpf_prog_test_run_xdp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583350688,
      "name": "alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * alloc_pages(gfp_t gfp, unsigned int order)
```

```json
{
  "name": "alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583588046,
      "name": "alloc_pages",
      "external": true,
      "loc": "mm/mempolicy.c:2193",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:folio_alloc"
      ],
      "caller_func": [
        "init/do_mounts.c:mount_root_generic",
        "init/do_mounts.c:do_mount_root",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit",
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/platform/efi/memmap.c:efi_memmap_alloc",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:preallocate_image_memory",
        "kernel/dma/swiotlb.c:swiotlb_alloc_pool",
        "kernel/dma/pool.c:atomic_pool_expand",
        "kernel/dma/pool.c:atomic_pool_expand",
        "kernel/module/decompress.c:module_zstd_decompress",
        "kernel/time/namespace.c:copy_time_ns",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/trace/trace.c:tracing_splice_read_pipe",
        "kernel/trace/trace.c:allocate_cmdlines_buffer",
        "kernel/events/uprobes.c:__create_xol_area",
        "kernel/watch_queue.c:watch_queue_set_size",
        "mm/mempool.c:mempool_alloc_pages",
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/page_alloc.c:alloc_pages_exact",
        "mm/page_alloc.c:get_zeroed_page",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/hugetlb_vmemmap.c:vmemmap_split_pmd",
        "mm/migrate_device.c:migrate_device_coherent_page",
        "mm/huge_memory.c:mm_get_huge_zero_page",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "mm/zbud.c:zbud_alloc",
        "mm/zsmalloc.c:alloc_zspage",
        "mm/balloon_compaction.c:balloon_page_alloc",
        "fs/pipe.c:pipe_write",
        "fs/coredump.c:dump_user_range",
        "fs/squashfs/block.c:squashfs_bio_read",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/dev.c:fuse_copy_fill",
        "fs/fuse/dir.c:fuse_get_link",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "security/selinux/status.c:selinux_kernel_status_page",
        "block/blk-map.c:bio_copy_kern",
        "block/blk-map.c:bio_copy_user_iov",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/stackdepot.c:stack_depot_save_flags",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_alloc_by_type",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/iommu/intel/svm.c:intel_svm_enable_prq",
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/scsi/sg.c:sg_build_indirect",
        "drivers/net/virtio_net.c:add_recvbuf_big",
        "drivers/net/virtio_net.c:add_recvbuf_big",
        "drivers/net/virtio_net.c:xdp_linearize_page",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_resize",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/md/dm-kcopyd.c:alloc_pl",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "net/core/sock.c:skb_page_frag_refill",
        "net/core/sock.c:skb_page_frag_refill",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:alloc_skb_with_frags",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data",
        "net/bpf/test_run.c:bpf_prog_test_run_xdp",
        "net/xdp/xsk.c:xsk_build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583587792,
      "name": "alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
  "name": "alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510805768,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490375456,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:kvm_vcpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490418232,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "virt/kvm/coalesced_mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/coalesced_mmio.c:kvm_coalesced_mmio_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490454928,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "virt/kvm/arm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/mmu.c:__create_hyp_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510898128,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/dma/remap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/remap.c:dma_atomic_pool_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491501448,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491776564,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491891604,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492414444,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__create_xol_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492441600,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492470276,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492666348,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492751272,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:do_fault",
        "mm/memory.c:__do_fault",
        "mm/memory.c:__pte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492843172,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492871896,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_pages_exact",
        "mm/page_alloc.c:get_zeroed_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492943640,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493062552,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493133184,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493223448,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493248756,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493260988,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493266088,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493368308,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494842456,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494882552,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494901508,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494918012,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446603336494960276,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495110868,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_alloc_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495313536,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "security/selinux/ss/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495781248,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496106940,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496109340,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:push_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496398340,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_allocate_pending_table",
        "drivers/irqchip/irq-gic-v3-its.c:its_allocate_prop_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497161240,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498051928,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/dma/mv_xor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mv_xor.c:mv_xor_channel_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498193280,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498210640,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498752328,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498784964,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446603336498794332,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446603336498796148,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498800996,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498932920,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499121948,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499212152,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499225420,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499655304,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500145596,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501074540,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446603336501137392,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446603336501209468,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:alloc_pl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501545820,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511285112,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501872392,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501910136,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446603336502205272,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302367884,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282725352,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/powerpc/mm/pgtable-frag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/pgtable-frag.c:pte_fragment_alloc",
        "arch/powerpc/mm/pgtable-frag.c:pte_fragment_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282757612,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/powerpc/mm/book3s64/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/pgtable.c:pmd_fragment_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284461108,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284824656,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284973896,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285680864,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__create_xol_area"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285715232,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285753276,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285991844,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286231816,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286245084,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__get_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286357072,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286497104,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286609864,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286738256,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286771116,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286775972,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286792028,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286914880,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288692820,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288749380,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288765776,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288794224,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 13835058055288837464,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289014244,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_alloc_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289303456,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "security/selinux/ss/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289957708,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290354556,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290358120,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:push_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291433352,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291915808,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291950220,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291977500,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 13835058055291989100,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 13835058055291991360,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291997772,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292070640,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292309908,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292425776,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292992856,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_build_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294579356,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 13835058055294644540,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 13835058055294733672,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:alloc_pl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295281040,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295323692,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 13835058055295702984,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604581856,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579032860,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604706686,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579381809,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579395141,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pte_alloc_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604743830,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579915603,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:alloc_image_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580227467,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580468848,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580562436,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581025045,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__create_xol_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581047163,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581073397,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581233509,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314440,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581408240,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581418037,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__get_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581488981,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582001,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652768,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581736215,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581756789,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581766397,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581770373,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581859010,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583101246,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583137472,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583152768,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583173355,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071583205547,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583331468,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_alloc_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583511048,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "security/selinux/ss/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583928274,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584198773,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584202261,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:push_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584765623,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585298700,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585310752,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585690313,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585716277,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585737151,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585750181,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071585758999,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071585760536,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585765347,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585830139,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585874920,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585888597,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585902242,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586053164,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586134020,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586141371,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586441646,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586456636,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_init_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586785205,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587480375,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071587538929,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071587599631,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:alloc_pl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587808668,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605047657,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:__efi_memmap_alloc_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587966199,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588001169,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071588272765,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
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
  "name": "alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604573533,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578965659,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604674655,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310106,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324869,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pte_alloc_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604711447,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579854835,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:alloc_image_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580174955,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580415824,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580509140,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580971141,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__create_xol_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580994443,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581020581,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581180181,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581258006,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581350752,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581360549,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__get_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581431237,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581523554,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581592992,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581674855,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581695413,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581705021,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581708997,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581796610,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583038398,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583074624,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583089920,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583110507,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071583142699,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583268572,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_alloc_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583448104,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "security/selinux/ss/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583865218,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584133989,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584137477,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:push_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584696407,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585251212,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585550009,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585575461,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585596335,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585609365,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071585618183,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071585619720,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585624531,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585689498,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585734611,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585748373,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585899116,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585978628,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586317902,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586332876,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_init_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586705870,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587248535,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071587307041,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071587367711,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:alloc_pl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587512092,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605012997,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:__efi_memmap_alloc_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587565347,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/hv/channel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/channel.c:vmbus_alloc_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587679303,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587714257,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071587985581,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
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
  "name": "alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604659680,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579032444,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604784253,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579381729,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579395061,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pte_alloc_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604821397,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579908099,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:alloc_image_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580218939,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580460096,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580553684,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581016245,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__create_xol_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581038363,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581064597,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581224709,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305640,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581399440,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581409237,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__get_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581480293,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581573313,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581644080,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581727527,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581748101,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581757709,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581761685,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581850322,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583089854,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583121504,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583136800,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583157387,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071583189579,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583315244,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_alloc_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583494824,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "security/selinux/ss/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583912034,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584182533,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584186021,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:push_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584767047,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585487068,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585499120,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585879561,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585905317,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585926191,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585939221,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071585948039,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071585949576,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585954387,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586019354,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586064483,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586078245,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586091890,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586239308,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586320100,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586327051,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586705726,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586982421,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587012510,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587805543,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071587864097,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071587924799,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:alloc_pl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588144764,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605134232,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:__efi_memmap_alloc_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588297975,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588332945,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071588604589,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
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
  "name": "alloc_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604659685,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579036012,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604796885,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390189,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579403573,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pte_alloc_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604834107,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579954163,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:alloc_image_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580271707,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580515760,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580610404,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_splice_read_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581077557,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__create_xol_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581099979,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581126149,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/mempool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempool.c:mempool_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581288693,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmalloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369640,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581463429,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581473333,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__get_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581545029,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638442,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581710464,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581795732,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581816337,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/zbud.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zbud.c:zbud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581821371,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581830565,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581919826,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583179070,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583218800,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583230480,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_get_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583251053,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071583283419,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583410268,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_alloc_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583591192,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "security/selinux/ss/status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/status.c:selinux_kernel_status_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584013330,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_kern",
        "block/bio.c:bio_copy_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584286869,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584290373,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:push_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584874567,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585591132,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585607152,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585988761,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586013301,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586034175,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586047173,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071586055815,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071586057336,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586062147,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586127306,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:alloc_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586172611,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586186533,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:intel_svm_enable_prq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586200498,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586348908,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_grow_paged_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586431553,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586438731,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect",
        "drivers/block/xen-blkfront.c:blkfront_setup_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586811710,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587089621,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587119678,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587933143,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071587979153,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071588040527,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:alloc_pl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588262260,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605161413,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:__efi_memmap_alloc_late"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588433143,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588468417,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
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
      "addr": 18446744071588742269,
      "name": "alloc_pages",
      "external": false,
      "loc": "include/linux/gfp.h:536",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data"
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
struct page * alloc_pages(gfp_t gfp, unsigned int order)
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
