# Function: <code>vm_stat_account</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vm_stat_account(struct mm_struct * mm, long unsigned int flags, struct file * file, long int pages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580703120,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:1216",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:move_vma",
        "mm/mremap.c:SyS_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580703120,
      "name": "vm_stat_account",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580821320,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:2966",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580828336,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580886808,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3119",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580893872,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580931790,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3173",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580938800,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581031534,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3216",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038640,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581166237,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3273",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "kernel/fork.c:copy_mm",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581174656,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581246285,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3317",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581254976,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581320859,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3323",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581329776,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581380091,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3329",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581389184,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581585435,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3341",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581586304,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581631519,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3399",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:move_vma",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581632384,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581646383,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3370",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:move_vma",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581654064,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581914415,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3350",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:move_vma",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581922208,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582320818,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3343",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:move_vma",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582328848,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582819023,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3302",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mas_align_munmap",
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:move_vma",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582828640,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583033407,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3397",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:move_vma",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583043888,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583214787,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3485",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:expand_downwards"
      ],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:move_vma",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583225712,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492786920,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3329",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__arm64_sys_mremap",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492794128,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226602472,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3329",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226609972,
      "name": "vm_stat_account",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286155728,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3329",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286165360,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272757828,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3329",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272763366,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581348939,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3329",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358032,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581292651,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3329",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581301744,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581340139,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3329",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581349232,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void vm_stat_account(struct mm_struct * mm, vm_flags_t flags, long int npages)
```

```json
{
  "name": "vm_stat_account",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581404091,
      "name": "vm_stat_account",
      "external": true,
      "loc": "mm/mmap.c:3329",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:move_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413168,
      "name": "vm_stat_account",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long int npages</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file * file</code>
</li>
<li>
<b>Param removed. </b>
<code>long int pages</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int flags</code> ➡️ <code>vm_flags_t flags</code>
</li>
</ul>
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
