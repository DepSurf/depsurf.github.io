# Function: <code>bitmap_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583011088,
      "name": "bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:273",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:sys_ioperm",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/cma.c:cma_clear_bitmap",
        "lib/idr.c:idr_remove",
        "lib/idr.c:idr_get_empty_slot",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011088,
      "name": "bitmap_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583301616,
      "name": "bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:275",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:sys_ioperm",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/cma.c:cma_clear_bitmap",
        "lib/idr.c:idr_remove",
        "lib/idr.c:idr_get_empty_slot",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583301616,
      "name": "bitmap_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583420656,
      "name": "bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:275",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:sys_ioperm",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/cma.c:cma_clear_bitmap",
        "lib/idr.c:idr_remove",
        "lib/idr.c:idr_get_empty_slot",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583420656,
      "name": "bitmap_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579035718,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:327",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:sys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579276459,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:327",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579280093,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:327",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588277516,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:327",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580829050,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:327",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581246950,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:327",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_clear_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583576622,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:327",
      "file": "lib/iommu-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-common.c:iommu_tbl_range_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583704467,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:327",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585140282,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:327",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585181224,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:327",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_release_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585985912,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:327",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
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
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579043558,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:347",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:sys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295067,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:347",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298797,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:347",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579817303,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:347",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580916371,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:347",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581378534,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:347",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_clear_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583822446,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:347",
      "file": "lib/iommu-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-common.c:iommu_tbl_range_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583961827,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:347",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585567146,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:347",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585609464,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:347",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_release_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586429896,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:347",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
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
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579048430,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:378",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307114,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:378",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310794,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:378",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579851045,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:378",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581056152,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:378",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581528534,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:378",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_clear_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584156371,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:378",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585811256,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:378",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585862984,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:378",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_release_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586694200,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:378",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
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
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579053310,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213264,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579331677,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335399,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579898037,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581133944,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581614294,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_clear_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584244099,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585945208,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585994888,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_release_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586851224,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589431233,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_store"
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
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579061006,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218911,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579346941,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579350599,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579932853,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581196880,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581725894,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_clear_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584436384,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605010832,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586187144,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586239242,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_release_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587109531,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589326266,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589888972,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_store"
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
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579063134,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579221231,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579351277,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354935,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579982981,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581255331,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581799446,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_clear_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584573200,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585377959,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586335448,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586387466,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_release_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587309931,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589550522,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590114924,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_store"
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
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579071153,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:419",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245039,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:419",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579380717,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:419",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580030853,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:419",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581444324,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:419",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584631897,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:419",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585119032,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:419",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585247586,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:419",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:free_pwms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586086473,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:419",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587106280,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:419",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587159818,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:419",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_release_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587887034,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:419",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588166071,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:419",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589886410,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:419",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590554025,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:419",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:inet6_net_init"
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
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579075441,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579237882,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387485,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580014773,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581487222,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584750937,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585269448,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585405158,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:free_pwms"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586207159,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587191608,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587244090,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_release_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587948570,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588204183,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589925713,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590613817,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:inet6_net_init"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579082417,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239313,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390915,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580015221,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581511657,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584779113,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585152265,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585286300,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586081874,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587078888,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587138266,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_release_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587834678,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588087447,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589833555,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590539034,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:417",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:inet6_net_init"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579105377,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:423",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579276611,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:423",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579452211,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:423",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580147333,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:423",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581765323,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:423",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_depopulated",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585209865,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:423",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585595109,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:423",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_squash_marks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585742361,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:423",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586578987,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:423",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587650344,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:423",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587712906,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:423",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_release_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588435333,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:423",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588720407,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:423",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590596465,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:423",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591348604,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:423",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:inet6_net_init"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579135894,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:443",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330322,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:443",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579526435,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:443",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580292197,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:443",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581395343,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:443",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_pack_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582149499,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:443",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_depopulated",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586046105,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:443",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586761448,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:443",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586924537,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:443",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587839016,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:443",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588054860,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:443",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:get_free_entries_seq",
        "drivers/xen/grant-table.c:get_free_seq",
        "drivers/xen/grant-table.c:get_free_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588995035,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:443",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589043560,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:443",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_release_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589848021,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:443",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590138472,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:443",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592216449,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:443",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593020979,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:443",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:inet6_net_init"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579177206,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:469",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394770,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:469",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579628607,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:469",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:free_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580502469,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:469",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:irq_free_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581745484,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:469",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_pack_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582505874,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:469",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:iterate_mm_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582627867,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:469",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_depopulated",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587029109,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:469",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588012070,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:469",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588080521,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:469",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589181370,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:469",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589433724,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:469",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:get_free_entries_seq",
        "drivers/xen/grant-table.c:get_free_seq",
        "drivers/xen/grant-table.c:get_free_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590517307,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:469",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590572584,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:469",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_release_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591752424,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:469",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594046426,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:469",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594912207,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:469",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:inet6_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595915041,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:469",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_squash_marks"
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
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579180605,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:467",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406082,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:467",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579642623,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:467",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:free_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581905148,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:467",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_pack_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582727105,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:467",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582836731,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:467",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_depopulated",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583130841,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:467",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vb_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587284256,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:467",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588285331,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:467",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588355030,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:467",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589475433,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:467",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589732860,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:467",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:get_free_entries_seq",
        "drivers/xen/grant-table.c:get_free_seq",
        "drivers/xen/grant-table.c:get_free_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590841547,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:467",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590913656,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:467",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_release_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592175752,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:467",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593346712,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:467",
      "file": "drivers/firmware/efi/unaccepted_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/unaccepted_memory.c:accept_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594424778,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:467",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595303889,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:467",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:inet6_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596432831,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:467",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_squash_marks"
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
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579209821,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434370,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579676479,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:free_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582029343,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_pack_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582896673,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583011675,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_depopulated",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583313833,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vb_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584657164,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587632832,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "lib/bitmap-str.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap-str.c:bitmap_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588578243,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589010432,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589022002,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589782175,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_update_target_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590070828,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:get_free_entries_seq",
        "drivers/xen/grant-table.c:get_free_seq",
        "drivers/xen/grant-table.c:get_free_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590832647,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591184843,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591257400,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_release_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592916440,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593463767,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "drivers/ptp/ptp_chardev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_chardev.c:ptp_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594100578,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "drivers/firmware/efi/unaccepted_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/unaccepted_memory.c:accept_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595227025,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "net/ethtool/bitset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596145505,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:inet6_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597328191,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:444",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_squash_marks"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490352368,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/arm64/mm/context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/context.c:check_and_switch_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491168804,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492657988,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493263728,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_clear_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496428108,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/irqchip/irq-ls-scfg-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496744176,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/gpio/gpiolib-of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-of.c:of_gpiochip_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496806504,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497101452,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/pci/controller/pci-aardvark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-aardvark.c:advk_msi_irq_domain_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497124532,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/pci/controller/pci-xgene-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-xgene-msi.c:xgene_irq_domain_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497126800,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/pci/controller/pcie-iproc-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_irq_domain_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497652004,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499173172,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499235836,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_release_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500427144,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503221432,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503896180,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_store"
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
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224489164,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/arm/mm/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/dma-mapping.c:arm_iommu_unmap_resource",
        "arch/arm/mm/dma-mapping.c:arm_iommu_map_resource",
        "arch/arm/mm/dma-mapping.c:arm_iommu_unmap_page",
        "arch/arm/mm/dma-mapping.c:arm_coherent_iommu_unmap_page",
        "arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_page",
        "arch/arm/mm/dma-mapping.c:__map_sg_chunk",
        "arch/arm/mm/dma-mapping.c:__iommu_remove_mapping",
        "arch/arm/mm/dma-mapping.c:__iommu_create_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 3224512064,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/arm/mm/context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/context.c:check_and_switch_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3225195328,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226497012,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 3226872212,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_clear_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3229692184,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/irqchip/irq-alpine-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-alpine-msi.c:alpine_msix_free_sgi"
      ],
      "caller_func": []
    },
    {
      "addr": 3229739552,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/irqchip/irq-armada-370-xp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_msi_free"
      ],
      "caller_func": []
    },
    {
      "addr": 3230031140,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/gpio/gpiolib-of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-of.c:of_gpiochip_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3230091716,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3231708092,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 3232398032,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/mtd/nand/raw/nand_macronix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232881720,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 3235891184,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236525728,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_store"
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
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282497884,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/powerpc/kernel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/iommu.c:__iommu_free"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282915936,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/powerpc/sysdev/msi_bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_free_hwirqs"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283053808,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/powerpc/platforms/powernv/pci-ioda.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284068268,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285979284,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286788348,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_clear_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290838888,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/gpio/gpiolib-of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-of.c:of_gpiochip_add"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290874280,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292375904,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293773808,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296960920,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297765260,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_store"
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
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271721570,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272670436,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273018580,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_clear_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275496680,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/gpio/gpiolib-of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-of.c:of_gpiochip_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275518020,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276469892,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277317856,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279256092,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279784944,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_store"
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
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579063486,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220079,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579347181,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579350839,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579951717,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581224179,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768182,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_clear_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584527648,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585169927,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586098696,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586149754,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_release_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587016011,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589154890,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589717180,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_store"
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
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578996222,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579155007,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579279389,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579283047,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579889605,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581170173,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581706806,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_clear_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585112919,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585944648,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588879882,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589442956,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_store"
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
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579063070,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579221151,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579347101,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579350759,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943253,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581215379,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581759494,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_clear_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584523360,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586283416,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586335434,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_release_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587264491,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589591754,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590160556,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_store"
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
  "name": "bitmap_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579067001,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579226511,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579355549,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579359207,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579990149,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581278074,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581828342,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_clear_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584631136,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585435687,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586394872,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/base/regmap/regcache-rbtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586435306,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_release_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587371259,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589639690,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590211196,
      "name": "bitmap_clear",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "lib/xarray.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/xarray.c:xas_store"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void bitmap_clear(long unsigned int * map, unsigned int start, int len)
```
</details>
</li>
</ul>
