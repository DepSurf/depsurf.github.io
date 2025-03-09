# Function: <code>alloc_pages_exact</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580503856,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:3481",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "mm/page_alloc.c:alloc_large_system_hash",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_modern.c:setup_vq",
        "drivers/virtio/virtio_pci_legacy.c:setup_vq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580503856,
      "name": "alloc_pages_exact",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580586144,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:3900",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "mm/page_alloc.c:alloc_large_system_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580586144,
      "name": "alloc_pages_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580653104,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:4056",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "mm/page_alloc.c:alloc_large_system_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580653104,
      "name": "alloc_pages_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580685984,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:4343",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/page_alloc.c:alloc_large_system_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580685984,
      "name": "alloc_pages_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580768960,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:4462",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/page_alloc.c:alloc_large_system_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580768960,
      "name": "alloc_pages_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580905168,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:4594",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/page_alloc.c:alloc_large_system_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580905168,
      "name": "alloc_pages_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580979824,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:4765",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/page_alloc.c:alloc_large_system_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580979824,
      "name": "alloc_pages_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581402768,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:4934",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/page_alloc.c:alloc_large_system_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581402768,
      "name": "alloc_pages_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463760,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:4952",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/page_alloc.c:alloc_large_system_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463760,
      "name": "alloc_pages_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581670384,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:5055",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/page_alloc.c:alloc_large_system_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581670384,
      "name": "alloc_pages_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581717856,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:5234",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/page_alloc.c:alloc_large_system_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581717856,
      "name": "alloc_pages_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581738224,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:5437",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/page_alloc.c:alloc_large_system_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581738224,
      "name": "alloc_pages_exact",
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
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582015168,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:5618",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/page_alloc.c:alloc_large_system_hash",
        "drivers/block/xen-blkfront.c:setup_blkring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582015168,
      "name": "alloc_pages_exact",
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
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582441248,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:5673",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/page_alloc.c:alloc_large_system_hash",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441248,
      "name": "alloc_pages_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582935072,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:5816",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/page_alloc.c:alloc_large_system_hash",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582935072,
      "name": "alloc_pages_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583152064,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:4744",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/mm_init.c:alloc_large_system_hash",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583152064,
      "name": "alloc_pages_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583336448,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:4833",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/mm_init.c:alloc_large_system_hash",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583336448,
      "name": "alloc_pages_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492871832,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:4952",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/mmu.c:kvm_alloc_stage2_pgd",
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/page_alloc.c:alloc_large_system_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492871832,
      "name": "alloc_pages_exact",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226679772,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:4952",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/page_alloc.c:alloc_large_system_hash",
        "drivers/virtio/virtio_ring.c:vring_alloc_queue",
        "sound/core/pcm.c:snd_pcm_attach_substream",
        "sound/core/pcm.c:snd_pcm_attach_substream",
        "sound/core/memalloc.c:snd_dma_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226679772,
      "name": "alloc_pages_exact",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286264832,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:4952",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/fadump.c:fadump_setup_cpu_notes_buf",
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/page_alloc.c:alloc_large_system_hash",
        "drivers/virtio/virtio_ring.c:vring_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286264832,
      "name": "alloc_pages_exact",
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272821506,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:4952",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/page_alloc.c:alloc_large_system_hash",
        "drivers/virtio/virtio_ring.c:vring_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272821506,
      "name": "alloc_pages_exact",
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
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581432608,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:4952",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/page_alloc.c:alloc_large_system_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581432608,
      "name": "alloc_pages_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581375024,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:4952",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/page_alloc.c:alloc_large_system_hash",
        "drivers/virtio/virtio_ring.c:vring_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581375024,
      "name": "alloc_pages_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581423808,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:4952",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/page_alloc.c:alloc_large_system_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581423808,
      "name": "alloc_pages_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void * alloc_pages_exact(size_t size, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_pages_exact",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581488256,
      "name": "alloc_pages_exact",
      "external": true,
      "loc": "mm/page_alloc.c:4952",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/page_alloc.c:alloc_large_system_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581488256,
      "name": "alloc_pages_exact",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
