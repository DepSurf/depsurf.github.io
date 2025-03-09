# Function: <code>__bitmap_clear</code>

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
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583441792,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:275",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:sys_ioperm",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:iommu_free",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/cma.c:cma_clear_bitmap",
        "lib/iommu-common.c:iommu_tbl_range_free",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/block/xen-blkfront.c:xlbd_release_minors",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583441792,
      "name": "__bitmap_clear",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583621728,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:277",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:sys_ioperm",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:iommu_free",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/cma.c:cma_clear_bitmap",
        "lib/iommu-common.c:iommu_tbl_range_free",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/block/xen-blkfront.c:xlbd_release_minors",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621728,
      "name": "__bitmap_clear",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583838064,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:274",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:iommu_free",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/cma.c:cma_clear_bitmap",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/block/xen-blkfront.c:xlbd_release_minors",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583838064,
      "name": "__bitmap_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583921696,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:271",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:iommu_free",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/cma.c:cma_clear_bitmap",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/block/xen-blkfront.c:xlbd_release_minors",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921696,
      "name": "__bitmap_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584101488,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:271",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:iommu_free",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/cma.c:cma_clear_bitmap",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/block/xen-blkfront.c:xlbd_release_minors",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584101488,
      "name": "__bitmap_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584224272,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:291",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:iommu_free",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/cma.c:cma_clear_bitmap",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/block/xen-blkfront.c:xlbd_release_minors",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584224272,
      "name": "__bitmap_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584630336,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:370",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "lib/bitmap.c:bitmap_parse",
        "lib/xarray.c:xas_store",
        "drivers/pwm/core.c:free_pwms",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/block/xen-blkfront.c:xlbd_release_minors",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584630336,
      "name": "__bitmap_clear",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584749392,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:370",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page",
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "lib/bitmap.c:bitmap_parse",
        "lib/xarray.c:xas_store",
        "drivers/pwm/core.c:free_pwms",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/block/xen-blkfront.c:xlbd_release_minors",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584749392,
      "name": "__bitmap_clear",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777728,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:372",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page",
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "lib/bitmap.c:bitmap_parse",
        "lib/xarray.c:xas_store",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/block/xen-blkfront.c:xlbd_release_minors",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777728,
      "name": "__bitmap_clear",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585207744,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:372",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page",
        "mm/percpu.c:pcpu_chunk_depopulated",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "lib/bitmap.c:bitmap_parse",
        "lib/xarray.c:xas_squash_marks",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/block/xen-blkfront.c:xlbd_release_minors",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585207744,
      "name": "__bitmap_clear",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586043648,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:372",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page",
        "kernel/bpf/core.c:bpf_prog_pack_free",
        "mm/percpu.c:pcpu_chunk_depopulated",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "lib/bitmap.c:bitmap_parse",
        "lib/xarray.c:xas_store",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/xen/grant-table.c:get_free_entries_seq",
        "drivers/xen/grant-table.c:get_free_seq",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/block/xen-blkfront.c:xlbd_release_minors",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043648,
      "name": "__bitmap_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587026464,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:383",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/amd_gart_64.c:free_iommu",
        "kernel/irq/irqdesc.c:irq_free_descs",
        "kernel/bpf/core.c:bpf_prog_pack_free",
        "mm/percpu.c:pcpu_chunk_depopulated",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "lib/bitmap.c:bitmap_parse",
        "drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/xen/grant-table.c:get_free_entries_seq",
        "drivers/xen/grant-table.c:get_free_seq",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/block/xen-blkfront.c:xlbd_release_minors",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "lib/xarray.c:xas_squash_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587026464,
      "name": "__bitmap_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587281456,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:383",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/amd_gart_64.c:free_iommu",
        "kernel/bpf/core.c:bpf_prog_pack_free",
        "mm/percpu.c:pcpu_chunk_depopulated",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/vmalloc.c:vb_free",
        "mm/vmalloc.c:vb_free",
        "lib/bitmap.c:bitmap_parse",
        "drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/xen/grant-table.c:get_free_entries_seq",
        "drivers/xen/grant-table.c:get_free_seq",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/block/xen-blkfront.c:xlbd_release_minors",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule",
        "drivers/firmware/efi/unaccepted_memory.c:accept_memory",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "lib/xarray.c:xas_squash_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587281456,
      "name": "__bitmap_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587570192,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:372",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/amd_gart_64.c:free_iommu",
        "kernel/bpf/core.c:bpf_prog_pack_free",
        "mm/percpu.c:pcpu_chunk_depopulated",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/vmalloc.c:vb_free",
        "mm/vmalloc.c:vb_free",
        "lib/bitmap-str.c:bitmap_parse",
        "drivers/gpio/gpiolib.c:gpiochip_apply_reserved_ranges",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free",
        "drivers/acpi/numa/hmat.c:hmat_update_target_attrs",
        "drivers/xen/grant-table.c:get_free_entries_seq",
        "drivers/xen/grant-table.c:get_free_seq",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/block/xen-blkfront.c:xlbd_release_minors",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule",
        "drivers/firmware/efi/unaccepted_memory.c:accept_memory",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "net/ethtool/bitset.c:ethnl_parse_bitset",
        "lib/xarray.c:xas_squash_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587570192,
      "name": "__bitmap_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496098040,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:291",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/context.c:check_and_switch_context",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/cma.c:cma_clear_bitmap",
        "drivers/gpio/gpiolib-of.c:of_gpiochip_add",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/pci/controller/pci-aardvark.c:advk_msi_irq_domain_free",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_irq_domain_free",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_irq_domain_free",
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/block/xen-blkfront.c:xlbd_release_minors",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496098040,
      "name": "__bitmap_clear",
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
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229424916,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:291",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/dma-mapping.c:arm_iommu_unmap_resource",
        "arch/arm/mm/dma-mapping.c:arm_iommu_map_resource",
        "arch/arm/mm/dma-mapping.c:arm_iommu_unmap_page",
        "arch/arm/mm/dma-mapping.c:arm_coherent_iommu_unmap_page",
        "arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_page",
        "arch/arm/mm/dma-mapping.c:__map_sg_chunk",
        "arch/arm/mm/dma-mapping.c:__iommu_remove_mapping",
        "arch/arm/mm/dma-mapping.c:__iommu_create_mapping",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/cma.c:cma_clear_bitmap",
        "drivers/irqchip/irq-alpine-msi.c:alpine_msix_free_sgi",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_msi_free",
        "drivers/gpio/gpiolib-of.c:of_gpiochip_add",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229424916,
      "name": "__bitmap_clear",
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
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290342464,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:291",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/iommu.c:__iommu_free",
        "arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_free_hwirqs",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_disable",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/cma.c:cma_clear_bitmap",
        "drivers/gpio/gpiolib-of.c:of_gpiochip_add",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290342464,
      "name": "__bitmap_clear",
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
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275166246,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:291",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/cma.c:cma_clear_bitmap",
        "drivers/gpio/gpiolib-of.c:of_gpiochip_add",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275166246,
      "name": "__bitmap_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584193008,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:291",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:iommu_free",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/cma.c:cma_clear_bitmap",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/block/xen-blkfront.c:xlbd_release_minors",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584193008,
      "name": "__bitmap_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584128224,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:291",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:iommu_free",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/cma.c:cma_clear_bitmap",
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584128224,
      "name": "__bitmap_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584176768,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:291",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:iommu_free",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/cma.c:cma_clear_bitmap",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/block/xen-blkfront.c:xlbd_release_minors",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584176768,
      "name": "__bitmap_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "__bitmap_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584281104,
      "name": "__bitmap_clear",
      "external": true,
      "loc": "lib/bitmap.c:291",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_page",
        "arch/x86/kernel/pci-calgary_64.c:iommu_free",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_free_area",
        "mm/percpu.c:pcpu_alloc_area",
        "mm/cma.c:cma_clear_bitmap",
        "drivers/pwm/core.c:pwmchip_remove",
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop",
        "drivers/block/xen-blkfront.c:xlbd_release_minors",
        "drivers/usb/dwc2/hcd_queue.c:pmap_unschedule",
        "lib/xarray.c:xas_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584281104,
      "name": "__bitmap_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void __bitmap_clear(long unsigned int * map, unsigned int start, int len)
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
