# Function: <code>clear_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clear_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/mm/init.c:alloc_low_pages",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/swap.c:swsusp_check",
        "kernel/kexec_core.c:kimage_load_segment",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/huge_memory.c:khugepaged",
        "fs/libfs.c:simple_readpage",
        "fs/dax.c:__dax_fault",
        "fs/dax.c:__dax_fault",
        "fs/dax.c:dax_do_io",
        "fs/dax.c:dax_do_io",
        "fs/dax.c:dax_zero_page_range",
        "fs/dax.c:dax_clear_blocks",
        "fs/fuse/dev.c:fuse_copy_page",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582997824,
      "name": "clear_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
  "name": "clear_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clear_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel",
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "arch/x86/mm/init.c:alloc_low_pages",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/swap.c:swsusp_check",
        "kernel/kexec_core.c:kimage_load_segment",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:wp_page_copy",
        "mm/khugepaged.c:collapse_huge_page",
        "fs/libfs.c:simple_readpage",
        "fs/dax.c:dax_fault",
        "fs/fuse/dev.c:fuse_copy_page",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/block/brd.c:brd_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583287504,
      "name": "clear_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clear_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel",
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "arch/x86/mm/init.c:alloc_low_pages",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/swap.c:swsusp_check",
        "kernel/kexec_core.c:kimage_load_segment",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:wp_page_copy",
        "mm/khugepaged.c:khugepaged",
        "fs/libfs.c:simple_readpage",
        "fs/dax.c:dax_iomap_fault",
        "fs/fuse/dev.c:fuse_copy_page",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/events/events_fifo.c:init_control_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583406256,
      "name": "clear_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clear_page(void * page)
