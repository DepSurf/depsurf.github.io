# Function: <code>gen_pool_free_owner</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void gen_pool_free_owner(struct gen_pool * pool, long unsigned int addr, size_t size, void * * owner)
```

```json
{
  "name": "gen_pool_free_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584181328,
      "name": "gen_pool_free_owner",
      "external": true,
      "loc": "lib/genalloc.c:485",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_free",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:td_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584181328,
      "name": "gen_pool_free_owner",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void gen_pool_free_owner(struct gen_pool * pool, long unsigned int addr, size_t size, void * * owner)
```

```json
{
  "name": "gen_pool_free_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584315024,
      "name": "gen_pool_free_owner",
      "external": true,
      "loc": "lib/genalloc.c:485",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_free",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:td_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584315024,
      "name": "gen_pool_free_owner",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void gen_pool_free_owner(struct gen_pool * pool, long unsigned int addr, size_t size, void * * owner)
```

```json
{
  "name": "gen_pool_free_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584726816,
      "name": "gen_pool_free_owner",
      "external": true,
      "loc": "lib/genalloc.c:485",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process",
        "kernel/dma/pool.c:dma_free_from_pool",
        "kernel/dma/pool.c:__dma_alloc_from_pool",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free",
        "drivers/acpi/apei/ghes.c:ghes_kick_task_work",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584726816,
      "name": "gen_pool_free_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void gen_pool_free_owner(struct gen_pool * pool, long unsigned int addr, size_t size, void * * owner)
```

```json
{
  "name": "gen_pool_free_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584840016,
      "name": "gen_pool_free_owner",
      "external": true,
      "loc": "lib/genalloc.c:486",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process",
        "kernel/dma/pool.c:dma_free_from_pool",
        "kernel/dma/pool.c:__dma_alloc_from_pool",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free",
        "drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func",
        "drivers/acpi/apei/ghes.c:ghes_kick_task_work",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584840016,
      "name": "gen_pool_free_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void gen_pool_free_owner(struct gen_pool * pool, long unsigned int addr, size_t size, void * * owner)
```

```json
{
  "name": "gen_pool_free_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584884672,
      "name": "gen_pool_free_owner",
      "external": true,
      "loc": "lib/genalloc.c:487",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process",
        "kernel/dma/pool.c:dma_free_from_pool",
        "kernel/dma/pool.c:dma_alloc_from_pool",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free",
        "drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func",
        "drivers/acpi/apei/ghes.c:ghes_kick_task_work",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584884672,
      "name": "gen_pool_free_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void gen_pool_free_owner(struct gen_pool * pool, long unsigned int addr, size_t size, void * * owner)
```

```json
{
  "name": "gen_pool_free_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gen_pool_free_owner",
      "external": true,
      "loc": "lib/genalloc.c:487",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process",
        "kernel/dma/pool.c:dma_free_from_pool",
        "kernel/dma/pool.c:dma_alloc_from_pool",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free",
        "drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func",
        "drivers/acpi/apei/ghes.c:ghes_kick_task_work",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592326864,
      "name": "gen_pool_free_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071585310480,
      "name": "gen_pool_free_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void gen_pool_free_owner(struct gen_pool * pool, long unsigned int addr, size_t size, void * * owner)
```

```json
{
  "name": "gen_pool_free_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gen_pool_free_owner",
      "external": true,
      "loc": "lib/genalloc.c:487",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process",
        "kernel/dma/pool.c:dma_free_from_pool",
        "kernel/dma/pool.c:dma_alloc_from_pool",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free",
        "drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func",
        "drivers/acpi/apei/ghes.c:ghes_kick_task_work",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594131223,
      "name": "gen_pool_free_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071586167648,
      "name": "gen_pool_free_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void gen_pool_free_owner(struct gen_pool * pool, long unsigned int addr, size_t size, void * * owner)
```

```json
{
  "name": "gen_pool_free_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gen_pool_free_owner",
      "external": true,
      "loc": "lib/genalloc.c:487",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process",
        "kernel/dma/pool.c:dma_free_from_pool",
        "kernel/dma/pool.c:dma_alloc_from_pool",
        "drivers/pci/p2pdma.c:pci_p2pmem_free_sgl",
        "drivers/pci/p2pdma.c:pci_alloc_p2pmem",
        "drivers/pci/p2pdma.c:p2pdma_page_free",
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap",
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free",
        "drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func",
        "drivers/acpi/apei/ghes.c:ghes_kick_task_work",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596117910,
      "name": "gen_pool_free_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071587162112,
      "name": "gen_pool_free_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void gen_pool_free_owner(struct gen_pool * pool, long unsigned int addr, size_t size, void * * owner)
```

```json
{
  "name": "gen_pool_free_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gen_pool_free_owner",
      "external": true,
      "loc": "lib/genalloc.c:485",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process",
        "kernel/dma/pool.c:dma_free_from_pool",
        "kernel/dma/pool.c:__dma_alloc_from_pool",
        "drivers/pci/p2pdma.c:pci_p2pmem_free_sgl",
        "drivers/pci/p2pdma.c:pci_alloc_p2pmem",
        "drivers/pci/p2pdma.c:p2pdma_page_free",
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap",
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free",
        "drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func",
        "drivers/acpi/apei/ghes.c:ghes_kick_task_work",
        "drivers/usb/core/buffer.c:hcd_buffer_free_pages",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596644047,
      "name": "gen_pool_free_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071587425216,
      "name": "gen_pool_free_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void gen_pool_free_owner(struct gen_pool * pool, long unsigned int addr, size_t size, void * * owner)
```

```json
{
  "name": "gen_pool_free_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gen_pool_free_owner",
      "external": true,
      "loc": "lib/genalloc.c:487",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process",
        "kernel/dma/pool.c:dma_free_from_pool",
        "kernel/dma/pool.c:__dma_alloc_from_pool",
        "drivers/pci/p2pdma.c:pci_p2pmem_free_sgl",
        "drivers/pci/p2pdma.c:pci_alloc_p2pmem",
        "drivers/pci/p2pdma.c:p2pdma_page_free",
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap",
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_rcu_free",
        "drivers/acpi/apei/ghes.c:ghes_vendor_record_work_func",
        "drivers/acpi/apei/ghes.c:ghes_kick_task_work",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_region_free",
        "drivers/usb/core/buffer.c:hcd_buffer_free_pages",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:td_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597553724,
      "name": "gen_pool_free_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071587760000,
      "name": "gen_pool_free_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void gen_pool_free_owner(struct gen_pool * pool, long unsigned int addr, size_t size, void * * owner)
```

```json
{
  "name": "gen_pool_free_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496204136,
      "name": "gen_pool_free_owner",
      "external": true,
      "loc": "lib/genalloc.c:485",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/remap.c:dma_free_from_pool",
        "drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_free",
        "drivers/net/ethernet/freescale/fman/fman_muram.c:fman_muram_free_mem",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:td_free",
        "drivers/edac/altera_edac.c:ocram_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496204136,
      "name": "gen_pool_free_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void gen_pool_free_owner(struct gen_pool * pool, long unsigned int addr, size_t size, void * * owner)
```

```json
{
  "name": "gen_pool_free_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229526932,
      "name": "gen_pool_free_owner",
      "external": true,
      "loc": "lib/genalloc.c:485",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/dma-mapping.c:__free_from_pool",
        "drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_free",
        "drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:td_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229526932,
      "name": "gen_pool_free_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void gen_pool_free_owner(struct gen_pool * pool, long unsigned int addr, size_t size, void * * owner)
```

```json
{
  "name": "gen_pool_free_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290485856,
      "name": "gen_pool_free_owner",
      "external": true,
      "loc": "lib/genalloc.c:485",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:td_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290485856,
      "name": "gen_pool_free_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void gen_pool_free_owner(struct gen_pool * pool, long unsigned int addr, size_t size, void * * owner)
```

```json
{
  "name": "gen_pool_free_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275254136,
      "name": "gen_pool_free_owner",
      "external": true,
      "loc": "lib/genalloc.c:485",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:td_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275254136,
      "name": "gen_pool_free_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void gen_pool_free_owner(struct gen_pool * pool, long unsigned int addr, size_t size, void * * owner)
```

```json
{
  "name": "gen_pool_free_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584283760,
      "name": "gen_pool_free_owner",
      "external": true,
      "loc": "lib/genalloc.c:485",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:td_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584283760,
      "name": "gen_pool_free_owner",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void gen_pool_free_owner(struct gen_pool * pool, long unsigned int addr, size_t size, void * * owner)
```

```json
{
  "name": "gen_pool_free_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584218960,
      "name": "gen_pool_free_owner",
      "external": true,
      "loc": "lib/genalloc.c:485",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process",
        "drivers/usb/core/buffer.c:hcd_buffer_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584218960,
      "name": "gen_pool_free_owner",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void gen_pool_free_owner(struct gen_pool * pool, long unsigned int addr, size_t size, void * * owner)
```

```json
{
  "name": "gen_pool_free_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584266672,
      "name": "gen_pool_free_owner",
      "external": true,
      "loc": "lib/genalloc.c:485",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_free",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:td_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584266672,
      "name": "gen_pool_free_owner",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void gen_pool_free_owner(struct gen_pool * pool, long unsigned int addr, size_t size, void * * owner)
```

```json
{
  "name": "gen_pool_free_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584372512,
      "name": "gen_pool_free_owner",
      "external": true,
      "loc": "lib/genalloc.c:485",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_process",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_free",
        "drivers/usb/core/buffer.c:hcd_buffer_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:td_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584372512,
      "name": "gen_pool_free_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void gen_pool_free_owner(struct gen_pool * pool, long unsigned int addr, size_t size, void * * owner)
```
</details>
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
