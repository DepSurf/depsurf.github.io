# Function: <code>vunmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580741248,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:1533",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/relay.c:relay_destroy_buf",
        "mm/vmalloc.c:vmap",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/base/dma-mapping.c:dma_common_pages_remap",
        "drivers/base/dma-mapping.c:dma_common_free_remap",
        "drivers/base/firmware_class.c:__fw_free_buf",
        "drivers/base/firmware_class.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580741248,
      "name": "vunmap",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580860432,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:1554",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/relay.c:relay_destroy_buf",
        "mm/vmalloc.c:vmap",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/base/dma-mapping.c:dma_common_free_remap",
        "drivers/base/dma-mapping.c:dma_common_pages_remap",
        "drivers/base/firmware_class.c:firmware_loading_store",
        "drivers/base/firmware_class.c:__fw_free_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860432,
      "name": "vunmap",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580930640,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:1569",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/relay.c:relay_destroy_buf",
        "mm/vmalloc.c:vmap",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/base/dma-mapping.c:dma_common_free_remap",
        "drivers/base/dma-mapping.c:dma_common_pages_remap",
        "drivers/base/firmware_class.c:firmware_loading_store",
        "drivers/base/firmware_class.c:__fw_free_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580930640,
      "name": "vunmap",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580974896,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:1621",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "mm/vmalloc.c:vmap",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/base/dma-mapping.c:dma_common_free_remap",
        "drivers/base/dma-mapping.c:dma_common_contiguous_remap",
        "drivers/base/dma-mapping.c:dma_common_pages_remap",
        "drivers/base/firmware_class.c:firmware_loading_store",
        "drivers/base/firmware_class.c:fw_free_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580974896,
      "name": "vunmap",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581077520,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:1619",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "mm/vmalloc.c:vmap",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/base/dma-mapping.c:dma_common_free_remap",
        "drivers/base/dma-mapping.c:dma_common_contiguous_remap",
        "drivers/base/dma-mapping.c:dma_common_pages_remap",
        "drivers/base/firmware_class.c:firmware_loading_store",
        "drivers/base/firmware_class.c:__fw_free_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077520,
      "name": "vunmap",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581216448,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:1606",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_common_free_remap",
        "kernel/dma/mapping.c:dma_common_contiguous_remap",
        "kernel/dma/mapping.c:dma_common_pages_remap",
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "mm/vmalloc.c:vmap",
        "security/keys/big_key.c:big_key_free_buffer",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581216448,
      "name": "vunmap",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581300176,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:1612",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "mm/vmalloc.c:vmap",
        "security/keys/big_key.c:big_key_free_buffer",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581300176,
      "name": "vunmap",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581374480,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:2344",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "mm/vmalloc.c:vmap",
        "security/keys/big_key.c:big_key_free_buffer",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581374480,
      "name": "vunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581435728,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:2350",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "mm/vmalloc.c:vmap",
        "security/keys/big_key.c:big_key_free_buffer",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581435728,
      "name": "vunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581646848,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:2397",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "kernel/bpf/ringbuf.c:ringbuf_map_free",
        "mm/vmalloc.c:vmap",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/base/firmware_loader/main.c:fw_decompress_xz_pages",
        "drivers/dma-buf/heaps/heap-helpers.c:dma_heap_dma_buf_vunmap",
        "drivers/dma-buf/heaps/heap-helpers.c:dma_heap_dma_buf_release",
        "net/xdp/xsk_buff_pool.c:xp_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581646848,
      "name": "vunmap",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581693376,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:2379",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "kernel/bpf/ringbuf.c:ringbuf_map_free",
        "mm/vmalloc.c:vmap",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/base/firmware_loader/main.c:fw_decompress_xz_pages",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_vunmap",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581693376,
      "name": "vunmap",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581716112,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:2661",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_vunmap_noncontiguous",
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "kernel/bpf/ringbuf.c:ringbuf_map_free",
        "mm/vmalloc.c:vmap",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/base/firmware_loader/main.c:fw_decompress_xz",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_vunmap",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716112,
      "name": "vunmap",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581988352,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:2714",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_vunmap_noncontiguous",
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "kernel/bpf/ringbuf.c:ringbuf_map_free",
        "mm/vmalloc.c:vmap",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/base/firmware_loader/main.c:fw_decompress_xz",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_vunmap",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581988352,
      "name": "vunmap",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582410576,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:2758",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/ivm.c:hv_unmap_memory",
        "kernel/dma/mapping.c:dma_vunmap_noncontiguous",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/remap.c:dma_common_free_remap",
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "kernel/bpf/ringbuf.c:ringbuf_map_free",
        "mm/vmalloc.c:vmap",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/base/firmware_loader/main.c:fw_map_paged_buf",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_vunmap",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582410576,
      "name": "vunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582917536,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:2820",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/ivm.c:hv_unmap_memory",
        "kernel/dma/mapping.c:dma_vunmap_noncontiguous",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/remap.c:dma_common_free_remap",
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "kernel/bpf/ringbuf.c:ringbuf_map_free",
        "mm/vmalloc.c:vmap",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/base/firmware_loader/main.c:fw_map_paged_buf",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_vunmap",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582917536,
      "name": "vunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583132688,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:2861",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_vunmap_noncontiguous",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/remap.c:dma_common_free_remap",
        "kernel/module/decompress.c:module_decompress_cleanup",
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "kernel/bpf/ringbuf.c:ringbuf_map_free",
        "mm/vmalloc.c:vmap",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/base/firmware_loader/main.c:fw_map_paged_buf",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_vunmap",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583132688,
      "name": "vunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583315680,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:2861",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_vunmap_noncontiguous",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/remap.c:dma_common_free_remap",
        "kernel/module/decompress.c:module_decompress_cleanup",
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "kernel/bpf/ringbuf.c:ringbuf_map_free",
        "mm/vmalloc.c:vmap",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm",
        "drivers/base/firmware_loader/main.c:fw_map_paged_buf",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_vunmap",
        "drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_vunmap",
        "net/xdp/xdp_umem.c:xdp_put_umem",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583315680,
      "name": "vunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492839112,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:2350",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/ioremap.c:iounmap",
        "arch/arm64/mm/ioremap.c:__ioremap_caller",
        "kernel/dma/remap.c:arch_dma_free",
        "kernel/dma/remap.c:__dma_common_pages_remap",
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "mm/vmalloc.c:vmap",
        "security/keys/big_key.c:big_key_free_buffer",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492839112,
      "name": "vunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226642732,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:2350",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/fault-armv.c:check_writebuffer_bugs",
        "arch/arm/mm/fault-armv.c:check_writebuffer_bugs",
        "arch/arm/mm/ioremap.c:__iounmap",
        "arch/arm/mm/ioremap.c:__arm_ioremap_pfn_caller",
        "kernel/dma/remap.c:dma_common_free_remap",
        "kernel/dma/remap.c:__dma_common_pages_remap",
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "mm/vmalloc.c:vmap",
        "fs/pstore/ram_core.c:persistent_ram_free",
        "security/keys/big_key.c:big_key_free_buffer",
        "net/xdp/xdp_umem.c:xdp_umem_unmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226642732,
      "name": "vunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286227232,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:2350",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci_64.c:pcibios_unmap_io_space",
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "mm/vmalloc.c:vmap",
        "security/keys/big_key.c:big_key_free_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286227232,
      "name": "vunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272791696,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:2350",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/mm/ioremap.c:iounmap",
        "kernel/relay.c:relay_destroy_buf",
        "mm/vmalloc.c:vmap",
        "security/keys/big_key.c:big_key_free_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272791696,
      "name": "vunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581404576,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:2350",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "mm/vmalloc.c:vmap",
        "security/keys/big_key.c:big_key_free_buffer",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581404576,
      "name": "vunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581347088,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:2350",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "mm/vmalloc.c:vmap",
        "security/keys/big_key.c:big_key_free_buffer",
        "drivers/hv/ring_buffer.c:hv_ringbuffer_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581347088,
      "name": "vunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581395776,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:2350",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "mm/vmalloc.c:vmap",
        "security/keys/big_key.c:big_key_free_buffer",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm",
        "drivers/base/firmware_loader/main.c:fw_map_paged_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395776,
      "name": "vunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void vunmap(const void * addr)
```

```json
{
  "name": "vunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581459760,
      "name": "vunmap",
      "external": true,
      "loc": "mm/vmalloc.c:2350",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_free",
        "kernel/relay.c:relay_destroy_buf",
        "mm/vmalloc.c:vmap",
        "security/keys/big_key.c:big_key_free_buffer",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459760,
      "name": "vunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
