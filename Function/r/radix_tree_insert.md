# Function: <code>radix_tree_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int radix_tree_insert(struct radix_tree_root * root, long unsigned int index, void * item)
```

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582969392,
      "name": "radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:448",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_map_ram",
        "mm/swap_state.c:__add_to_swap_cache",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create",
        "drivers/pinctrl/core.c:pinctrl_register",
        "drivers/pwm/core.c:pwmchip_add_with_polarity",
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582969392,
      "name": "radix_tree_insert",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587834838,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:270",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579790473,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:270",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580540922,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:270",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:devm_memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580681915,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:270",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580715127,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:270",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580857883,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:270",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vm_map_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580877810,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:270",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581052073,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:270",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581498933,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:270",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault",
        "fs/dax.c:dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583052301,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:270",
      "file": "block/blk-ioc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-ioc.c:ioc_create_icq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583160913,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:270",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583461647,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:270",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583531535,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:270",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_add_with_polarity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584884741,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:270",
      "file": "drivers/block/brd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585871605,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:270",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping"
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
  "name": "radix_tree_insert",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588050110,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:290",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579817593,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:290",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580604973,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:290",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:devm_memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580748955,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:290",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580780953,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:290",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580928139,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:290",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vm_map_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580945848,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:290",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581123737,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:290",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583158077,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:290",
      "file": "block/blk-ioc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-ioc.c:ioc_create_icq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583272977,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:290",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583589375,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:290",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/core.c:pinctrl_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583667567,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:290",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_add_with_polarity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586060453,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:290",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping"
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
  "name": "radix_tree_insert",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588277327,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:294",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579815998,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:294",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580634512,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:294",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:devm_memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580783149,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:294",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580818304,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:294",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580972291,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:294",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vm_map_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580990226,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:294",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581175096,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:294",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583215517,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:294",
      "file": "block/blk-ioc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-ioc.c:ioc_create_icq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583328309,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:294",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583626444,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:294",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583707511,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:294",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_add_with_polarity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586142332,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:294",
      "file": "drivers/usb/host/xhci-mem.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588843072,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:293",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579847401,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:293",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580869901,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:293",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580908569,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:293",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581074931,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:293",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vm_map_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581094148,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:293",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299766,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:293",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581391269,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:293",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_devmem_pages_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583392141,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:293",
      "file": "block/blk-ioc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-ioc.c:ioc_create_icq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583511560,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:293",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583872556,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:293",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583964903,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:293",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/core.c:pwmchip_add_with_polarity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586587276,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:293",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587305578,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:293",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589222332,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:297",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579881189,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:297",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581003304,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:297",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044570,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:297",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581213663,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:297",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vm_map_ram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581234928,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:297",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581447005,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:297",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581540490,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:297",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_devmem_pages_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583602113,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:297",
      "file": "block/blk-ioc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-ioc.c:ioc_create_icq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583726564,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:297",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584073126,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:297",
      "file": "drivers/pinctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584159558,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:297",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586851899,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:297",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587608784,
      "name": "radix_tree_insert",
      "external": false,
      "loc": "include/linux/radix-tree.h:297",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int radix_tree_insert(struct xarray * root, long unsigned int index, void * item)
```

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589385200,
      "name": "radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:725",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_map_ram",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589385200,
      "name": "radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
int radix_tree_insert(struct xarray * root, long unsigned int index, void * item)
```

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589842208,
      "name": "radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:712",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_map_ram",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589842208,
      "name": "radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int radix_tree_insert(struct xarray * root, long unsigned int index, void * item)
```

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590068304,
      "name": "radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:712",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_map_ram",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590068304,
      "name": "radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int radix_tree_insert(struct xarray * root, long unsigned int index, void * item)