```

```json
{
  "name": "clear_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596266266,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:42",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578995323,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:42",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579230150,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:42",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588275107,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:42",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:alloc_low_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579748613,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:42",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579761020,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:42",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580017294,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:42",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580689897,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:42",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580781838,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:42",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580912099,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:42",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581173342,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:42",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581454914,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:42",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581643982,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:42",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582438690,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:42",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584444277,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:42",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584463908,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:42",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578995323,
      "name": "clear_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clear_page(void * page)
```

```json
{
  "name": "clear_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602582792,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:43",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578958765,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:43",
      "file": "arch/x86/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_save_time_memory_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578998299,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:43",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579245710,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:43",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588840659,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:43",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:alloc_low_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579781925,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:43",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_read_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579794444,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:43",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580064382,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:43",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580774497,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:43",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580868439,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:43",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581011085,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:43",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581309745,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:43",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596898,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:43",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581789716,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:43",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582588055,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:43",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584853891,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:43",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584874308,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:43",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578998299,
      "name": "clear_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clear_page(void * page)
```

```json
{
  "name": "clear_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602750697,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578961265,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_save_time_memory_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579001692,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579258177,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589219937,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:alloc_low_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579813547,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579824211,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580121026,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580910816,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581004761,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581144747,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581451405,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581754793,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581963803,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582780592,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585084954,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585105250,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579001692,
      "name": "clear_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clear_page(void * page)
```

```json
{
  "name": "clear_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604544756,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578960032,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_save_time_memory_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579000588,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579281841,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589462062,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:alloc_low_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579860299,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579870947,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580168034,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580985559,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581080587,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581224571,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531092,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581841321,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582046140,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582883856,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582949121,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585189157,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585195673,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585215410,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586329007,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579000588,
      "name": "clear_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clear_page(void * page)
```

```json
{
  "name": "clear_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604638849,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578966800,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_save_time_memory_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579008012,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579297487,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589922750,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:alloc_low_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579894601,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579905373,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580213936,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581144180,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581298233,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581390042,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581641837,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581965881,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582210525,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583064767,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583129739,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585405384,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585408030,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585428130,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586579966,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579008012,
      "name": "clear_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604651137,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578969264,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_save_time_memory_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604695682,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579303039,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590148926,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:alloc_low_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579944873,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579955629,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580262336,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201716,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581357001,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581450266,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581712958,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582038633,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582291421,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583174175,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583235677,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585542104,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585548775,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585568578,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586727311,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
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
  "name": "clear_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609001302,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578978656,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_save_time_memory_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609041445,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:check_pt_base",
        "arch/x86/xen/mmu_pv.c:check_pt_base",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579332849,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591167569,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:alloc_low_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579990538,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580001181,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swap_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580329964,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_normal_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581388150,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581554599,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581655885,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581931382,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582275993,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582574767,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583497905,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583563434,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586264332,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586268519,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586288978,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587513215,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_unmap_cmnd"
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
  "name": "clear_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612065260,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578981280,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_save_time_memory_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612104803,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:check_pt_base",
        "arch/x86/xen/mmu_pv.c:check_pt_base",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334433,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591663313,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:alloc_low_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579975242,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:clear_or_poison_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579983341,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swap_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580315436,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_normal_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581431836,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581599383,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581704038,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581981899,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582326761,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582646285,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583606606,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583675783,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586382844,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586384967,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586408194,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587579544,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_unmap_cmnd"
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
  "name": "clear_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614203372,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578990402,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_save_time_memory_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614249818,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337137,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591607153,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:alloc_low_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579977559,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579985117,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swap_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580318924,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_normal_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581451900,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622232,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581725705,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582010945,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354681,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582676387,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583629853,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583696791,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586267036,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586269139,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586292050,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587463736,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_unmap_cmnd"
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
  "name": "clear_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615121087,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579007458,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_save_time_memory_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615170241,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392449,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592780364,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:alloc_low_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580108951,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580116882,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swap_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580472812,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_normal_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581706380,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581889624,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581996412,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582313428,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582409618,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/secretmem.c:secretmem_freepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582675801,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582993669,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583988945,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584056933,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586777559,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586780691,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586809729,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588041074,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
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
  "name": "clear_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071616882479,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:48",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579024826,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:48",
      "file": "arch/x86/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_save_time_memory_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616936470,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:48",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458977,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:48",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594678364,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:48",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:alloc_low_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580248647,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:48",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580257385,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:48",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swap_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580666562,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:48",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_normal_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582088994,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:48",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582287401,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:48",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582452216,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:48",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582799926,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:48",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583463560,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:48",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584571603,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:48",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584647714,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:48",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588059156,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:48",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588061385,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:48",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588092492,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:48",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589403710,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:48",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
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
  "name": "clear_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627470901,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:50",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579053174,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:50",
      "file": "arch/x86/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_save_time_memory_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627542492,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:50",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579548161,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:50",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596413996,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:50",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:alloc_low_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580448407,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:50",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580462537,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:50",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swap_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580936788,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:50",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_normal_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582567666,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:50",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_get_folio_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582780217,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:50",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582961274,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:50",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583342993,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:50",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584055112,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:50",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585247697,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:50",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585328866,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:50",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589438959,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:50",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589440649,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:50",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589476412,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:50",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590977289,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:50",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
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
  "name": "clear_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579053078,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "arch/x86/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_save_time_memory_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619288666,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619300078,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579563457,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596953852,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:alloc_low_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580518439,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580534052,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swap_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581023828,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_normal_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582789681,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_get_folio_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582996650,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:__wp_page_copy_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583178168,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:free_unref_page_prepare",
        "mm/page_alloc.c:__free_pages_ok"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583562774,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584280904,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585477441,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585558853,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589737583,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589740089,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589776624,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591317226,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_set_special_bvec"
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
  "name": "clear_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579078406,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "arch/x86/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_save_time_memory_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621581162,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621593566,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579590993,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597881372,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:alloc_low_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580579501,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580595871,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_check",
        "kernel/power/swap.c:swap_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581121956,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_normal_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582964554,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_get_folio_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583167882,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:__wp_page_copy_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583362026,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:free_unref_page_prepare",
        "mm/page_alloc.c:__free_pages_ok"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583751456,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584497704,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585712465,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585797266,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590075535,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590078073,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590112704,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591665738,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:46",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_set_special_bvec"
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
  "name": "clear_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clear_page",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/copypage.c:__cpu_clear_user_page",
        "virt/kvm/arm/mmu.c:free_hyp_pgds",
        "kernel/kexec_core.c:kimage_load_segment",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/memory.c:wp_page_copy",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "fs/libfs.c:simple_readpage",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/readdir.c:fuse_emit",
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503795516,
      "name": "clear_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "clear_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282716864,
      "name": "clear_page",
      "external": false,
      "loc": "arch/powerpc/include/asm/page_64.h:43",
      "file": "arch/powerpc/mm/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/mem.c:clear_user_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284465524,
      "name": "clear_page",
      "external": false,
      "loc": "arch/powerpc/include/asm/page_64.h:43",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285903212,
      "name": "clear_page",
      "external": false,
      "loc": "arch/powerpc/include/asm/page_64.h:43",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286080080,
      "name": "clear_page",
      "external": false,
      "loc": "arch/powerpc/include/asm/page_64.h:43",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286248044,
      "name": "clear_page",
      "external": false,
      "loc": "arch/powerpc/include/asm/page_64.h:43",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286656616,
      "name": "clear_page",
      "external": false,
      "loc": "arch/powerpc/include/asm/page_64.h:43",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287140408,
      "name": "clear_page",
      "external": false,
      "loc": "arch/powerpc/include/asm/page_64.h:43",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288752024,
      "name": "clear_page",
      "external": false,
      "loc": "arch/powerpc/include/asm/page_64.h:43",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288835792,
      "name": "clear_page",
      "external": false,
      "loc": "arch/powerpc/include/asm/page_64.h:43",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292958600,
      "name": "clear_page",
      "external": false,
      "loc": "arch/powerpc/include/asm/page_64.h:43",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604577409,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578969280,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_save_time_memory_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604621963,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298847,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589751214,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:alloc_low_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579912649,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579924301,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580231136,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581170564,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581325849,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581419114,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581681694,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582007369,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582260157,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583142911,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583204413,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585304136,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585310807,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585330610,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586417791,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
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
  "name": "clear_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604569125,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233473,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589475438,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:alloc_low_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579851881,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579862637,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580178624,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581117380,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581269609,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361626,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620358,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581944937,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582196913,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583080063,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583141565,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586294047,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
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
  "name": "clear_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604655233,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578969200,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_save_time_memory_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604699778,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579300047,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590194622,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:alloc_low_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579905145,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579915901,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580222608,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581161764,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581317049,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581410314,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673006,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581998649,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582250637,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583126943,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583188445,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585492504,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585499175,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585518978,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586681871,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
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
  "name": "clear_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604655233,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578969812,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_save_time_memory_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604699784,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308879,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590245054,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:alloc_low_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579951209,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579961949,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:swsusp_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580275402,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581228010,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581380980,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581475408,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740244,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582069587,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582330971,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583220527,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583282949,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585600511,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585607214,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585627026,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:init_control_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586787894,
      "name": "clear_page",
      "external": false,
      "loc": "arch/x86/include/asm/page_64.h:47",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void clear_page(void * page)
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
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
void clear_page(void * page)
```
</details>
</li>
</ul>
