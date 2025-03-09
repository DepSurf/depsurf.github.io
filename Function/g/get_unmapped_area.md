# Function: <code>get_unmapped_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580697680,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2007",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580697680,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580812160,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:1896",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580812160,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580877520,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2049",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580877520,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580922192,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2071",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922192,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581021808,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2087",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021808,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581156512,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2147",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:vma_expandable",
        "mm/mremap.c:mremap_to"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581156512,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581236304,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2182",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:vma_expandable",
        "mm/mremap.c:mremap_to"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581236304,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581310576,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2183",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:vma_expandable",
        "mm/mremap.c:mremap_to"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581310576,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581369120,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2191",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:vma_expandable",
        "mm/mremap.c:mremap_to"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581369120,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581567872,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2190",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:xol_add_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:mremap_to"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581567872,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581613312,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2256",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:xol_add_vma",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:mremap_to"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581613312,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581635728,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2260",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:mremap_to"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581635728,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581903568,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2229",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:mremap_to"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581903568,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582307744,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2257",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582307744,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582805216,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:1759",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:xol_add_vma",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:check_brk_limits",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582805216,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583019376,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:1787",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:xol_add_vma",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:check_brk_limits",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583019376,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583199424,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:1814",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:xol_add_vma",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:check_brk_limits",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583199424,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492774624,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2191",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/vdso.c:arch_setup_additional_pages",
        "arch/arm64/kernel/vdso.c:aarch32_setup_additional_pages",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:__arm64_sys_mremap",
        "mm/mremap.c:__arm64_sys_mremap",
        "mm/mremap.c:__arm64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492774624,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226604484,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2191",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mmap"
      ],
      "caller_func": [
        "arch/arm/kernel/process.c:arch_setup_additional_pages",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:__se_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226592664,
      "name": "get_unmapped_area.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 3226592848,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286141744,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2191",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/vdso.c:arch_setup_additional_pages",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:__se_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286141744,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272749754,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2191",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/vdso.c:arch_setup_additional_pages",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:__se_sys_mremap",
        "mm/mremap.c:__se_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272749754,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581337968,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2191",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:vma_expandable",
        "mm/mremap.c:mremap_to"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581337968,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581281680,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2191",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:vma_expandable",
        "mm/mremap.c:mremap_to"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581281680,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581329168,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2191",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:vma_expandable",
        "mm/mremap.c:mremap_to"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581329168,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
long unsigned int get_unmapped_area(struct file * file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581393248,
      "name": "get_unmapped_area",
      "external": true,
      "loc": "mm/mmap.c:2191",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "kernel/events/uprobes.c:__create_xol_area",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mmap",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "mm/mremap.c:vma_expandable",
        "mm/mremap.c:mremap_to"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581393248,
      "name": "get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
