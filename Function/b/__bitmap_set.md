# Function: <code>__bitmap_set</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583441664,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:254",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:sys_ioperm",
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/cma.c:cma_alloc",
        "lib/iommu-helper.c:iommu_area_alloc",
        "drivers/pwm/core.c:pwmchip_add_with_polarity",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583441664,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583621600,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:256",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:sys_ioperm",
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/cma.c:cma_alloc",
        "lib/bitmap.c:__bitmap_parselist",
        "lib/iommu-helper.c:iommu_area_alloc",
        "drivers/pwm/core.c:pwmchip_add_with_polarity",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621600,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583837952,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:253",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/cma.c:cma_alloc",
        "lib/bitmap.c:__bitmap_parselist",
        "lib/iommu-helper.c:iommu_area_alloc",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583837952,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583921584,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:250",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/cma.c:cma_alloc",
        "lib/bitmap.c:__bitmap_parselist",
        "lib/iommu-helper.c:iommu_area_alloc",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921584,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584101376,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:250",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/sparse.c:subsection_mask_set",
        "mm/cma.c:cma_alloc",
        "lib/bitmap.c:bitmap_parselist",
        "lib/iommu-helper.c:iommu_area_alloc",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584101376,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584224160,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:270",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/sparse.c:subsection_mask_set",
        "mm/cma.c:cma_alloc",
        "lib/bitmap.c:bitmap_parselist",
        "lib/iommu-helper.c:iommu_area_alloc",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584224160,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584630208,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:349",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:alloc_descs",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/sparse.c:subsection_mask_set",
        "lib/bitmap.c:bitmap_parselist",
        "lib/iommu-helper.c:iommu_area_alloc",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/pwm/core.c:pwmchip_add_with_polarity",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/block/xen-blkfront.c:xlbd_reserve_minors",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk",
        "drivers/vfio/vfio_iommu_type1.c:update_user_bitmap",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584630208,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584749264,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:349",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:alloc_descs",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/sparse.c:subsection_mask_set",
        "fs/file.c:__close_range",
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate",
        "lib/bitmap.c:bitmap_parselist",
        "lib/iommu-helper.c:iommu_area_alloc",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/pwm/core.c:pwmchip_add_with_polarity",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/block/xen-blkfront.c:xlbd_reserve_minors",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk",
        "drivers/vfio/vfio_iommu_type1.c:update_user_bitmap",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_populate_bitmap_full",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584749264,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777600,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:351",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:alloc_descs",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/sparse.c:subsection_mask_set",
        "fs/file.c:__close_range",
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate",
        "lib/bitmap.c:bitmap_parselist",
        "lib/iommu-helper.c:iommu_area_alloc",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/pwm/core.c:pwmchip_add",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/block/xen-blkfront.c:xlbd_reserve_minors",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:update_user_bitmap",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777600,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585207616,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:351",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:alloc_descs",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/sparse.c:subsection_mask_set",
        "fs/file.c:__close_range",
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate",
        "lib/bitmap.c:bitmap_parselist",
        "lib/iommu-helper.c:iommu_area_alloc",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/pwm/core.c:pwmchip_add",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/block/xen-blkfront.c:xlbd_reserve_minors",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:update_user_bitmap",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585207616,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586043504,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:351",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/sparse.c:subsection_mask_set",
        "fs/file.c:__close_range",
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate",
        "lib/bitmap.c:bitmap_parselist",
        "lib/iommu-helper.c:iommu_area_alloc",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/pwm/core.c:pwmchip_add",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/xen/grant-table.c:gnttab_set_free",
        "drivers/block/xen-blkfront.c:xlbd_reserve_minors",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:update_user_bitmap",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043504,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587026304,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:362",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/sparse.c:subsection_mask_set",
        "fs/file.c:__close_range",
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate",
        "lib/bitmap.c:bitmap_parselist",
        "lib/iommu-helper.c:iommu_area_alloc",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/pwm/core.c:pwmchip_add",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/xen/grant-table.c:gnttab_set_free",
        "drivers/block/xen-blkfront.c:xlbd_reserve_minors",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587026304,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587281296,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:362",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/sparse.c:subsection_mask_set",
        "fs/file.c:__close_range",
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate",
        "lib/bitmap.c:bitmap_parselist",
        "lib/iommu-helper.c:iommu_area_alloc",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/pwm/core.c:pwmchip_add",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/xen/grant-table.c:gnttab_set_free",
        "drivers/block/xen-blkfront.c:xlbd_reserve_minors",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587281296,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587570032,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:351",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/sparse.c:subsection_mask_set",
        "fs/file.c:__close_range",
        "fs/iomap/buffered-io.c:ifs_alloc",
        "fs/iomap/buffered-io.c:ifs_alloc",
        "fs/iomap/buffered-io.c:ifs_set_range_dirty",
        "fs/iomap/buffered-io.c:ifs_set_range_uptodate",
        "lib/bitmap-str.c:bitmap_parselist",
        "lib/iommu-helper.c:iommu_area_alloc",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc",
        "drivers/xen/grant-table.c:gnttab_set_free",
        "drivers/iommu/intel/irq_remapping.c:alloc_irte",
        "drivers/iommu/iommufd/iova_bitmap.c:iova_bitmap_set",
        "drivers/block/xen-blkfront.c:xlbd_reserve_minors",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587570032,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496097912,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:270",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/sparse.c:subsection_mask_set",
        "mm/cma.c:cma_alloc",
        "lib/bitmap.c:bitmap_parselist",
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/pci/controller/pci-aardvark.c:advk_msi_irq_domain_alloc",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_irq_domain_alloc",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_irq_domain_alloc",
        "drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_write_ctrl_data",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496097912,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229424768,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:270",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/dma-mapping.c:arm_iommu_map_resource",
        "arch/arm/mm/dma-mapping.c:arm_iommu_map_resource",
        "arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_page",
        "arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_page",
        "arch/arm/mm/dma-mapping.c:__map_sg_chunk",
        "arch/arm/mm/dma-mapping.c:__map_sg_chunk",
        "arch/arm/mm/dma-mapping.c:__iommu_create_mapping",
        "arch/arm/mm/dma-mapping.c:__iommu_create_mapping",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/cma.c:cma_alloc",
        "lib/bitmap.c:bitmap_parselist",
        "drivers/irqchip/irq-alpine-msi.c:alpine_msix_middle_domain_alloc",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_msi_alloc",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/dma/ti/edma.c:edma_probe",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229424768,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290342288,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:270",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/slice.c:slice_range_to_mask",
        "arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_alloc_hwirqs",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/sparse.c:subsection_mask_set",
        "mm/cma.c:cma_alloc",
        "lib/bitmap.c:bitmap_parselist",
        "lib/iommu-helper.c:iommu_area_alloc",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290342288,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275166130,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:270",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/sparse.c:subsection_map_init",
        "mm/cma.c:cma_alloc",
        "lib/bitmap.c:bitmap_parselist",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275166130,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584192896,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:270",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/sparse.c:subsection_mask_set",
        "mm/cma.c:cma_alloc",
        "lib/bitmap.c:bitmap_parselist",
        "lib/iommu-helper.c:iommu_area_alloc",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584192896,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584128112,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:270",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/sparse.c:subsection_mask_set",
        "mm/cma.c:cma_alloc",
        "lib/bitmap.c:bitmap_parselist",
        "lib/iommu-helper.c:iommu_area_alloc",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/pci/pci.c:pci_add_dma_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584128112,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584176656,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:270",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/sparse.c:subsection_mask_set",
        "mm/cma.c:cma_alloc",
        "lib/bitmap.c:bitmap_parselist",
        "lib/iommu-helper.c:iommu_area_alloc",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584176656,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584280992,
      "name": "__bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:270",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/sparse.c:subsection_mask_set",
        "mm/cma.c:cma_alloc",
        "lib/bitmap.c:bitmap_parselist",
        "lib/iommu-helper.c:iommu_area_alloc",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/pci/pci.c:pci_add_dma_alias",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584280992,
      "name": "__bitmap_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void __bitmap_set(long unsigned int * map, unsigned int start, int len)
```
</details>
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
