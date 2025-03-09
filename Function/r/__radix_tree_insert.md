# Function: <code>__radix_tree_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __radix_tree_insert(struct radix_tree_root * root, long unsigned int index, unsigned int order, void * item)
```

```json
{
  "name": "__radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583258032,
      "name": "__radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:633",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/memremap.c:devm_memremap_pages",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_map_ram",
        "mm/swap_state.c:__add_to_swap_cache",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:dax_fault",
        "fs/dax.c:dax_fault",
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
      "addr": 18446744071583258032,
      "name": "__radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int __radix_tree_insert(struct radix_tree_root * root, long unsigned int index, unsigned int order, void * item)
```

```json
{
  "name": "__radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583374336,
      "name": "__radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:867",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/memremap.c:devm_memremap_pages",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_map_ram",
        "mm/swap_state.c:__add_to_swap_cache",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:dax_insert_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
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
      "addr": 18446744071583374336,
      "name": "__radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
int __radix_tree_insert(struct radix_tree_root * root, long unsigned int index, unsigned int order, void * item)
```

```json
{
  "name": "__radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588223712,
      "name": "__radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:985",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_associate",
        "kernel/memremap.c:devm_memremap_pages",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_map_ram",
        "mm/swap_state.c:__add_to_swap_cache",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:grab_mapping_entry",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create",
        "drivers/pwm/core.c:pwmchip_add_with_polarity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588223712,
      "name": "__radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
int __radix_tree_insert(struct radix_tree_root * root, long unsigned int index, unsigned int order, void * item)
```

```json
{
  "name": "__radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588773776,
      "name": "__radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:984",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/memremap.c:devm_memremap_pages",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_map_ram",
        "mm/swap_state.c:__add_to_swap_cache",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/hmm.c:hmm_devmem_pages_create",
        "fs/dax.c:grab_mapping_entry",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create",
        "drivers/pwm/core.c:pwmchip_add_with_polarity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588773776,
      "name": "__radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
int __radix_tree_insert(struct radix_tree_root * root, long unsigned int index, unsigned int order, void * item)
```

```json
{
  "name": "__radix_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589152464,
      "name": "__radix_tree_insert",
      "external": true,
      "loc": "lib/radix-tree.c:985",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/memremap.c:devm_memremap_pages",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/backing-dev.c:wb_get_create",
        "mm/vmalloc.c:vm_map_ram",
        "mm/swap_state.c:__add_to_swap_cache",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/hmm.c:hmm_devmem_pages_create",
        "fs/dax.c:grab_mapping_entry",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-cgroup.c:blkg_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589152464,
      "name": "__radix_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 543
    }
  ]
}
```
</details>
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int __radix_tree_insert(struct radix_tree_root * root, long unsigned int index, unsigned int order, void * item)
```
</details>
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int __radix_tree_insert(struct radix_tree_root * root, long unsigned int index, unsigned int order, void * item)
```
</details>
</li>
</ul>
