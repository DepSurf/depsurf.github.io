# Function: <code>__split_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580701728,
      "name": "__split_vma",
      "external": false,
      "loc": "mm/mmap.c:2451",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:split_vma",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580701728,
      "name": "__split_vma.isra.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
  "name": "__split_vma",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580816016,
      "name": "__split_vma",
      "external": false,
      "loc": "mm/mmap.c:2348",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816016,
      "name": "__split_vma.isra.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
  "name": "__split_vma",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580881488,
      "name": "__split_vma",
      "external": false,
      "loc": "mm/mmap.c:2501",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881488,
      "name": "__split_vma.isra.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580929072,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2536",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:split_vma",
        "mm/madvise.c:SyS_madvise",
        "mm/madvise.c:SyS_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580929072,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581028800,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2552",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:split_vma",
        "mm/madvise.c:SyS_madvise",
        "mm/madvise.c:SyS_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581028800,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581163568,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2612",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:split_vma",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581163568,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581243472,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2646",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:split_vma",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581243472,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581318016,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2651",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:split_vma",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581318016,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581377136,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2656",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:split_vma",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581377136,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581576384,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2665",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:split_vma",
        "mm/madvise.c:madvise_behavior",
        "mm/madvise.c:madvise_behavior"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581576384,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581621888,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2728",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:split_vma",
        "mm/madvise.c:madvise_behavior",
        "mm/madvise.c:madvise_behavior"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581621888,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581643248,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2732",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:split_vma",
        "mm/madvise.c:madvise_behavior",
        "mm/madvise.c:madvise_behavior"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581643248,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581911232,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2702",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:split_vma",
        "mm/madvise.c:madvise_behavior",
        "mm/madvise.c:madvise_behavior"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911232,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582317488,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2725",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:split_vma",
        "mm/madvise.c:madvise_update_vma",
        "mm/madvise.c:madvise_update_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582317488,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582814896,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2198",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_mas_align_munmap",
        "mm/mmap.c:do_mas_align_munmap",
        "mm/mmap.c:split_vma",
        "mm/madvise.c:madvise_update_vma",
        "mm/madvise.c:madvise_update_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582814896,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
int __split_vma(struct vma_iterator * vmi, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583028800,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2323",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:split_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583028800,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
int __split_vma(struct vma_iterator * vmi, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583201120,
      "name": "__split_vma",
      "external": false,
      "loc": "mm/mmap.c:2327",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:vma_modify",
        "mm/mmap.c:vma_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583201120,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 725
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
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492784032,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2656",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:split_vma",
        "mm/madvise.c:__arm64_sys_madvise",
        "mm/madvise.c:__arm64_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492784032,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226599744,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2656",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:split_vma",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:__se_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226599744,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286152016,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2656",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:split_vma",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:__se_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286152016,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272755648,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2656",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:split_vma",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:__se_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272755648,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581345984,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2656",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:split_vma",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345984,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581289696,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2656",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:split_vma",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581289696,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581337184,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2656",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:split_vma",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581337184,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
```

```json
{
  "name": "__split_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581401136,
      "name": "__split_vma",
      "external": true,
      "loc": "mm/mmap.c:2656",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:split_vma",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581401136,
      "name": "__split_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int __split_vma(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int addr, int new_below)
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vma_iterator * vmi</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct * mm</code>
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
