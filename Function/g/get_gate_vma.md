# Function: <code>get_gate_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578864448,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:298",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578864448,
      "name": "get_gate_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578864888,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:298",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578864816,
      "name": "get_gate_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578865000,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:298",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578864928,
      "name": "get_gate_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578864632,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:300",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578864560,
      "name": "get_gate_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578865224,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:306",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578865152,
      "name": "get_gate_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578867093,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:302",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:mem_init",
        "mm/gup.c:__get_user_pages",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578867024,
      "name": "get_gate_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578866837,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:295",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:mem_init",
        "mm/gup.c:__get_user_pages",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578866768,
      "name": "get_gate_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578867013,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:316",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:mem_init",
        "mm/gup.c:__get_user_pages",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578866944,
      "name": "get_gate_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578867141,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:316",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:mem_init",
        "mm/gup.c:__get_user_pages",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578867072,
      "name": "get_gate_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578870853,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:316",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:mem_init",
        "mm/gup.c:get_gate_page",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:vma_dump_size",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:vma_dump_size",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578870784,
      "name": "get_gate_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578867269,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:316",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:mem_init",
        "mm/gup.c:get_gate_page",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/coredump.c:vma_dump_size",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578867200,
      "name": "get_gate_vma",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578867109,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:316",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:mem_init",
        "mm/gup.c:get_gate_page",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/coredump.c:vma_dump_size",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578867040,
      "name": "get_gate_vma",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578868709,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:317",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:mem_init",
        "mm/gup.c:get_gate_page",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/coredump.c:vma_dump_size",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578868640,
      "name": "get_gate_vma",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578865141,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:317",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:mem_init",
        "mm/gup.c:get_gate_page",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/coredump.c:vma_dump_size",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578865056,
      "name": "get_gate_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578867861,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:317",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:mem_init",
        "mm/vmscan.c:should_skip_vma",
        "mm/gup.c:get_gate_page",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/coredump.c:vma_dump_size",
        "fs/proc/task_mmu.c:m_next",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578867760,
      "name": "get_gate_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578865733,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:317",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:mem_init",
        "mm/vmscan.c:should_skip_vma",
        "mm/gup.c:get_gate_page",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/coredump.c:vma_dump_size",
        "fs/proc/task_mmu.c:m_next",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578865632,
      "name": "get_gate_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578876245,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:317",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:mem_init",
        "mm/vmscan.c:should_skip_vma",
        "mm/gup.c:get_gate_page",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/coredump.c:vma_dump_size",
        "fs/proc/task_mmu.c:m_next",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578876144,
      "name": "get_gate_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "get_gate_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "get_gate_vma",
      "external": false,
      "loc": "include/linux/mm.h:2745",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_gate_vma",
      "external": false,
      "loc": "include/linux/mm.h:2745",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_gate_vma",
      "external": false,
      "loc": "include/linux/mm.h:2745",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_gate_vma",
      "external": false,
      "loc": "include/linux/mm.h:2745",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_gate_vma",
      "external": false,
      "loc": "include/linux/mm.h:2745",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_gate_vma",
      "external": false,
      "loc": "include/linux/mm.h:2745",
      "file": "fs/proc/task_mmu.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224417576,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/arm/kernel/process.c:342",
      "file": "arch/arm/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224417576,
      "name": "get_gate_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "get_gate_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "get_gate_vma",
      "external": false,
      "loc": "include/linux/mm.h:2745",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_gate_vma",
      "external": false,
      "loc": "include/linux/mm.h:2745",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_gate_vma",
      "external": false,
      "loc": "include/linux/mm.h:2745",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_gate_vma",
      "external": false,
      "loc": "include/linux/mm.h:2745",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_gate_vma",
      "external": false,
      "loc": "include/linux/mm.h:2745",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_gate_vma",
      "external": false,
      "loc": "include/linux/mm.h:2745",
      "file": "fs/proc/task_mmu.c",
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
  "name": "get_gate_vma",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "get_gate_vma",
      "external": false,
      "loc": "include/linux/mm.h:2745",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_gate_vma",
      "external": false,
      "loc": "include/linux/mm.h:2745",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_gate_vma",
      "external": false,
      "loc": "include/linux/mm.h:2745",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_gate_vma",
      "external": false,
      "loc": "include/linux/mm.h:2745",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_gate_vma",
      "external": false,
      "loc": "include/linux/mm.h:2745",
      "file": "fs/proc/task_mmu.c",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578867141,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:316",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:mem_init",
        "mm/gup.c:__get_user_pages",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578867072,
      "name": "get_gate_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578860709,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:316",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:mem_init",
        "mm/gup.c:__get_user_pages",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578860640,
      "name": "get_gate_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578867077,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:316",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:mem_init",
        "mm/gup.c:__get_user_pages",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578867008,
      "name": "get_gate_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```

```json
{
  "name": "get_gate_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578867429,
      "name": "get_gate_vma",
      "external": true,
      "loc": "arch/x86/entry/vsyscall/vsyscall_64.c:316",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:in_gate_area"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:mem_init",
        "mm/gup.c:__get_user_pages",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:mmap_region",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/proc/task_mmu.c:m_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578867360,
      "name": "get_gate_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct vm_area_struct * get_gate_vma(struct mm_struct * mm)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
