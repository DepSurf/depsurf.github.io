# Function: <code>sg_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583014224,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:25",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_nents",
        "lib/scatterlist.c:sg_last",
        "lib/scatterlist.c:sg_alloc_table_from_pages"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-nommu.c:nommu_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "crypto/scatterwalk.c:scatterwalk_bytes_sglen",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/eseqiv.c:eseqiv_givencrypt",
        "crypto/eseqiv.c:eseqiv_givencrypt",
        "crypto/ahash.c:crypto_hash_walk_done",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "lib/swiotlb.c:swiotlb_sync_sg_for_device",
        "lib/swiotlb.c:swiotlb_sync_sg_for_cpu",
        "lib/swiotlb.c:swiotlb_map_sg_attrs",
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "lib/mpi/mpicoder.c:mpi_read_raw_from_sgl",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/iommu/iommu.c:default_iommu_map_sg",
        "drivers/iommu/amd_iommu.c:unmap_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:intel_map_sg",
        "drivers/iommu/intel-iommu.c:intel_map_sg",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_map",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583014224,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583307959,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:25",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_alloc_table_from_pages",
        "lib/scatterlist.c:sg_last",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-nommu.c:nommu_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "lib/swiotlb.c:swiotlb_sync_sg_for_device",
        "lib/swiotlb.c:swiotlb_sync_sg_for_cpu",
        "lib/swiotlb.c:swiotlb_map_sg_attrs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries",
        "drivers/iommu/iommu.c:default_iommu_map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:sg_num_pages",
        "drivers/iommu/intel-iommu.c:intel_map_sg",
        "drivers/iommu/intel-iommu.c:intel_map_sg",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_map",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583305104,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583427270,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:25",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_alloc_table_from_pages",
        "lib/scatterlist.c:sg_last",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-nommu.c:nommu_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/scompress.c:crypto_scomp_sg_free",
        "crypto/xts.c:pre_crypt",
        "crypto/xts.c:pre_crypt",
        "crypto/xts.c:post_crypt",
        "crypto/xts.c:post_crypt",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "lib/swiotlb.c:swiotlb_sync_sg_for_device",
        "lib/swiotlb.c:swiotlb_sync_sg_for_cpu",
        "lib/swiotlb.c:swiotlb_map_sg_attrs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries",
        "drivers/iommu/iommu.c:default_iommu_map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:sg_num_pages",
        "drivers/iommu/intel-iommu.c:intel_map_sg",
        "drivers/iommu/intel-iommu.c:intel_map_sg",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_map",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583424432,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583448477,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:25",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_alloc_table_from_pages",
        "lib/scatterlist.c:sg_last",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-nommu.c:nommu_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/xts.c:pre_crypt",
        "crypto/xts.c:pre_crypt",
        "crypto/xts.c:post_crypt",
        "crypto/xts.c:post_crypt",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "lib/swiotlb.c:swiotlb_sync_sg_for_device",
        "lib/swiotlb.c:swiotlb_sync_sg_for_cpu",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries",
        "drivers/iommu/iommu.c:default_iommu_map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:sg_num_pages",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/scsi_lib_dma.c:scsi_dma_map",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_qc_issue",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583445680,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583625813,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:25",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_last",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/x86/kernel/pci-nommu.c:nommu_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/xts.c:pre_crypt",
        "crypto/xts.c:pre_crypt",
        "crypto/xts.c:post_crypt",
        "crypto/xts.c:post_crypt",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "lib/swiotlb.c:swiotlb_sync_sg_for_device",
        "lib/swiotlb.c:swiotlb_sync_sg_for_cpu",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries",
        "drivers/iommu/iommu.c:default_iommu_map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:sg_num_pages",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/core.c:mmc_mrq_prep",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583625664,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583842418,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:25",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free_n_order",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg",
        "kernel/dma/swiotlb.c:swiotlb_sync_sg_for_device",
        "kernel/dma/swiotlb.c:swiotlb_sync_sg_for_cpu",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/xts.c:pre_crypt",
        "crypto/xts.c:pre_crypt",
        "crypto/xts.c:post_crypt",
        "crypto/xts.c:post_crypt",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries",
        "drivers/iommu/iommu.c:default_iommu_map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:sg_num_pages",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/core.c:mmc_mrq_prep",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583841776,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583926130,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:25",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free_n_order",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_cpu",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_device",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add",
        "drivers/virtio/virtio_ring.c:virtqueue_add",
        "drivers/virtio/virtio_ring.c:virtqueue_add",
        "drivers/virtio/virtio_ring.c:virtqueue_add",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries",
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:sg_num_pages",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/core.c:mmc_mrq_prep",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583925472,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584106213,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:23",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free_n_order",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_cpu",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_device",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries",
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:sg_num_pages",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/core.c:mmc_mrq_prep",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584105200,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584228981,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:23",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free_n_order",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_cpu",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_device",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries",
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:sg_num_pages",
        "drivers/iommu/intel-iommu.c:bounce_sync_sg_for_device",
        "drivers/iommu/intel-iommu.c:bounce_sync_sg_for_cpu",
        "drivers/iommu/intel-iommu.c:bounce_map_sg",
        "drivers/iommu/intel-iommu.c:bounce_unmap_sg",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/core.c:mmc_mrq_prep",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584228096,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584638502,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:23",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:__sg_alloc_table_from_pages",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:dma_map_sg_nonforce",
        "arch/x86/kernel/amd_gart_64.c:dma_map_sg_nonforce",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_cpu",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_device",
        "kernel/dma/virt.c:dma_virt_map_sg",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:__blk_rq_map_sg",
        "block/blk-merge.c:__blk_rq_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:blk_bvec_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries",
        "drivers/char/agp/intel-gtt.c:intel_gtt_map_memory",
        "drivers/iommu/iommu.c:__iommu_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/intel/iommu.c:bounce_sync_sg_for_device",
        "drivers/iommu/intel/iommu.c:bounce_sync_sg_for_cpu",
        "drivers/iommu/intel/iommu.c:bounce_map_sg",
        "drivers/iommu/intel/iommu.c:bounce_map_sg",
        "drivers/iommu/intel/iommu.c:bounce_map_sg",
        "drivers/iommu/intel/iommu.c:intel_map_sg",
        "drivers/iommu/intel/iommu.c:intel_map_sg",
        "drivers/iommu/intel/iommu.c:intel_unmap_sg",
        "drivers/iommu/intel/iommu.c:__domain_mapping",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/scsi_lib.c:scsi_init_io",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_fill_sg_dumb",
        "drivers/ata/libata-sff.c:__atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_submit_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/core.c:mmc_mrq_prep",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584634464,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584756247,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:23",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:__sg_alloc_table_from_pages",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:__dma_map_cont",
        "arch/x86/kernel/amd_gart_64.c:dma_map_sg_nonforce",
        "arch/x86/kernel/amd_gart_64.c:dma_map_sg_nonforce",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_cpu",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_device",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:__blk_rq_map_sg",
        "block/blk-merge.c:__blk_rq_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:blk_bvec_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries",
        "drivers/char/agp/intel-gtt.c:intel_gtt_map_memory",
        "drivers/iommu/iommu.c:__iommu_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg_swiotlb",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg_swiotlb",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release",
        "drivers/dma-buf/heaps/system_heap.c:dup_sg_table",
        "drivers/dma-buf/heaps/system_heap.c:dup_sg_table",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/scsi_lib.c:scsi_alloc_sgtables",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_fill_sg_dumb",
        "drivers/ata/libata-sff.c:__atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_submit_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/core.c:mmc_mrq_prep",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584753504,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584785879,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:23",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:__sg_alloc_table_from_pages",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:__dma_map_cont",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_cpu",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_device",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:__blk_rq_map_sg",
        "block/blk-merge.c:__blk_rq_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg",
        "drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries",
        "drivers/iommu/iommu.c:__iommu_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_attach",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_attach",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/scsi_lib.c:scsi_alloc_sgtables",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:__atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_submit_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/core.c:mmc_mrq_prep",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584781952,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585216615,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:23",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_alloc_append_table_from_pages",
        "lib/scatterlist.c:sg_last",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:__dma_map_cont",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_cpu",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_device",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:__blk_rq_map_sg",
        "block/blk-merge.c:__blk_rq_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg",
        "drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries",
        "drivers/iommu/iommu.c:__iommu_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_attach",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_attach",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/scsi_lib.c:scsi_alloc_sgtables",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_submit_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/core.c:mmc_mrq_prep",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585212416,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586049670,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:23",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:__sg_page_iter_dma_next",
        "lib/scatterlist.c:__sg_page_iter_next",
        "lib/scatterlist.c:sgl_free",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_alloc_append_table_from_pages",
        "lib/scatterlist.c:sg_last",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:__dma_map_cont",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_cpu",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_device",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:__blk_rq_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg",
        "drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries",
        "drivers/iommu/iommu.c:__iommu_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_attach",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_attach",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/scsi_lib.c:scsi_alloc_sgtables",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:__atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_submit_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/core.c:mmc_mrq_prep",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586049168,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587033158,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:23",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:__sg_page_iter_dma_next",
        "lib/scatterlist.c:__sg_page_iter_next",
        "lib/scatterlist.c:sgl_free",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_alloc_append_table_from_pages",
        "lib/scatterlist.c:sg_last",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:__dma_map_cont",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_cpu",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_device",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:__blk_rq_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "drivers/pci/p2pdma.c:pci_p2pmem_free_sgl",
        "drivers/dma/hsu/hsu.c:hsu_dma_prep_slave_sg",
        "drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg",
        "drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_gmch_gtt_insert_sg_entries",
        "drivers/iommu/iommu.c:__iommu_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_attach",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_attach",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/scsi_lib.c:scsi_alloc_sgtables",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:__atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/spi/spi.c:spi_map_buf_attrs",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_submit_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/core.c:mmc_mrq_prep",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587032624,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587288310,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:25",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:__sg_page_iter_dma_next",
        "lib/scatterlist.c:__sg_page_iter_next",
        "lib/scatterlist.c:sgl_free",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_alloc_append_table_from_pages",
        "lib/scatterlist.c:sg_last",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:__dma_map_cont",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_cpu",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_device",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:__blk_rq_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "drivers/pci/p2pdma.c:pci_p2pmem_free_sgl",
        "drivers/dma/hsu/hsu.c:hsu_dma_prep_slave_sg",
        "drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg",
        "drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_gmch_gtt_insert_sg_entries",
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_attach",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_attach",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/scsi_lib.c:scsi_alloc_sgtables",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:__atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/spi/spi.c:spi_map_buf_attrs",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_submit_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/core.c:mmc_mrq_prep",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587287776,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587574182,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:25",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:__sg_page_iter_dma_next",
        "lib/scatterlist.c:__sg_page_iter_next",
        "lib/scatterlist.c:sgl_free",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_alloc_append_table_from_pages",
        "lib/scatterlist.c:sg_last",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:__dma_map_cont",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_cpu",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_device",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/scatterwalk.c:scatterwalk_ffwd",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:__blk_rq_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "drivers/pci/p2pdma.c:pci_p2pmem_free_sgl",
        "drivers/dma/hsu/hsu.c:hsu_dma_prep_slave_sg",
        "drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg",
        "drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_gmch_gtt_insert_sg_entries",
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_attach",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_attach",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/scsi_lib.c:scsi_alloc_sgtables",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:__atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/gpu/drm/drm_prime.c:drm_prime_get_contiguous_size",
        "drivers/spi/spi.c:spi_map_buf_attrs",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_submit_urb",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/core.c:mmc_mrq_prep",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587573648,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496104208,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:23",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free_n_order",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_cpu",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_device",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_device",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "lib/sg_split.c:sg_split",
        "lib/sg_split.c:sg_split",
        "lib/sg_split.c:sg_split",
        "lib/sg_split.c:sg_calculate_split",
        "drivers/dma/amba-pl08x.c:pl08x_prep_slave_sg",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_slave_sg",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_prep_slave_sg",
        "drivers/dma/mxs-dma.c:mxs_dma_prep_slave_sg",
        "drivers/dma/mxs-dma.c:mxs_dma_prep_slave_sg",
        "drivers/dma/ipu/ipu_idmac.c:ipu_gc_tasklet",
        "drivers/dma/ipu/ipu_idmac.c:ipu_gc_tasklet",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/ata/libahci.c:ahci_qc_prep",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/core.c:mmc_mrq_prep",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/block.c:mmc_blk_data_prep",
        "drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_start",
        "drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_validate_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496103144,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229428948,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:23",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free_n_order",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/arm/mm/dma-mapping.c:arm_iommu_sync_sg_for_device",
        "arch/arm/mm/dma-mapping.c:arm_iommu_sync_sg_for_cpu",
        "arch/arm/mm/dma-mapping.c:arm_iommu_unmap_sg",
        "arch/arm/mm/dma-mapping.c:arm_coherent_iommu_unmap_sg",
        "arch/arm/mm/dma-mapping.c:__iommu_map_sg",
        "arch/arm/mm/dma-mapping.c:__iommu_map_sg",
        "arch/arm/mm/dma-mapping.c:__iommu_map_sg",
        "arch/arm/mm/dma-mapping.c:__map_sg_chunk",
        "arch/arm/mm/dma-mapping.c:arm_dma_sync_sg_for_device",
        "arch/arm/mm/dma-mapping.c:arm_dma_sync_sg_for_cpu",
        "arch/arm/mm/dma-mapping.c:arm_dma_unmap_sg",
        "arch/arm/mm/dma-mapping.c:arm_dma_map_sg",
        "arch/arm/mm/dma-mapping.c:arm_dma_map_sg",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "lib/sg_split.c:sg_split",
        "lib/sg_split.c:sg_split",
        "lib/sg_split.c:sg_calculate_split",
        "lib/sg_split.c:sg_calculate_split",
        "drivers/dma/amba-pl08x.c:pl08x_prep_slave_sg",
        "drivers/dma/mxs-dma.c:mxs_dma_prep_slave_sg",
        "drivers/dma/mxs-dma.c:mxs_dma_prep_slave_sg",
        "drivers/dma/ipu/ipu_idmac.c:ipu_gc_tasklet",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_interrupt",
        "drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_prep_slave_sg",
        "drivers/dma/ti/edma.c:edma_prep_slave_sg",
        "drivers/dma/ti/omap-dma.c:omap_dma_prep_slave_sg",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/ata/libahci.c:ahci_qc_prep",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_submit_common",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/core.c:mmc_mrq_prep",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/block.c:mmc_blk_data_prep",
        "drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_start",
        "drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_validate_data",
        "drivers/mmc/host/sdhci.c:sdhci_finish_data",
        "drivers/mmc/host/sdhci.c:sdhci_finish_data",
        "drivers/mmc/host/sdhci.c:sdhci_prepare_data",
        "drivers/mmc/host/sdhci.c:sdhci_prepare_data",
        "drivers/mmc/host/cqhci.c:cqhci_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229428008,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290350860,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:23",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free_n_order",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_last",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/powerpc/kernel/iommu.c:ppc_iommu_unmap_sg",
        "arch/powerpc/kernel/iommu.c:ppc_iommu_map_sg",
        "arch/powerpc/kernel/iommu.c:ppc_iommu_map_sg",
        "arch/powerpc/kernel/iommu.c:ppc_iommu_map_sg",
        "arch/powerpc/kernel/iommu.c:ppc_iommu_map_sg",
        "arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_unmap_sg",
        "arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_map_sg",
        "arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_map_sg",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_cpu",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_device",
        "kernel/dma/virt.c:dma_virt_map_sg",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/core.c:mmc_mrq_prep",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290349152,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275170638,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:23",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free_n_order",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_cpu",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_device",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:td_submit_urb",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/core.c:mmc_mrq_prep",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended",
        "drivers/mmc/core/block.c:mmc_blk_data_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275169540,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584197717,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:23",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free_n_order",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_cpu",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_device",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries",
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:sg_num_pages",
        "drivers/iommu/intel-iommu.c:bounce_sync_sg_for_device",
        "drivers/iommu/intel-iommu.c:bounce_sync_sg_for_cpu",
        "drivers/iommu/intel-iommu.c:bounce_map_sg",
        "drivers/iommu/intel-iommu.c:bounce_unmap_sg",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/core.c:mmc_mrq_prep",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584196832,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584132933,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:23",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free_n_order",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_cpu",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_device",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries",
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:sg_num_pages",
        "drivers/iommu/intel-iommu.c:bounce_sync_sg_for_device",
        "drivers/iommu/intel-iommu.c:bounce_sync_sg_for_cpu",
        "drivers/iommu/intel-iommu.c:bounce_map_sg",
        "drivers/iommu/intel-iommu.c:bounce_unmap_sg",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/storvsc_drv.c:storvsc_queuecommand",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/nvme/host/pci.c:nvme_map_data",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132048,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584181477,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:23",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free_n_order",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_cpu",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_device",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries",
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:sg_num_pages",
        "drivers/iommu/intel-iommu.c:bounce_sync_sg_for_device",
        "drivers/iommu/intel-iommu.c:bounce_sync_sg_for_cpu",
        "drivers/iommu/intel-iommu.c:bounce_map_sg",
        "drivers/iommu/intel-iommu.c:bounce_unmap_sg",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/core.c:mmc_mrq_prep",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584180592,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct scatterlist * sg_next(struct scatterlist * sg)
