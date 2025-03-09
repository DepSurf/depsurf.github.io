# Function: <code>vm_unacct_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579368410,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580581839,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:shmem_recalc_inode",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580699178,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__vm_enough_memory",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580716606,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580720276,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_vma",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580769525,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SyS_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580776811,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579373625,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580676144,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580700465,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580820798,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580832063,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580836574,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580892604,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SyS_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580900027,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
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
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579392575,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580740752,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580766273,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580886286,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897683,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580902846,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580961004,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SyS_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580968427,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
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
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579381938,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580798209,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mcopy_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580802705,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580931254,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580942250,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580948437,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581007772,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SyS_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581015420,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:28",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
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
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579406857,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580871997,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580891409,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581030961,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581042506,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581049237,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581120346,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SYSC_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581124425,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
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
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579417532,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581005909,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581027383,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581165682,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581180385,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581186223,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581256100,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581266441,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
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
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579457129,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581084089,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581104915,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245762,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581262673,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581269013,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581339345,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581349545,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
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
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579466164,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147066,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581169722,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581320260,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581337241,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581343501,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581449764,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581460099,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579492468,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581204602,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581227658,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379492,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581396548,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581402845,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581513988,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581524195,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void vm_unacct_memory(long int pages)
```

```json
{
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579523049,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394740,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581415376,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581584841,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "mm/mmap.c:do_brk_flags"
      ]
    },
    {
      "addr": 18446744071581594649,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602407,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581722612,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581731457,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581566672,
      "name": "vm_unacct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void vm_unacct_memory(long int pages)
```

```json
{
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579504609,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:75",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581438255,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:75",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581458528,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:75",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581630841,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:75",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "mm/mmap.c:do_brk_flags"
      ]
    },
    {
      "addr": 18446744071581640665,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:75",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581649550,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:75",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:mremap_to"
      ],
      "caller_func": [
        "mm/mremap.c:move_vma"
      ]
    },
    {
      "addr": 18446744071581770708,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:75",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581779105,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:75",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612112,
      "name": "vm_unacct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581642416,
      "name": "vm_unacct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void vm_unacct_memory(long int pages)
```

```json
{
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579508056,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:75",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581458653,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:75",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479373,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:75",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581645703,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:75",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "mm/mmap.c:do_brk_flags"
      ]
    },
    {
      "addr": 18446744071581662235,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:75",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581670869,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:75",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:mremap_to"
      ],
      "caller_func": [
        "mm/mremap.c:move_vma"
      ]
    },
    {
      "addr": 18446744071581798145,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:75",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581807281,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:75",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581634688,
      "name": "vm_unacct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581663936,
      "name": "vm_unacct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void vm_unacct_memory(long int pages)
```

```json
{
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579580720,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581728916,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581733773,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581913710,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "mm/mmap.c:do_brk_flags"
      ]
    },
    {
      "addr": 18446744071581930603,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581940144,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:mremap_to"
      ],
      "caller_func": [
        "mm/mremap.c:move_vma"
      ]
    },
    {
      "addr": 18446744071582082546,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582092616,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902576,
      "name": "vm_unacct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581931840,
      "name": "vm_unacct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void vm_unacct_memory(long int pages)
```

```json
{
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579671419,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582107903,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_folio",
        "mm/shmem.c:shmem_alloc_and_acct_folio",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582114681,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582320142,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "mm/mmap.c:do_brk_flags"
      ]
    },
    {
      "addr": 18446744071582339368,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582349378,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582521250,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582307136,
      "name": "vm_unacct_memory",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579791167,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582582189,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_folio",
        "mm/shmem.c:shmem_alloc_and_acct_folio",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582588424,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582818810,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mas_align_munmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582840384,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582850511,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583039276,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff"
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
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579838975,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582789347,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_folio",
        "mm/shmem.c:shmem_alloc_and_acct_folio",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582795784,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583033201,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_vmi_align_munmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583055923,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583067159,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583247835,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:78",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff"
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
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579874997,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:82",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582958546,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:82",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_inode_unacct_blocks",
        "mm/shmem.c:shmem_inode_acct_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582970504,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:82",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583214567,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:82",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_vmi_align_munmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583237490,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:82",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583249092,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:82",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583482363,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:82",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff"
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
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490626080,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492593972,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492618012,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492786388,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492800352,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492804772,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__arm64_sys_mremap",
        "mm/mremap.c:__arm64_sys_mremap",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492936372,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492950484,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224704348,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3226448720,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 3226469096,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 3226601960,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 3226613916,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 3226617656,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 3226723336,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 3226733636,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283443900,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285907472,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285935268,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286154944,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286173376,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286180120,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286347840,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286363664,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271382588,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272622998,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272643374,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272757398,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272766692,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272769280,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272854348,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272865512,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579466132,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581173450,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581196506,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581348340,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581365396,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581371693,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581482724,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581492931,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
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
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579395092,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581120222,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581143258,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581292052,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581308900,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315101,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581425012,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581435171,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
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
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579466052,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581164650,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581187706,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581339540,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581356596,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581362893,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474036,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581484243,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
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
  "name": "vm_unacct_memory",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579497796,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581230933,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581250954,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:__vm_enough_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581403492,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581420516,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:mprotect_fixup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581426797,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581538818,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapoff"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581548685,
      "name": "vm_unacct_memory",
      "external": false,
      "loc": "include/linux/mman.h:71",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:frontswap_shrink"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void vm_unacct_memory(long int pages)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void vm_unacct_memory(long int pages)
```
</details>
</li>
</ul>
