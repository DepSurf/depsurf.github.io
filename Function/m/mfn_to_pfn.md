# Function: <code>mfn_to_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```

```json
{
  "name": "mfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594974397,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_memory_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970128,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:m2v",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages"
      ],
      "caller_func": [
        "arch/x86/xen/mmu.c:m2v",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages"
      ]
    },
    {
      "addr": 18446744071578992319,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578996241,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579023629,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583876256,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586136707,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071583909842,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584084839,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_pv_console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578970128,
      "name": "mfn_to_pfn.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    },
    {
      "addr": 18446744071586136707,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```

```json
{
  "name": "mfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595134858,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595139208,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:m2v",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages"
      ],
      "caller_func": [
        "arch/x86/xen/mmu.c:m2v",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages"
      ]
    },
    {
      "addr": 18446744071578988895,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578992961,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579020454,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584207332,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586550496,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071584244087,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584415178,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967088,
      "name": "mfn_to_pfn.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 18446744071586550496,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```

```json
{
  "name": "mfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595377534,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595381890,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:m2v",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages"
      ],
      "caller_func": [
        "arch/x86/xen/mmu.c:m2v",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages"
      ]
    },
    {
      "addr": 18446744071578990767,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend",
        "arch/x86/xen/suspend.c:xen_arch_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578994801,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579020880,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584388916,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586732122,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071584425607,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584598394,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:153",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578968864,
      "name": "mfn_to_pfn.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 18446744071586732122,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```

```json
{
  "name": "mfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596294629,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:179",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578963399,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:179",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578966526,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:179",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596303073,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:179",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:m2v",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:m2v",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ]
    },
    {
      "addr": 18446744071579014644,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:179",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584470547,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:179",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584484741,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:179",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071584509527,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:179",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584680510,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:179",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578977520,
      "name": "mfn_to_pfn.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446744071584484741,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```

```json
{
  "name": "mfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602612419,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:186",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578966647,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:186",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578969733,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:186",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602620856,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:186",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:m2v",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:m2v",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ]
    },
    {
      "addr": 18446744071579015218,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:186",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584880931,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:186",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584895077,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:186",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071584919559,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:186",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585093406,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:186",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578980832,
      "name": "mfn_to_pfn.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    },
    {
      "addr": 18446744071584895077,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```

```json
{
  "name": "mfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602780717,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:186",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578969321,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:186",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578972654,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:186",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602789205,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:186",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ]
    },
    {
      "addr": 18446744071579017839,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:186",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585110451,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:186",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585126102,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:186",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071585151076,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:186",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585326270,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:186",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578983616,
      "name": "mfn_to_pfn.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071585126102,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```

```json
{
  "name": "mfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604574921,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578967416,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970787,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604583419,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ]
    },
    {
      "addr": 18446744071579019455,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585221235,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585236918,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071585261944,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585449726,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578981616,
      "name": "mfn_to_pfn.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071585236918,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```

```json
{
  "name": "mfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604670067,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578974487,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977795,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604678716,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ]
    },
    {
      "addr": 18446744071579027216,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585433427,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585449079,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071585469351,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585665550,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578988640,
      "name": "mfn_to_pfn.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071585449079,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```

```json
{
  "name": "mfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604682559,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578976887,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980195,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604691183,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ]
    },
    {
      "addr": 18446744071579029472,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585573875,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585589511,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071585609607,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585806526,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578991008,
      "name": "mfn_to_pfn.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071585589511,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```

```json
{
  "name": "mfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609033970,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578986695,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578990423,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609042325,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ]
    },
    {
      "addr": 18446744071579037543,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586295363,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586311252,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071586332507,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586536766,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579001216,
      "name": "mfn_to_pfn.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071586311252,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```

```json
{
  "name": "mfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612097376,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578988183,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578991911,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612105681,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ]
    },
    {
      "addr": 18446744071579041143,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586414515,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591450192,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071586448831,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586647982,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579003024,
      "name": "mfn_to_pfn.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071591450192,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```

```json
{
  "name": "mfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614236922,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578997175,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579002656,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591186190,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ]
    },
    {
      "addr": 18446744071579043972,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586297955,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591391946,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071586333121,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586531950,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591186190,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071591391946,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```

```json
{
  "name": "mfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615156620,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579014855,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579020336,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592048508,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ]
    },
    {
      "addr": 18446744071579064123,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586778912,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_add_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586817171,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592436169,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071586852935,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587070254,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:212",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592048508,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071592436169,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```

