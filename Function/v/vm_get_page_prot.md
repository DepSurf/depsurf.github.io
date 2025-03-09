# Function: <code>vm_get_page_prot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580696208,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:85",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__install_special_mapping"
      ],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/agp/frontend.c:agp_create_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580696208,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580810432,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:97",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/agp/frontend.c:agp_create_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580810432,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580875792,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:102",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/agp/frontend.c:agp_create_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580875792,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580931677,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:102",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot"
      ],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/agp/frontend.c:agp_create_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920624,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581031421,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:103",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot"
      ],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/agp/frontend.c:agp_create_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581020224,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581166181,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:110",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot"
      ],
      "caller_func": [
        "mm/mprotect.c:mprotect_fixup",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/agp/frontend.c:agp_create_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581155280,
      "name": "vm_get_page_prot",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581246229,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:110",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot"
      ],
      "caller_func": [
        "mm/mprotect.c:mprotect_fixup",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/agp/frontend.c:agp_create_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581235072,
      "name": "vm_get_page_prot",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581320794,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:112",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot"
      ],
      "caller_func": [
        "mm/mprotect.c:mprotect_fixup",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/agp/frontend.c:agp_create_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581309328,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581380026,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:106",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot"
      ],
      "caller_func": [
        "mm/mprotect.c:mprotect_fixup",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/agp/frontend.c:agp_create_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581367904,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581585370,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:109",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot"
      ],
      "caller_func": [
        "mm/mprotect.c:mprotect_fixup",
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mwriteprotect_range",
        "fs/exec.c:__bprm_mm_init",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/agp/frontend.c:agp_create_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581564576,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581631450,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:109",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot"
      ],
      "caller_func": [
        "mm/mprotect.c:mprotect_fixup",
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mwriteprotect_range",
        "fs/exec.c:__bprm_mm_init",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581610048,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581646314,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:115",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot"
      ],
      "caller_func": [
        "mm/mprotect.c:mprotect_fixup",
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mwriteprotect_range",
        "fs/exec.c:__bprm_mm_init",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581632672,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581914346,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:115",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot"
      ],
      "caller_func": [
        "mm/mprotect.c:mprotect_fixup",
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mwriteprotect_range",
        "fs/exec.c:__bprm_mm_init",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581900560,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579563680,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "arch/x86/mm/pgprot.c:7",
      "file": "arch/x86/mm/pgprot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup",
        "mm/userfaultfd.c:uffd_wp_range",
        "mm/userfaultfd.c:uffd_wp_range",
        "fs/exec.c:alloc_bprm",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579563680,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671360,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "arch/x86/mm/pgprot.c:35",
      "file": "arch/x86/mm/pgprot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup",
        "mm/userfaultfd.c:uffd_wp_range",
        "mm/userfaultfd.c:uffd_wp_range",
        "fs/exec.c:alloc_bprm",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671360,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579685296,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "arch/x86/mm/pgprot.c:35",
      "file": "arch/x86/mm/pgprot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup",
        "fs/exec.c:alloc_bprm",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685296,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579719824,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "arch/x86/mm/pgprot.c:35",
      "file": "arch/x86/mm/pgprot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup",
        "fs/exec.c:alloc_bprm",
        "drivers/video/fbdev/core/fb_io_fops.c:fb_io_mmap",
        "drivers/gpu/drm/drm_gem.c:drm_gem_mmap_obj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719824,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492786888,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:106",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vm_pgprot_modify"
      ],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492773488,
      "name": "vm_get_page_prot",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226602420,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:106",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot"
      ],
      "caller_func": [
        "fs/exec.c:__do_execve_file",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226590820,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286155676,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:106",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vm_pgprot_modify"
      ],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/agp/frontend.c:agp_create_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286139888,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272757782,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:106",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot"
      ],
      "caller_func": [
        "fs/exec.c:__do_execve_file",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272748768,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581348874,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:106",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot"
      ],
      "caller_func": [
        "mm/mprotect.c:mprotect_fixup",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/agp/frontend.c:agp_create_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581336752,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581292586,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:106",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot"
      ],
      "caller_func": [
        "mm/mprotect.c:mprotect_fixup",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/agp/frontend.c:agp_create_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581280464,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581340074,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:106",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot"
      ],
      "caller_func": [
        "mm/mprotect.c:mprotect_fixup",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/agp/frontend.c:agp_create_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581327952,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
pgprot_t vm_get_page_prot(long unsigned int vm_flags)
```

```json
{
  "name": "vm_get_page_prot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581404026,
      "name": "vm_get_page_prot",
      "external": true,
      "loc": "mm/mmap.c:106",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__install_special_mapping",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:vma_wants_writenotify",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mmap.c:vma_set_page_prot"
      ],
      "caller_func": [
        "mm/mprotect.c:mprotect_fixup",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/agp/frontend.c:agp_create_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581391920,
      "name": "vm_get_page_prot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