```

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585065568,
      "name": "radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:704",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:irq_domain_insert_irq",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "mm/backing-dev.c:cgwb_create",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create",
        "drivers/pinctrl/core.c:pinctrl_register_one_pin",
        "drivers/pwm/core.c:pwmchip_add_with_polarity",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register",
        "net/mptcp/token.c:mptcp_token_new_accept",
        "net/mptcp/token.c:mptcp_token_new_connect",
        "net/mptcp/token.c:mptcp_token_new_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585065568,
      "name": "radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int radix_tree_insert(struct xarray * root, long unsigned int index, void * item)
```

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585214896,
      "name": "radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:704",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:irq_domain_insert_irq",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "mm/backing-dev.c:cgwb_create",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create",
        "drivers/pinctrl/core.c:pinctrl_register_one_pin",
        "drivers/pwm/core.c:pwmchip_add_with_polarity",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585214896,
      "name": "radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int radix_tree_insert(struct xarray * root, long unsigned int index, void * item)
```

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585097200,
      "name": "radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:704",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "mm/backing-dev.c:cgwb_create",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create",
        "drivers/pwm/core.c:pwmchip_add",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585097200,
      "name": "radix_tree_insert",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int radix_tree_insert(struct xarray * root, long unsigned int index, void * item)
```

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:704",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "mm/backing-dev.c:cgwb_create",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create",
        "drivers/pwm/core.c:pwmchip_add",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592343723,
      "name": "radix_tree_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071585545808,
      "name": "radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int radix_tree_insert(struct xarray * root, long unsigned int index, void * item)
```

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:704",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "mm/backing-dev.c:cgwb_create",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create",
        "drivers/pwm/core.c:pwmchip_add",
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594205259,
      "name": "radix_tree_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071586701440,
      "name": "radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int radix_tree_insert(struct xarray * root, long unsigned int index, void * item)
```

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:704",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_associate_locked",
        "mm/backing-dev.c:cgwb_create",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create",
        "drivers/pwm/core.c:pwmchip_add",
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596374472,
      "name": "radix_tree_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071595863088,
      "name": "radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int radix_tree_insert(struct xarray * root, long unsigned int index, void * item)
```

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:703",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_associate_locked",
        "mm/backing-dev.c:cgwb_create",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create",
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596903996,
      "name": "radix_tree_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071596380448,
      "name": "radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int radix_tree_insert(struct xarray * root, long unsigned int index, void * item)
```

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:703",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_push_irq",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_associate_locked",
        "mm/backing-dev.c:cgwb_create",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create",
        "drivers/pinctrl/core.c:pinctrl_register_pins",
        "drivers/usb/host/xhci-mem.c:xhci_update_stream_segment_mapping",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597829089,
      "name": "radix_tree_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071597275696,
      "name": "radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
int radix_tree_insert(struct xarray * root, long unsigned int index, void * item)
```

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503845864,
      "name": "radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:712",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_map_ram",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503845864,
      "name": "radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
int radix_tree_insert(struct xarray * root, long unsigned int index, void * item)
```

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236465664,
      "name": "radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:712",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_map_ram",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236465664,
      "name": "radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int radix_tree_insert(struct xarray * root, long unsigned int index, void * item)
```

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297699888,
      "name": "radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:712",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_map_ram",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297699888,
      "name": "radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 760
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
int radix_tree_insert(struct xarray * root, long unsigned int index, void * item)
```

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279736306,
      "name": "radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:712",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_map_ram",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279736306,
      "name": "radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
int radix_tree_insert(struct xarray * root, long unsigned int index, void * item)
```

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589670560,
      "name": "radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:712",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_map_ram",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589670560,
      "name": "radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int radix_tree_insert(struct xarray * root, long unsigned int index, void * item)
```

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589396384,
      "name": "radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:712",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_map_ram",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589396384,
      "name": "radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int radix_tree_insert(struct xarray * root, long unsigned int index, void * item)
```

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590113936,
      "name": "radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:712",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_map_ram",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590113936,
      "name": "radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int radix_tree_insert(struct xarray * root, long unsigned int index, void * item)
```

```json
{
  "name": "radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590164320,
      "name": "radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:712",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_map_ram",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590164320,
      "name": "radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int radix_tree_insert(struct radix_tree_root * root, long unsigned int index, void * item)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int radix_tree_insert(struct xarray * root, long unsigned int index, void * item)
```
</details>
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
