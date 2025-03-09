# Function: <code>bitmap_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583010976,
      "name": "bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:252",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:sys_ioperm",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/cma.c:cma_alloc",
        "lib/iommu-helper.c:iommu_area_alloc",
        "drivers/pwm/core.c:pwmchip_add_with_polarity",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583010976,
      "name": "bitmap_set",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583301488,
      "name": "bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:254",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:sys_ioperm",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc",
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
      "addr": 18446744071583301488,
      "name": "bitmap_set",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void bitmap_set(long unsigned int * map, unsigned int start, int len)
```

```json
{
  "name": "bitmap_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583420528,
      "name": "bitmap_set",
      "external": true,
      "loc": "lib/bitmap.c:254",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ioport.c:sys_ioperm",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_alloc",
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
      "addr": 18446744071583420528,
      "name": "bitmap_set",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579035745,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:315",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:sys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596384536,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:315",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579283006,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:315",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427724,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:315",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588277038,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:315",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580822343,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:315",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581247478,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:315",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583016870,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:315",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583575374,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:315",
      "file": "lib/iommu-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-helper.c:iommu_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583707619,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:315",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_add_with_polarity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584964037,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:315",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585188632,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:315",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585986415,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:315",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
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
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579043585,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:sys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602703047,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301694,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579455975,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588843253,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579865007,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580910044,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379062,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583181894,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583623849,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:__bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583821198,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "lib/iommu-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-helper.c:iommu_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583965014,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_add_with_polarity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585385333,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585616886,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586430399,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:333",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
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
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579048311,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602875611,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313676,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579470727,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589222489,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579899151,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581045900,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581529079,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583388182,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583840410,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:__bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584022411,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "lib/iommu-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-helper.c:iommu_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584159590,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585628086,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585867413,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586694663,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:364",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
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
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579053191,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338340,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579504395,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589464625,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579946537,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581123564,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581614860,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583507958,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583923402,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:__bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584104107,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "lib/iommu-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-helper.c:iommu_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584218272,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584247316,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585755286,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585996149,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586851687,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
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
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579060887,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579353552,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579522942,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589924725,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579985166,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581188480,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581522421,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:subsection_mask_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581726479,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583695606,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584103485,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584292897,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "lib/iommu-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-helper.c:iommu_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584407012,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584439653,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585987087,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586239876,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587110034,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589326247,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:365",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579063015,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579357888,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579549022,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590150837,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580035294,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581246928,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581587013,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:subsection_mask_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581800031,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583803737,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584226269,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584427617,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "lib/iommu-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-helper.c:iommu_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584542692,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584576421,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584635106,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_add_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586134095,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586388100,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587310434,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589550503,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579071064,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:405",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579575857,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:405",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580031769,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:405",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580086062,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:405",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581435952,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:405",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581799029,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:405",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:subsection_mask_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584198393,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:405",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584633320,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:405",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584989767,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:405",
      "file": "lib/iommu-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-helper.c:iommu_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585215652,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:405",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585250040,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:405",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_add_with_polarity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585318160,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:405",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_add_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586885601,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:405",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587160792,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:405",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_reserve_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587890138,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:405",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap",
        "drivers/vfio/vfio_iommu_type1.c:update_user_bitmap",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588167425,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:405",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590554006,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:405",
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
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579075352,
      "name": "bitmap_set",
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
      "addr": 18446744071579557473,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580015481,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580069646,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581479072,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581846933,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:subsection_mask_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582274302,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:__close_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582762106,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584317081,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584752360,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585111783,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "lib/iommu-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-helper.c:iommu_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585366907,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585407467,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_add_with_polarity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585473136,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_add_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586935873,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587245016,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_reserve_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587950018,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap",
        "drivers/vfio/vfio_iommu_type1.c:update_user_bitmap",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_populate_bitmap_full"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588205537,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590613798,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
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
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579082328,
      "name": "bitmap_set",
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
      "addr": 18446744071579562202,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579906813,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_init_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580016265,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580070316,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581504112,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581877765,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:subsection_mask_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582299651,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:__close_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582790090,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584351488,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584780440,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584991943,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "lib/iommu-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-helper.c:iommu_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585251006,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585288475,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585352992,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_add_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586820137,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587139394,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_reserve_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587828932,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap",
        "drivers/vfio/vfio_iommu_type1.c:update_user_bitmap",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588088753,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590539015,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:403",
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
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579105288,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579637864,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580026520,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580148437,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580203916,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581765216,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582169365,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:subsection_mask_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582618707,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:__close_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583116103,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584742719,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585211318,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585432615,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "lib/iommu-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-helper.c:iommu_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585706983,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585745195,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585811984,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_add_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587380057,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587713762,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_reserve_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588433729,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:update_user_bitmap",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_populate_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588720833,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591348585,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:409",
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
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579135796,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579734056,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580197606,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_init_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580293285,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580357931,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581385365,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_pack_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582149376,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582627125,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:subsection_mask_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583153585,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:__close_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583600565,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585421626,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586047523,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586572307,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "lib/iommu-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-helper.c:iommu_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586875208,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586927750,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587001060,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_add_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588049905,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_set_free",
        "drivers/xen/grant-table.c:put_free_entry_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588687828,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589044685,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_reserve_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589833566,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:update_user_bitmap",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_populate_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590138913,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593020960,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:429",
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
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579177108,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579860632,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580388510,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_init_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580503893,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580580683,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581739321,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_pack_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582627728,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583151461,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:subsection_mask_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583727409,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:__close_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584205861,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586176578,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587031340,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587807283,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
      "file": "lib/iommu-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-helper.c:iommu_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588024682,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588083471,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588169742,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_add_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589429025,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_set_free",
        "drivers/xen/grant-table.c:put_free_entry_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590165569,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590573765,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_reserve_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591752881,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594912188,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:453",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579180484,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579910789,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580457102,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_init_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580653611,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581898793,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_pack_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582836592,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583125219,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583361797,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:subsection_mask_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583944465,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:__close_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584435717,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586414178,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587286261,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588078755,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
      "file": "lib/iommu-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-helper.c:iommu_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588299031,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588357839,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588445780,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_add_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589728177,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_set_free",
        "drivers/xen/grant-table.c:put_free_entry_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590479807,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590914872,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_reserve_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592176209,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595303870,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:451",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579209700,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579950037,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580516750,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_init_numa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580718827,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582023305,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_pack_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583011536,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583308210,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583598245,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:subsection_mask_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584151647,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:__close_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584658953,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:ifs_alloc",
        "fs/iomap/buffered-io.c:ifs_alloc",
        "fs/iomap/buffered-io.c:ifs_set_range_dirty",
        "fs/iomap/buffered-io.c:ifs_set_range_uptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586679122,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587633477,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "lib/bitmap-str.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap-str.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588414035,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "lib/iommu-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-helper.c:iommu_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588592457,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588742644,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_add_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589009358,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589021704,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "drivers/pci/controller/dwc/pcie-designware-host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590066145,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_set_free",
        "drivers/xen/grant-table.c:put_free_entry_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590830335,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "drivers/iommu/intel/irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte",
        "drivers/iommu/intel/irq_remapping.c:alloc_irte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590845352,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "drivers/iommu/iommufd/iova_bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommufd/iova_bitmap.c:iova_bitmap_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591258664,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlbd_reserve_minors"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592032657,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "drivers/gpu/drm/drm_edid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_edid.c:drm_parse_cea_ext",
        "drivers/gpu/drm/drm_edid.c:drm_parse_cea_ext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592916897,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593459772,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593462345,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
      "file": "drivers/ptp/ptp_chardev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_chardev.c:ptp_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596145486,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:428",
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490697792,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503902528,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492647236,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493025036,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:subsection_mask_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493264964,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495607384,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496100412,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496426916,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/irqchip/irq-ls-scfg-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_remove",
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496729828,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496808084,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496882252,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_add_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497101604,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/pci/controller/pci-aardvark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-aardvark.c:advk_msi_irq_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497124816,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/pci/controller/pci-xgene-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-xgene-msi.c:xgene_irq_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497127116,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/pci/controller/pcie-iproc-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_irq_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498137448,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/soc/qcom/rpmh-rsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_write_ctrl_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499237048,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500427680,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503221404,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224493812,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "arch/arm/mm/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/dma-mapping.c:arm_iommu_map_resource",
        "arch/arm/mm/dma-mapping.c:arm_iommu_map_resource",
        "arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_page",
        "arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_page",
        "arch/arm/mm/dma-mapping.c:__map_sg_chunk",
        "arch/arm/mm/dma-mapping.c:__map_sg_chunk",
        "arch/arm/mm/dma-mapping.c:__iommu_create_mapping",
        "arch/arm/mm/dma-mapping.c:__iommu_create_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 3224765948,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3236530080,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 3226487604,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 3226872892,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3228967972,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 3229427420,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 3229692428,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/irqchip/irq-alpine-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-alpine-msi.c:alpine_msix_middle_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3229739676,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/irqchip/irq-armada-370-xp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_msi_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3230020308,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array"
      ],
      "caller_func": []
    },
    {
      "addr": 3230095760,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230159340,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_add_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 3230854268,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/dma/ti/edma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/ti/edma.c:edma_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3232392952,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/mtd/nand/raw/nand_onfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mtd/nand/raw/nand_onfi.c:nand_onfi_detect",
        "drivers/mtd/nand/raw/nand_onfi.c:nand_onfi_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 3232398000,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/mtd/nand/raw/nand_macronix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232882228,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 3235891184,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282835188,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "arch/powerpc/mm/slice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/slice.c:slice_range_to_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282915652,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "arch/powerpc/sysdev/msi_bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_alloc_hwirqs"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283053232,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "arch/powerpc/platforms/powernv/pci-ioda.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283525452,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284072848,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285963612,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286454264,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:subsection_mask_set"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286789216,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289721960,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290345908,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290624656,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "lib/iommu-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-helper.c:iommu_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290821196,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290881288,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290967304,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_add_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293774544,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296960876,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271424034,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279790396,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272661764,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270697822,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:subsection_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273019194,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274769198,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275168778,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275486022,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275521630,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275579862,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_add_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277318310,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279256072,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579063367,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579353792,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579522686,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589753125,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580004030,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581215776,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581555749,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:subsection_mask_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768767,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583772473,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584195005,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584396353,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "lib/iommu-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-helper.c:iommu_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584499620,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584530869,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584587266,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_add_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585894463,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586150388,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587016514,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589154871,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578996103,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286000,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579451486,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589477349,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579942702,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581162480,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581497397,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:subsection_mask_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581707391,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583709529,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584130221,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584331553,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "lib/iommu-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-helper.c:iommu_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584437748,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584515394,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_add_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585754239,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588879863,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579062951,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579353712,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579522606,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590196533,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579995566,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581206976,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581547061,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:subsection_mask_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581760079,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583756233,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584178765,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584379265,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "lib/iommu-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-helper.c:iommu_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584494356,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584526581,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584585266,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_add_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586084111,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586336068,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587264994,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589591735,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "bitmap_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579066866,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362160,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:iommu_range_reserve"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579555566,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_large_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590246965,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580042302,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "kernel/irq/matrix.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581270336,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_chunk_populated",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_first_chunk",
        "mm/percpu.c:pcpu_alloc_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612181,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:subsection_mask_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581828927,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "mm/cma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cma.c:cma_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583857225,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "security/integrity/ima/ima_template.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list",
        "security/integrity/ima/ima_template.c:ima_restore_measurement_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584283101,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "lib/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584485329,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "lib/iommu-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iommu-helper.c:iommu_area_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584600628,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_get_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584634357,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584692930,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_add_dma_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586192399,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586446452,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587371762,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:pmap_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589639671,
      "name": "bitmap_set",
      "external": false,
      "loc": "include/linux/bitmap.h:389",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
void bitmap_set(long unsigned int * map, unsigned int start, int len)
```
</details>
</li>
</ul>
