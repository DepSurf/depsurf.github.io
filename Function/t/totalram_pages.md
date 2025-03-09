# Function: <code>totalram_pages</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int totalram_pages()
```

```json
{
  "name": "totalram_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579183765,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579461014,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:sysctl_max_threads",
        "kernel/fork.c:fork_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604720326,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:hibernate_image_size_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580165697,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:sanity_check_segment_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580963921,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604771700,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:si_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604772931,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:swap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095945,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_parse_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581104544,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:vm_commit_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589483446,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604787414,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581300281,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581354908,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604800228,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604806828,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:files_maxfiles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582198037,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_oom_score"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604848847,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:process_init_reply",
        "fs/fuse/inode.c:process_init_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585254055,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "drivers/xen/xen-selfballoon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xen-selfballoon.c:xen_selfballoon_init",
        "drivers/xen/xen-selfballoon.c:selfballoon_process",
        "drivers/xen/xen-selfballoon.c:selfballoon_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585582850,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "drivers/char/agp/backend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/backend.c:agp_add_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587497093,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_kvzalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588557663,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:52",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580968400,
      "name": "totalram_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "totalram_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579196485,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579478742,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:sysctl_max_threads",
        "kernel/fork.c:fork_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604821093,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:hibernate_image_size_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580211786,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:sanity_check_segment_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581058061,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604868196,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:swap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581149641,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_parse_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581169608,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory",
        "mm/util.c:vm_commit_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589941565,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604883152,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581377561,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604890765,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:si_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581464508,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604903535,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604910202,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:files_maxfiles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582361765,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_oom_score"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604953662,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:process_init_reply",
        "fs/fuse/inode.c:process_init_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585803024,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "drivers/char/agp/backend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/backend.c:agp_add_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587771206,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_kvzalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588968707,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "net/ipv4/tcp_metrics.c",
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
  "name": "totalram_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579198853,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604840058,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:fork_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604855465,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:hibernate_image_size_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580260186,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:sanity_check_segment_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581113821,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604902114,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:swap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581207149,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581227544,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory",
        "mm/util.c:vm_commit_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590169117,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604917087,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581438761,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604924702,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:si_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581529516,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604937494,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604944048,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:files_maxfiles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582460597,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_oom_score"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604989188,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:process_init_reply",
        "fs/fuse/inode.c:process_init_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585945760,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "drivers/char/agp/backend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/backend.c:agp_add_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587975654,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_kvzalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589194131,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "net/ipv4/tcp_metrics.c",
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
  "name": "totalram_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579220340,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609175061,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:fork_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609185991,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:hibernate_image_size_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609194219,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "kernel/dma/pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:dma_atomic_pool_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580330770,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:sanity_check_segment_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581292278,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609223476,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:swap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581407789,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581415242,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory",
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591187326,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609231332,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581648216,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609238791,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:si_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581737547,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609251568,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609255921,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:files_maxfiles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582756341,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_oom_score"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583552204,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:set_global_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586685077,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "drivers/char/agp/backend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/backend.c:agp_backend_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588826930,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:__check_shared_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590164163,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:56",
      "file": "net/ipv4/tcp_metrics.c",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "totalram_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579214788,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612240495,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:fork_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612251634,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:hibernate_image_size_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612260671,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "kernel/dma/pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:dma_atomic_pool_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580316242,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:sanity_check_segment_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581336438,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612290605,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:swap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581436275,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581458394,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory",
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581477698,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612298464,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581694600,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612305186,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:si_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581785924,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612317852,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612322230,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:files_maxfiles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582828869,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_oom_score"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583663324,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:set_global_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586793301,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "drivers/char/agp/backend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/backend.c:agp_backend_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588843474,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:__check_shared_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590213219,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "net/ipv4/tcp_metrics.c",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "totalram_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579217252,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614380776,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:fork_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614393173,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:hibernate_image_size_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614401651,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "kernel/dma/pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:dma_atomic_pool_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580319714,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:sanity_check_segment_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581356117,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614430470,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:swap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581456675,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479242,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory",
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581498483,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614438402,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581717670,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614445414,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:si_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581812196,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614458107,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614462439,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:files_maxfiles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582857477,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_oom_score"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583684364,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:set_global_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586673701,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "drivers/char/agp/backend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/backend.c:agp_backend_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588730546,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:__check_shared_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614659082,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "net/ipv4/inetpeer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inetpeer.c:inet_initpeers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590127509,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "net/ipv4/tcp_metrics.c",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "totalram_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579255460,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615313427,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:fork_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615327472,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:hibernate_image_size_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615336841,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "kernel/dma/pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:dma_atomic_pool_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580473818,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:sanity_check_segment_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581603973,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615370364,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:swap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581711461,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581733642,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory",
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581758483,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615379363,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581989990,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615388066,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:si_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582099718,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615403025,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615408425,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:files_maxfiles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583190709,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_oom_score"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584043356,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:set_global_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587221957,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "drivers/char/agp/backend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/backend.c:agp_backend_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589420162,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:__check_shared_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615618512,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "net/ipv4/inetpeer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inetpeer.c:inet_initpeers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590905336,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:61",
      "file": "net/ipv4/tcp_metrics.c",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "totalram_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617094797,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:fork_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617110728,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:hibernate_image_size_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617121480,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "kernel/dma/pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:dma_atomic_pool_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580667594,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:sanity_check_segment_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581964101,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617158311,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:swap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582085989,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582114538,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory",
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582140259,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617168194,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582412419,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617177929,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:si_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582539627,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617195071,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617200740,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:files_maxfiles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583685669,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_oom_score"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584632998,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:set_global_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588528421,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "drivers/char/agp/backend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/backend.c:agp_backend_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590897282,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:__check_shared_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617428690,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "net/ipv4/inetpeer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inetpeer.c:inet_initpeers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592544639,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:54",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_net_metrics_init"
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
  "name": "totalram_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627754630,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:fork_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627776261,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:hibernate_image_size_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627790792,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "kernel/dma/pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:dma_atomic_pool_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580937866,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:sanity_check_segment_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582397221,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627842789,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:swap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582563653,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582588250,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory",
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627844791,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch_init",
        "mm/mm_init.c:mm_compute_batch_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627855493,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582919971,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627869092,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:si_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583055259,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627893610,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627901045,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:files_maxfiles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584295093,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_oom_score"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627926596,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:set_global_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586189224,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "security/integrity/ima/ima_kexec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589972453,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "drivers/char/agp/backend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/backend.c:agp_backend_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592593298,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:__check_shared_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628186565,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "net/ipv4/inetpeer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inetpeer.c:inet_initpeers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594403551,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:55",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_net_metrics_init"
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
  "name": "totalram_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619514374,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:fork_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619539141,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:hibernate_image_size_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619553704,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "kernel/dma/pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:dma_atomic_pool_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581024906,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:sanity_check_segment_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582603125,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619607285,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:swap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582769817,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582795610,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory",
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619621246,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_core_init",
        "mm/mm_init.c:mm_compute_batch_init",
        "mm/mm_init.c:mm_compute_batch_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582898757,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "mm/show_mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/show_mem.c:si_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619631941,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583136131,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583263738,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:shrink_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619656538,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619664101,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:files_maxfiles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584524965,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_oom_score"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619689684,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:set_global_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586426952,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "security/integrity/ima/ima_kexec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590282053,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "drivers/char/agp/backend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/backend.c:agp_backend_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593023858,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:__check_shared_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619955157,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "net/ipv4/inetpeer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inetpeer.c:inet_initpeers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594792523,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_net_metrics_init"
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
  "name": "totalram_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621811302,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:fork_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621838037,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:hibernate_image_size_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621855080,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "kernel/dma/pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/pool.c:dma_atomic_pool_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581123034,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:sanity_check_segment_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582774581,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:constrained_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621911413,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:swap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582937848,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582970330,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory",
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621925390,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_core_init",
        "mm/mm_init.c:mm_compute_batch_init",
        "mm/mm_init.c:mm_compute_batch_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583070485,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "mm/show_mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/show_mem.c:si_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621936005,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583319251,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583500101,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_store",
        "mm/zswap.c:zswap_store",
        "mm/zswap.c:shrink_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621962719,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621970245,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:files_maxfiles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584756869,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_oom_score"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621996196,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:set_global_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586692024,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "security/integrity/ima/ima_kexec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590623157,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "drivers/char/agp/backend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/backend.c:agp_backend_initialize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593775282,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:__check_shared_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622266773,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "net/ipv4/inetpeer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inetpeer.c:inet_initpeers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622269207,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:57",
      "file": "net/ipv4/tcp_metrics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_metrics.c:tcp_metrics_init"
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
  "name": "totalram_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510872556,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:fork_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491503008,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:sanity_check_segment_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492481824,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336510940380,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:swap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492590864,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492617892,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory",
        "mm/util.c:vm_commit_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503916860,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510955188,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492842372,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510963404,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:si_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492957520,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510977248,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510984880,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:files_maxfiles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494076204,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_oom_score"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511031400,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:process_init_reply",
        "fs/fuse/inode.c:process_init_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501219272,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_kvzalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502811416,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "net/ipv4/tcp_metrics.c",
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
  "name": "totalram_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243359176,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:fork_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243376488,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:hibernate_image_size_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3225484312,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:sanity_check_segment_list"
      ],
      "caller_func": []
    },
    {
      "addr": 3226358384,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243430020,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:swap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 3226443356,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 3226468912,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory",
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 3243435208,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243446060,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3226649232,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3243449932,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:si_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 3226739324,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 3243464600,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:files_maxfiles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3227529112,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_oom_score"
      ],
      "caller_func": []
    },
    {
      "addr": 3243512364,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:process_init_reply",
        "fs/fuse/inode.c:process_init_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 3233719768,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_kvzalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3235514412,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "net/ipv4/tcp_metrics.c",
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
  "name": "totalram_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302501816,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:fork_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284462824,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:sanity_check_segment_list"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285767096,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055302587640,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:swap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285899388,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285935088,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory",
        "mm/util.c:vm_commit_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297811000,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302606320,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286231020,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302616680,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:si_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286369028,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302634540,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302642360,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:files_maxfiles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287738388,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_oom_score"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302702668,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:process_init_reply",
        "fs/fuse/inode.c:process_init_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289734228,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "security/integrity/ima/ima_kexec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291937164,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "drivers/char/agp/backend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/backend.c:agp_add_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294744568,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_kvzalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296458892,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "net/ipv4/tcp_metrics.c",
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
  "name": "totalram_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270615204,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:fork_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272549662,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936270670388,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:swap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272626698,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272643258,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory",
        "mm/util.c:vm_commit_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270674610,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270683676,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272794332,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270690268,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:si_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272870278,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270705244,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:files_maxfiles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273570480,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_oom_score"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270744342,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:process_init_reply",
        "fs/fuse/inode.c:process_init_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277915280,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_kvzalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278928328,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "net/ipv4/tcp_metrics.c",
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
  "name": "totalram_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579197701,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604745325,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:fork_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580228986,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:sanity_check_segment_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581082669,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604807571,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:swap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581175997,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581196392,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory",
        "mm/util.c:vm_commit_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589771405,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604822547,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581407609,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604830162,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:si_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581498252,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604842954,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604849508,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:files_maxfiles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582429333,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_oom_score"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604894648,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:process_init_reply",
        "fs/fuse/inode.c:process_init_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585706736,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "drivers/char/agp/backend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/backend.c:agp_add_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587606630,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_kvzalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588800515,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "net/ipv4/tcp_metrics.c",
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
  "name": "totalram_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579132693,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604712942,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:fork_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604728364,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:hibernate_image_size_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580176474,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:sanity_check_segment_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581029853,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604776635,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:swap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581122813,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581143144,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory",
        "mm/util.c:vm_commit_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589494228,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604791608,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581350121,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604799223,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:si_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440492,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604812015,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604818560,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:files_maxfiles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582366501,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_oom_score"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604863700,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:process_init_reply",
        "fs/fuse/inode.c:process_init_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585565936,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "drivers/char/agp/backend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/backend.c:agp_add_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587374662,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_kvzalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588512451,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "net/ipv4/tcp_metrics.c",
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
  "name": "totalram_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579198773,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604822892,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:fork_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604838109,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:hibernate_image_size_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580220458,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:sanity_check_segment_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581073869,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604884758,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:swap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581167197,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581187592,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory",
        "mm/util.c:vm_commit_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590214813,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604899731,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581398809,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604907346,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:si_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581489564,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604920138,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604926692,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:files_maxfiles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582419813,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_oom_score"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604971832,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:process_init_reply",
        "fs/fuse/inode.c:process_init_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585895776,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "drivers/char/agp/backend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/backend.c:agp_add_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587931798,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_kvzalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588940005,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "net/netfilter/nf_conntrack_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_core.c:nf_conntrack_init_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589236691,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "net/ipv4/tcp_metrics.c",
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
  "name": "totalram_pages",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579204229,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604844215,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:fork_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604859535,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:hibernate_image_size_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580273290,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:sanity_check_segment_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581135597,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604906295,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:swap_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581222157,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_show_options",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581250840,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory",
        "mm/util.c:vm_commit_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590265181,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_compute_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604921268,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581462825,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604928883,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mem_init_print_info",
        "mm/page_alloc.c:si_meminfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581554364,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604941665,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604948219,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:files_maxfiles_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582499301,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_oom_score"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604993358,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:process_init_reply",
        "fs/fuse/inode.c:process_init_reply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586003760,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "drivers/char/agp/backend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/backend.c:agp_add_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588044463,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_kvzalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589276979,
      "name": "totalram_pages",
      "external": false,
      "loc": "include/linux/mm.h:53",
      "file": "net/ipv4/tcp_metrics.c",
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
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
long unsigned int totalram_pages()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
long unsigned int totalram_pages()
```
</details>
</li>
</ul>
