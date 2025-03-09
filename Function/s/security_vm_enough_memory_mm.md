# Function: <code>security_vm_enough_memory_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582240672,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:216",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_setattr",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:insert_vm_struct",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/swapfile.c:SyS_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582240672,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582459344,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:217",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/swapfile.c:SyS_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582459344,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582551808,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:217",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/swapfile.c:SyS_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582551808,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582638704,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:788",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mcopy_atomic_pte",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/swapfile.c:SyS_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582638704,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582792752,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:738",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/swapfile.c:SYSC_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792752,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582990992,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:315",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_mm",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582990992,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583102576,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:797",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583102576,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583288112,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:796",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583288112,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583393328,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:830",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583393328,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583732720,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:973",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583732720,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583853040,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:975",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/mremap.c:move_vma",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583853040,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583877856,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:999",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/mremap.c:move_vma",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583877856,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584242784,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:999",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/mremap.c:move_vma",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584242784,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584849728,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:998",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_alloc_and_acct_folio",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:move_vma",
        "mm/swapfile.c:__do_sys_swapoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584849728,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585552336,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:996",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_alloc_and_acct_folio",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:expand_downwards",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:move_vma",
        "mm/swapfile.c:__do_sys_swapoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585552336,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585783120,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:1156",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_alloc_and_acct_folio",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:expand_downwards",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:move_vma",
        "mm/swapfile.c:__do_sys_swapoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585783120,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586031232,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:1199",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_inode_acct_blocks",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:expand_downwards",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:move_vma",
        "mm/swapfile.c:__do_sys_swapoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586031232,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495144672,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:830",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495144672,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228532392,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:830",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228532392,
      "name": "security_vm_enough_memory_mm",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289064608,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:830",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289064608,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274393528,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:830",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274393528,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583362064,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:830",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583362064,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583299168,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:830",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583299168,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583345840,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:830",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583345840,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int security_vm_enough_memory_mm(struct mm_struct * mm, long int pages)
```

```json
{
  "name": "security_vm_enough_memory_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583441024,
      "name": "security_vm_enough_memory_mm",
      "external": true,
      "loc": "security/security.c:830",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_charge",
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/frontswap.c:frontswap_shrink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583441024,
      "name": "security_vm_enough_memory_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