```

```json
{
  "name": "sg_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584285813,
      "name": "sg_next",
      "external": true,
      "loc": "lib/scatterlist.c:23",
      "file": "lib/scatterlist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sgl_free_n_order",
        "lib/scatterlist.c:sgl_alloc_order",
        "lib/scatterlist.c:sg_nents"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_map_sg",
        "arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg",
        "kernel/dma/direct.c:dma_direct_map_sg",
        "kernel/dma/direct.c:dma_direct_unmap_sg",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_cpu",
        "kernel/dma/direct.c:dma_direct_sync_sg_for_device",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/ablkcipher.c:ablkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_aead_common",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/gcm.c:crypto_gcm_decrypt",
        "crypto/gcm.c:gcm_encrypt_continue",
        "block/blk-merge.c:blk_rq_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-merge.c:__blk_bios_map_sg",
        "block/blk-integrity.c:blk_rq_map_integrity_sg",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries",
        "drivers/char/agp/intel-gtt.c:intel_gtt_insert_sg_entries",
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:sg_num_pages",
        "drivers/iommu/intel-iommu.c:bounce_sync_sg_for_device",
        "drivers/iommu/intel-iommu.c:bounce_sync_sg_for_cpu",
        "drivers/iommu/intel-iommu.c:bounce_map_sg",
        "drivers/iommu/intel-iommu.c:bounce_unmap_sg",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/iommu/intel-iommu.c:__domain_mapping",
        "drivers/base/devcoredump.c:devcd_free_sgtable",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/sr.c:sr_init_command",
        "drivers/ata/libata-core.c:ata_exec_internal_sg",
        "drivers/ata/libata-sff.c:ata_bmdma_dumb_qc_prep",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_prep",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/usb/core/urb.c:usb_submit_urb",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/host/ehci-hcd.c:qh_urb_transaction",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/mmc/core/core.c:mmc_mrq_prep",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584284928,
      "name": "sg_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
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
