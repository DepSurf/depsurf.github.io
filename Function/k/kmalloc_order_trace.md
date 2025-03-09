# Function: <code>kmalloc_order_trace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580624800,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:1016",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:trace_init",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "fs/xattr.c:listxattr",
        "fs/xattr.c:getxattr",
        "crypto/lzo.c:lzo_init",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/base/regmap/regcache-lzo.c:regcache_lzo_init",
        "drivers/block/xen-blkfront.c:blkfront_probe",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open",
        "net/ipv4/route.c:update_or_create_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580624800,
      "name": "kmalloc_order_trace",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580729872,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:1024",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "fs/xattr.c:listxattr",
        "fs/xattr.c:getxattr",
        "fs/squashfs/file.c:squashfs_readpage",
        "crypto/lzo.c:lzo_init",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/base/power/clock_ops.c:of_pm_clk_add_clks",
        "drivers/base/regmap/regcache-lzo.c:regcache_lzo_init",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open",
        "net/ipv4/route.c:update_or_create_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580729872,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580795664,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:1053",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "fs/xattr.c:listxattr",
        "fs/xattr.c:getxattr",
        "fs/squashfs/file.c:squashfs_readpage",
        "crypto/lzo.c:lzo_alloc_ctx",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/base/power/clock_ops.c:of_pm_clk_add_clks",
        "drivers/base/regmap/regcache-lzo.c:regcache_lzo_init",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open",
        "net/ipv4/route.c:update_or_create_fnhe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580795664,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580836400,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:1122",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace.c:set_tracer_flag",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "fs/squashfs/file.c:squashfs_readpage",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open",
        "net/ipv4/route.c:update_or_create_fnhe",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580836400,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580927088,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:1131",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:arch_xen_balloon_init",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace.c:set_tracer_flag",
        "mm/swapfile.c:SYSC_swapon",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "fs/squashfs/file.c:squashfs_readpage",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/ipv6/route.c:rt6_insert_exception",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580927088,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581062608,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:1192",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "arch/x86/xen/enlighten.c:arch_xen_balloon_init",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace.c:set_tracer_flag",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "fs/squashfs/file.c:squashfs_readpage",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/ipv6/route.c:rt6_insert_exception",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581062608,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581140416,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:1239",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "kernel/workqueue.c:apply_wqattrs_prepare",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:instance_mkdir",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace.c:set_tracer_flag",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "fs/squashfs/file.c:squashfs_readpage",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/tty/tty_io.c:tty_write",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv6/route.c:rt6_insert_exception",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140416,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581205984,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:1267",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/tracepoint.c:allocate_probes",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:trace_array_create",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace.c:set_tracer_flag",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/char/hpet.c:hpet_alloc",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/usb/core/urb.c:usb_alloc_urb",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:rt6_insert_exception",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581205984,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581264784,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:1331",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/tracepoint.c:allocate_probes",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/usb/core/urb.c:usb_alloc_urb",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:rt6_insert_exception",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581264784,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581455200,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:1339",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/tracepoint.c:tracepoint_remove_func",
        "kernel/tracepoint.c:func_add",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_resize_saved_cmdlines",
        "kernel/watch_queue.c:watch_queue_set_filter",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/squashfs/file.c:empty_meta_index",
        "security/integrity/ima/ima_api.c:ima_alloc_init_template",
        "security/integrity/ima/ima_template.c:ima_restore_template_data",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "lib/decompress_bunzip2.c:start_bunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/tty/vt/vt.c:con_font_get",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/usb/core/urb.c:usb_alloc_urb",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/interconnect/core.c:path_find",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581455200,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581502720,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:851",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_open",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/audit_tree.c:alloc_chunk",
        "kernel/tracepoint.c:func_remove",
        "kernel/tracepoint.c:func_add",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_resize_saved_cmdlines",
        "kernel/watch_queue.c:watch_queue_set_filter",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key",
        "fs/squashfs/file.c:empty_meta_index",
        "security/integrity/ima/ima_api.c:ima_alloc_init_template",
        "security/integrity/ima/ima_policy.c:ima_alloc_rule_opt_list",
        "security/integrity/ima/ima_template.c:ima_restore_template_data",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "lib/decompress_bunzip2.c:start_bunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/tty/vt/vt.c:con_font_get",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/usb/core/urb.c:usb_alloc_urb",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/interconnect/core.c:path_find",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581502720,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581524928,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:937",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_open",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "fs/squashfs/file.c:empty_meta_index",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/tty/vt/vt.c:con_font_get",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581524928,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:971",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_open",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "fs/squashfs/file.c:empty_meta_index",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/tty/vt/vt.c:con_font_get",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592195276,
      "name": "kmalloc_order_trace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581786864,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:959",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "fs/squashfs/file.c:empty_meta_index",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "lib/xz/xz_dec_lzma2.c:xz_dec_microlzma_alloc",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo",
        "drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/tty/vt/vt.c:con_font_get",
        "drivers/scsi/sd.c:sd_read_cpr",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv6/route.c:rt6_insert_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593971833,
      "name": "kmalloc_order_trace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582172048,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
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
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492673112,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:1331",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "virt/kvm/kvm_main.c:kvm_io_bus_unregister_dev",
        "virt/kvm/kvm_main.c:kvm_io_bus_register_dev",
        "virt/kvm/arm/arm.c:kvm_arch_alloc_vm",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "security/integrity/ima/ima_api.c:ima_alloc_init_template",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_create_cb_chain",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/misc/vexpress-syscfg.c:vexpress_syscfg_regmap_init",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_init",
        "drivers/usb/core/urb.c:usb_alloc_urb",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:rt6_insert_exception",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492673112,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226508548,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:1331",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "arch/arm/mach-omap2/pm34xx.c:omap3_pm_init",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/module.c:mod_sysfs_setup",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "security/integrity/ima/ima_api.c:ima_alloc_init_template",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/bio-integrity.c:bio_integrity_alloc",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/dma/ti/edma.c:edma_prep_dma_cyclic",
        "drivers/dma/ti/edma.c:edma_prep_slave_sg",
        "drivers/dma/ti/omap-dma.c:omap_dma_prep_slave_sg",
        "drivers/reset/core.c:of_reset_control_array_get",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/iommu/omap-iommu.c:omap_iommu_attach_dev",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/usb/core/urb.c:usb_alloc_urb",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "sound/core/vmaster.c:_snd_ctl_add_slave",
        "sound/core/compress_offload.c:snd_compr_ioctl",
        "sound/soc/soc-dapm.c:snd_soc_dapm_dai_get_connected_widgets",
        "net/core/flow_offload.c:flow_rule_alloc",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226508548,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285992016,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:1331",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/vas.c:vas_probe",
        "kernel/tracepoint.c:allocate_probes",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/usb/core/urb.c:usb_alloc_urb",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285992016,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272677288,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:1331",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "security/integrity/ima/ima_api.c:ima_alloc_init_template",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/usb/core/urb.c:usb_alloc_urb",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:rt6_insert_exception",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272677288,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581233632,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:1331",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/tracepoint.c:allocate_probes",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/usb/core/urb.c:usb_alloc_urb",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:rt6_insert_exception",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581233632,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581180304,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:1331",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/tracepoint.c:allocate_probes",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/nvdimm/btt.c:btt_meta_init",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/net/vxlan.c:__vxlan_sock_add",
        "drivers/usb/core/urb.c:usb_alloc_urb",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:rt6_insert_exception",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581180304,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581224832,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:1331",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/tracepoint.c:allocate_probes",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/usb/core/urb.c:usb_alloc_urb",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:rt6_insert_exception",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581224832,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
```

```json
{
  "name": "kmalloc_order_trace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581288816,
      "name": "kmalloc_order_trace",
      "external": true,
      "loc": "mm/slab_common.c:1331",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:unpack_to_rootfs",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/tracepoint.c:allocate_probes",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracer_alloc_buffers",
        "kernel/trace/trace.c:tracing_buffers_open",
        "kernel/trace/trace.c:tracing_snapshot_open",
        "kernel/trace/trace.c:tracing_open_pipe",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/memory_hotplug.c:hotadd_new_pgdat",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger",
        "drivers/acpi/apei/ghes.c:ghes_probe",
        "drivers/clk/clk.c:clk_notifier_register",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/char/virtio_console.c:alloc_buf",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/ata/libata-core.c:ata_port_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_config",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/usb/core/urb.c:usb_alloc_urb",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_debug_open",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv6/route.c:rt6_insert_exception",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_inflate.c:__gunzip",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzo.c:unlzo",
        "lib/decompress_unlzo.c:unlzo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581288816,
      "name": "kmalloc_order_trace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void * kmalloc_order_trace(size_t size, gfp_t flags, unsigned int order)
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