```json
{
  "name": "mfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616922035,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579033664,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ]
    },
    {
      "addr": 18446744071579035392,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ]
    },
    {
      "addr": 18446744071579048704,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_p4d_val",
        "arch/x86/xen/mmu_pv.c:xen_pud_val",
        "arch/x86/xen/mmu_pv.c:xen_pmd_val",
        "arch/x86/xen/mmu_pv.c:xen_pgd_val",
        "arch/x86/xen/mmu_pv.c:xen_pte_val",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ]
    },
    {
      "addr": 18446744071579088233,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588058515,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_add_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588101632,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ]
    },
    {
      "addr": 18446744071594304170,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071588138576,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ]
    },
    {
      "addr": 18446744071588373974,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033664,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071579035392,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071579048704,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071588101632,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071594304170,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071588138576,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```

```json
{
  "name": "mfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627523412,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579063360,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ]
    },
    {
      "addr": 18446744071579065424,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ]
    },
    {
      "addr": 18446744071579079584,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_p4d_val",
        "arch/x86/xen/mmu_pv.c:xen_pud_val",
        "arch/x86/xen/mmu_pv.c:xen_pmd_val",
        "arch/x86/xen/mmu_pv.c:xen_pgd_val",
        "arch/x86/xen/mmu_pv.c:xen_pte_val",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ]
    },
    {
      "addr": 18446744071579123001,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589438528,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_add_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589486608,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ]
    },
    {
      "addr": 18446744071589504672,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071589528192,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ]
    },
    {
      "addr": 18446744071589797958,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579063360,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071579065424,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071579079584,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071589486608,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071589504672,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071589528192,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```

```json
{
  "name": "mfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619268653,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579063232,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ]
    },
    {
      "addr": 18446744071579065296,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ]
    },
    {
      "addr": 18446744071579079392,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_p4d_val",
        "arch/x86/xen/mmu_pv.c:xen_pud_val",
        "arch/x86/xen/mmu_pv.c:xen_pmd_val",
        "arch/x86/xen/mmu_pv.c:xen_pgd_val",
        "arch/x86/xen/mmu_pv.c:xen_pte_val",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ]
    },
    {
      "addr": 18446744071579123277,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589738574,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_add_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589787072,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ]
    },
    {
      "addr": 18446744071589805648,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071589829264,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ]
    },
    {
      "addr": 18446744071590103309,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579063232,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071579065296,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071579079392,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071589787072,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071589805648,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071589829264,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```

```json
{
  "name": "mfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621561325,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579088320,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ]
    },
    {
      "addr": 18446744071579089872,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ]
    },
    {
      "addr": 18446744071579105168,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_p4d_val",
        "arch/x86/xen/mmu_pv.c:xen_pud_val",
        "arch/x86/xen/mmu_pv.c:xen_pmd_val",
        "arch/x86/xen/mmu_pv.c:xen_pgd_val",
        "arch/x86/xen/mmu_pv.c:xen_pte_val",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ]
    },
    {
      "addr": 18446744071579149180,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590076570,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_add_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590123200,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ]
    },
    {
      "addr": 18446744071590141872,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071590166272,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ]
    },
    {
      "addr": 18446744071590442701,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:204",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579088320,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071579089872,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071579105168,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071590123200,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071590141872,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071590166272,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```

```json
{
  "name": "mfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604608869,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977239,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980547,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604617464,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ]
    },
    {
      "addr": 18446744071579029824,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585335907,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585351965,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071585371255,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585567518,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578991360,
      "name": "mfn_to_pfn.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071585351965,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```

```json
{
  "name": "mfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604686655,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578976823,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980131,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604695279,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ]
    },
    {
      "addr": 18446744071579029408,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585524275,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585539911,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071585560007,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585756926,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578990944,
      "name": "mfn_to_pfn.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071585539911,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```

```json
{
  "name": "mfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604686611,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977415,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/suspend_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend",
        "arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980723,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604695235,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:m2p",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages"
      ]
    },
    {
      "addr": 18446744071579032976,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585633651,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585647895,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071585667975,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer",
        "drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585865758,
      "name": "mfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:213",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578992144,
      "name": "mfn_to_pfn.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071585647895,
      "name": "mfn_to_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
long unsigned int mfn_to_pfn(long unsigned int mfn)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
