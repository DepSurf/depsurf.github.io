# Function: <code>do_munmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580705872,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2532",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "mm/mmap.c:vm_munmap",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:SyS_brk",
        "mm/mmap.c:mmap_region",
        "mm/mremap.c:move_vma",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "ipc/shm.c:SyS_shmdt",
        "ipc/shm.c:SyS_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705872,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1152
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580819168,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2429",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:SyS_munmap",
        "mm/mmap.c:vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:SyS_brk",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "ipc/shm.c:SyS_shmdt",
        "ipc/shm.c:SyS_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580819168,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1138
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580884688,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2582",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:SyS_munmap",
        "mm/mmap.c:vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:SyS_brk",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "ipc/shm.c:SyS_shmdt",
        "ipc/shm.c:SyS_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580884688,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1106
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580929616,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2617",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:SyS_brk",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "ipc/shm.c:SyS_shmdt",
        "ipc/shm.c:SyS_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580929616,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1174
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581029360,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2635",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:SyS_brk",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "ipc/shm.c:SyS_shmdt",
        "ipc/shm.c:SyS_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029360,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1110
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581164064,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2690",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:vm_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581164064,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1087
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581248336,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2832",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581245472,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581323209,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2838",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319968,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581382553,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2843",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379200,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581578657,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2853",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_checked",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581584544,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581624287,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2916",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_checked",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581630544,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581648809,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2920",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581645424,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581916921,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2892",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581913440,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582323490,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2893",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582319824,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582817712,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2511",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582817712,
      "name": "do_munmap",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583031904,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2632",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583031904,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583213120,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2714",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583213120,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492789560,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2843",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "mm/mremap.c:__arm64_sys_mremap",
        "mm/mremap.c:__arm64_sys_mremap",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492786024,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226604984,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2843",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226601544,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286159280,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2843",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286154624,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272759810,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2843",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:move_vma",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272757048,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581351401,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2843",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581348048,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581295113,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2843",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581291760,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581342601,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2843",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581339248,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
int do_munmap(struct mm_struct * mm, long unsigned int start, size_t len, struct list_head * uf)
```

```json
{
  "name": "do_munmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581406537,
      "name": "do_munmap",
      "external": true,
      "loc": "mm/mmap.c:2843",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:move_vma",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:mmap_vmcore",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403200,
      "name": "do_munmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct list_head * uf</code>
</li>
</ul>
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
