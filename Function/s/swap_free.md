# Function: <code>swap_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580762096,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:838",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:alloc_swapdev_block",
        "kernel/power/swap.c:free_all_swap_pages",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:handle_mm_fault",
        "mm/swapfile.c:unuse_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580762096,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580884512,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:833",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580884512,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580952592,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:839",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952592,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580997872,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1138",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580997872,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581108896,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1173",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581108896,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581244944,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1173",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581244944,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581328480,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1213",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581328480,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581439440,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1313",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581439440,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581503664,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1313",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503664,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581711644,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1350",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581712400,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581759429,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1368",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581760320,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581786429,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1367",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581787280,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582070205,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1336",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582071328,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582509301,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1319",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582511232,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583028307,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1323",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583030240,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583237941,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1329",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583239296,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583469395,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1329",
      "file": "mm/swapfile.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:try_to_unmap_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583473824,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492925440,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1313",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492925440,
      "name": "swap_free",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226713984,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1313",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226713984,
      "name": "swap_free",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286333504,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1313",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286333504,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272845178,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1313",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272845178,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581472400,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1313",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581472400,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581414656,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1313",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page",
        "mm/swapfile.c:unuse_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414656,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463712,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1313",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463712,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void swap_free(swp_entry_t entry)
```

```json
{
  "name": "swap_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581528432,
      "name": "swap_free",
      "external": true,
      "loc": "mm/swapfile.c:1313",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:free_all_swap_pages",
        "kernel/power/swap.c:alloc_swapdev_block",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581528432,
      "name": "swap_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
