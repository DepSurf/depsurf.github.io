# Function: <code>vmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580741312,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:1552",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:xen_pvh_gnttab_setup",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/base/firmware_class.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580741312,
      "name": "vmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580860496,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:1573",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages",
        "drivers/base/firmware_class.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860496,
      "name": "vmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580930704,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:1588",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages",
        "drivers/base/firmware_class.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580930704,
      "name": "vmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580974960,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:1640",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages",
        "drivers/base/firmware_class.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580974960,
      "name": "vmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581077584,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:1638",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages",
        "drivers/base/firmware_class.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077584,
      "name": "vmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581216512,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:1625",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581216512,
      "name": "vmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581300240,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:1631",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581300240,
      "name": "vmap",
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581377520,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:2365",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581377520,
      "name": "vmap",
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581438720,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:2371",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581438720,
      "name": "vmap",
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581646912,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:2418",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq_64.c:map_irq_stack",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages",
        "drivers/base/firmware_loader/main.c:fw_decompress_xz_pages",
        "drivers/dma-buf/heaps/heap-helpers.c:dma_heap_dma_buf_vmap",
        "net/xdp/xsk_buff_pool.c:xp_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581646912,
      "name": "vmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581693440,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:2403",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq_64.c:map_irq_stack",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages",
        "drivers/base/firmware_loader/main.c:fw_decompress_xz_pages",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_do_vmap",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581693440,
      "name": "vmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581716176,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:2685",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack",
        "kernel/dma/mapping.c:dma_vmap_noncontiguous",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/relay.c:relay_create_buf",
        "kernel/relay.c:relay_create_buf",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages",
        "drivers/base/firmware_loader/main.c:fw_decompress_xz",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_vmap",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716176,
      "name": "vmap",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581988416,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:2738",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack",
        "kernel/dma/mapping.c:dma_vmap_noncontiguous",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/relay.c:relay_create_buf",
        "kernel/relay.c:relay_create_buf",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages",
        "drivers/base/firmware_loader/main.c:fw_decompress_xz",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_vmap",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581988416,
      "name": "vmap",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582410656,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:2782",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack",
        "kernel/dma/mapping.c:dma_vmap_noncontiguous",
        "kernel/dma/remap.c:dma_common_contiguous_remap",
        "kernel/dma/remap.c:dma_common_pages_remap",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages",
        "drivers/base/firmware_loader/main.c:fw_map_paged_buf",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_vmap",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582410656,
      "name": "vmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582917632,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:2844",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack",
        "kernel/dma/mapping.c:dma_vmap_noncontiguous",
        "kernel/dma/remap.c:dma_common_contiguous_remap",
        "kernel/dma/remap.c:dma_common_pages_remap",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages",
        "drivers/base/firmware_loader/main.c:fw_map_paged_buf",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_vmap",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582917632,
      "name": "vmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583132800,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:2895",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack",
        "kernel/dma/mapping.c:dma_vmap_noncontiguous",
        "kernel/dma/remap.c:dma_common_contiguous_remap",
        "kernel/dma/remap.c:dma_common_pages_remap",
        "kernel/module/decompress.c:module_decompress",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages",
        "drivers/base/firmware_loader/main.c:fw_map_paged_buf",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_vmap",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583132800,
      "name": "vmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583315792,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:2895",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack",
        "kernel/dma/mapping.c:dma_vmap_noncontiguous",
        "kernel/dma/remap.c:dma_common_contiguous_remap",
        "kernel/dma/remap.c:dma_common_pages_remap",
        "kernel/module/decompress.c:module_decompress",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_alloc",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages",
        "drivers/base/firmware_loader/main.c:fw_map_paged_buf",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_vmap",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_vmap",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583315792,
      "name": "vmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492842312,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:2371",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492842312,
      "name": "vmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226649188,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:2371",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/fault-armv.c:check_writebuffer_bugs",
        "arch/arm/mm/fault-armv.c:check_writebuffer_bugs",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "fs/pstore/ram_core.c:persistent_ram_new",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226649188,
      "name": "vmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286230944,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:2371",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "security/keys/big_key.c:big_key_alloc_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286230944,
      "name": "vmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272794282,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:2371",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/big_key.c:big_key_alloc_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272794282,
      "name": "vmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581407568,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:2371",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581407568,
      "name": "vmap",
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581350080,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:2371",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "drivers/hv/ring_buffer.c:hv_ringbuffer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581350080,
      "name": "vmap",
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581398768,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:2371",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages",
        "drivers/base/firmware_loader/main.c:fw_map_paged_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581398768,
      "name": "vmap",
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
void * vmap(struct page * * pages, unsigned int count, long unsigned int flags, pgprot_t prot)
```

```json
{
  "name": "vmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581462800,
      "name": "vmap",
      "external": true,
      "loc": "mm/vmalloc.c:2371",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq_64.c:irq_init_percpu_irqstack",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "security/keys/big_key.c:big_key_alloc_buffer",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581462800,
      "name": "vmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
