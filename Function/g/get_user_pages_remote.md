# Function: <code>get_user_pages_remote</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long int get_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, int write, int force, struct page * * pages, struct vm_area_struct * * vmas)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580769696,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:961",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:__access_remote_vm",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580769696,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
long int get_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580835168,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:964",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:__access_remote_vm",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580835168,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
long int get_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580877776,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:1045",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:__access_remote_vm",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580877776,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
long int get_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580973072,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:1070",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:__access_remote_vm",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580973072,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
long int get_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581107136,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:1076",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:__access_remote_vm",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581107136,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
long int get_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581187040,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:1101",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "mm/memory.c:__access_remote_vm",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581187040,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
long int get_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581257584,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:1156",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "mm/memory.c:__access_remote_vm",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581257584,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 559
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
long int get_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581316256,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:1159",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "mm/memory.c:__access_remote_vm",
        "security/tomoyo/domain.c:tomoyo_dump_page",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581316256,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 559
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
long int get_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581509632,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:1924",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:is_trap_at_addr",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "mm/memory.c:__access_remote_vm",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581509632,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
long int get_user_pages_remote(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581549680,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:1788",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:is_trap_at_addr",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "mm/memory.c:__access_remote_vm",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581549680,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
long int get_user_pages_remote(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581572800,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:1854",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "mm/memory.c:__access_remote_vm",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572800,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
long int get_user_pages_remote(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581837408,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:1942",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "mm/memory.c:__access_remote_vm",
        "mm/rmap.c:make_device_exclusive_range",
        "fs/exec.c:get_arg_page",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581837408,
      "name": "get_user_pages_remote",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long int get_user_pages_remote(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582229264,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:2131",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "mm/memory.c:__access_remote_vm",
        "mm/rmap.c:make_device_exclusive_range",
        "fs/exec.c:get_arg_page",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582229264,
      "name": "get_user_pages_remote",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
long int get_user_pages_remote(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582718624,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:2176",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "mm/memory.c:__access_remote_vm",
        "mm/rmap.c:make_device_exclusive_range",
        "fs/exec.c:get_arg_page",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582718624,
      "name": "get_user_pages_remote",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
long int get_user_pages_remote(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582930656,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:2320",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "mm/memory.c:__access_remote_vm",
        "mm/rmap.c:make_device_exclusive_range",
        "fs/exec.c:get_arg_page",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582930656,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 962
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
long int get_user_pages_remote(struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583105168,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:2338",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "mm/memory.c:__access_remote_vm",
        "mm/rmap.c:make_device_exclusive_range",
        "fs/exec.c:get_arg_page",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583105168,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1203
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
long int get_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492722312,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:1159",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:is_trap_at_addr",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "mm/memory.c:__access_remote_vm",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492722312,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
long int get_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226553280,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:1159",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "mm/memory.c:__access_remote_vm",
        "fs/exec.c:copy_strings",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226553280,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
long int get_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286067088,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:1159",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "mm/memory.c:__access_remote_vm",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286067088,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
long int get_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272715318,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:1159",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "fs/exec.c:copy_strings",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272715318,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
long int get_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581285104,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:1159",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "mm/memory.c:__access_remote_vm",
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581285104,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 559
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
long int get_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581230912,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:1159",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "mm/memory.c:__access_remote_vm",
        "security/tomoyo/domain.c:tomoyo_dump_page",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581230912,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 559
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
long int get_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581276304,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:1159",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "mm/memory.c:__access_remote_vm",
        "security/tomoyo/domain.c:tomoyo_dump_page",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276304,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 559
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
long int get_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page * * pages, struct vm_area_struct * * vmas, int * locked)
```

```json
{
  "name": "get_user_pages_remote",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581340224,
      "name": "get_user_pages_remote",
      "external": true,
      "loc": "mm/gup.c:1159",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "mm/memory.c:__access_remote_vm",
        "security/tomoyo/domain.c:tomoyo_dump_page",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581340224,
      "name": "get_user_pages_remote",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 559
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
long int get_user_pages_remote(struct task_struct * tsk, struct mm_struct * mm, long unsigned int start, long unsigned int nr_pages, int write, int force, struct page * * pages, struct vm_area_struct * * vmas)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int gup_flags</code>
</li>
<li>
<b>Param added. </b>
<code>int * locked</code>
</li>
<li>
<b>Param removed. </b>
<code>int write</code>
</li>
<li>
<b>Param removed. </b>
<code>int force</code>
</li>
<li>
<b>Param reordered. </b>
<code>tsk, mm, start, nr_pages, write, force, pages, vmas</code> ➡️ <code>tsk, mm, start, nr_pages, gup_flags, pages, vmas, locked</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct * tsk</code>
</li>
<li>
<b>Param reordered. </b>
<code>tsk, mm, start, nr_pages, gup_flags, pages, vmas, locked</code> ➡️ <code>mm, start, nr_pages, gup_flags, pages, vmas, locked</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct * * vmas</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, start, nr_pages, gup_flags, pages, vmas, locked</code> ➡️ <code>mm, start, nr_pages, gup_flags, pages, locked</code>
</li>
</ul>
</details>
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
