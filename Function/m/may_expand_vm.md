# Function: <code>may_expand_vm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int may_expand_vm(struct mm_struct * mm, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580705095,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3007",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580713344,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580822112,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:2943",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580822112,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580887600,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3096",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580887600,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580932544,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3150",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932544,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581032304,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3193",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581032304,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3248",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581175633,
      "name": "may_expand_vm.cold.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071581166976,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581247096,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3292",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581255953,
      "name": "may_expand_vm.cold.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071581247024,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581321704,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3298",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581330775,
      "name": "may_expand_vm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071581321632,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581380936,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3304",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581390183,
      "name": "may_expand_vm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071581380864,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581578432,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3316",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581567712,
      "name": "may_expand_vm.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071581587303,
      "name": "may_expand_vm.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071581586208,
      "name": "may_expand_vm",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581623952,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3374",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581613152,
      "name": "may_expand_vm.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071591328287,
      "name": "may_expand_vm.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071581632288,
      "name": "may_expand_vm",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581647192,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3345",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591270521,
      "name": "may_expand_vm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071581647120,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581915280,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3325",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:mremap_to",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592200278,
      "name": "may_expand_vm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    },
    {
      "addr": 18446744071581915184,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3318",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593976902,
      "name": "may_expand_vm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    },
    {
      "addr": 18446744071582321600,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3277",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:expand_downwards",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596032928,
      "name": "may_expand_vm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071582819824,
      "name": "may_expand_vm",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3372",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:expand_downwards",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596554878,
      "name": "may_expand_vm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071583034304,
      "name": "may_expand_vm",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3460",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:expand_downwards",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597458983,
      "name": "may_expand_vm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071583215664,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492787672,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3304",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492787672,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226603156,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3304",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226603156,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286156848,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3304",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286156848,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272758354,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3304",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272758354,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581349784,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3304",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581359031,
      "name": "may_expand_vm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071581349712,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581293496,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3304",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581302743,
      "name": "may_expand_vm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071581293424,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581340984,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3304",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581350231,
      "name": "may_expand_vm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071581340912,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool may_expand_vm(struct mm_struct * mm, vm_flags_t flags, long unsigned int npages)
```

```json
{
  "name": "may_expand_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581404936,
      "name": "may_expand_vm",
      "external": true,
      "loc": "mm/mmap.c:3304",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:vma_to_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414167,
      "name": "may_expand_vm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071581404864,
      "name": "may_expand_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
<code>vm_flags_t flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, npages</code> ➡️ <code>mm, flags, npages</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
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
