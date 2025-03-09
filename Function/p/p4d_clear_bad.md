# Function: <code>p4d_clear_bad</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580953216,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:25",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/swapfile.c:unuse_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580953216,
      "name": "p4d_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void p4d_clear_bad(p4d_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581054960,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:26",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/swapfile.c:unuse_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581054960,
      "name": "p4d_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void p4d_clear_bad(p4d_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581193680,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:26",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/mprotect.c:change_protection",
        "mm/mremap.c:move_page_tables",
        "mm/swapfile.c:unuse_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581193680,
      "name": "p4d_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void p4d_clear_bad(p4d_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581276960,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:27",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/swapfile.c:unuse_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276960,
      "name": "p4d_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void p4d_clear_bad(p4d_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581351408,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:27",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351408,
      "name": "p4d_clear_bad",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581410912,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:27",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581410912,
      "name": "p4d_clear_bad",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581610992,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:28",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:apply_to_p4d_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_p4d_range",
        "mm/mprotect.c:change_p4d_range",
        "mm/mremap.c:get_old_pmd",
        "mm/pagewalk.c:walk_p4d_range",
        "mm/vmalloc.c:vunmap_p4d_range",
        "mm/swapfile.c:unuse_p4d_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581610992,
      "name": "p4d_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void p4d_clear_bad(p4d_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581658368,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:28",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:free_p4d_range",
        "mm/mprotect.c:change_p4d_range",
        "mm/mremap.c:get_old_pud",
        "mm/pagewalk.c:walk_p4d_range",
        "mm/vmalloc.c:vunmap_p4d_range",
        "mm/swapfile.c:unuse_p4d_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581658368,
      "name": "p4d_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void p4d_clear_bad(p4d_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581680176,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:28",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:free_p4d_range",
        "mm/mprotect.c:change_p4d_range",
        "mm/mremap.c:get_old_pud",
        "mm/pagewalk.c:walk_p4d_range",
        "mm/vmalloc.c:vunmap_range_noflush",
        "mm/swapfile.c:unuse_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581680176,
      "name": "p4d_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void p4d_clear_bad(p4d_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581949456,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:28",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:free_p4d_range",
        "mm/mprotect.c:change_p4d_range",
        "mm/mremap.c:get_old_pud",
        "mm/pagewalk.c:walk_p4d_range",
        "mm/vmalloc.c:vunmap_range_noflush",
        "mm/swapfile.c:unuse_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581949456,
      "name": "p4d_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void p4d_clear_bad(p4d_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582358896,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:29",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:free_p4d_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:get_old_pud",
        "mm/pagewalk.c:walk_p4d_range",
        "mm/vmalloc.c:vunmap_p4d_range",
        "mm/swapfile.c:unuse_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582358896,
      "name": "p4d_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void p4d_clear_bad(p4d_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582861168,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:29",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:free_p4d_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:get_old_pud",
        "mm/pagewalk.c:walk_p4d_range",
        "mm/vmalloc.c:vunmap_p4d_range",
        "mm/swapfile.c:unuse_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582861168,
      "name": "p4d_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void p4d_clear_bad(p4d_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583076672,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:31",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:free_p4d_range",
        "mm/mprotect.c:change_p4d_range",
        "mm/mremap.c:get_old_pud",
        "mm/pagewalk.c:walk_p4d_range",
        "mm/vmalloc.c:vunmap_p4d_range",
        "mm/swapfile.c:unuse_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583076672,
      "name": "p4d_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void p4d_clear_bad(p4d_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583258928,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:32",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:free_p4d_range",
        "mm/mprotect.c:change_p4d_range",
        "mm/mremap.c:get_old_pud",
        "mm/pagewalk.c:walk_p4d_range",
        "mm/vmalloc.c:vunmap_p4d_range",
        "mm/swapfile.c:unuse_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583258928,
      "name": "p4d_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void p4d_clear_bad(pgd_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492809936,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:27",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492809936,
      "name": "p4d_clear_bad",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void p4d_clear_bad(pgd_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226620912,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:27",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226620912,
      "name": "p4d_clear_bad",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void p4d_clear_bad(pgd_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286190096,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:27",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286190096,
      "name": "p4d_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void p4d_clear_bad(p4d_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272772532,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:27",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272772532,
      "name": "p4d_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void p4d_clear_bad(p4d_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581379760,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:27",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379760,
      "name": "p4d_clear_bad",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581323663,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:27",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323663,
      "name": "p4d_clear_bad",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581370960,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:27",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581370960,
      "name": "p4d_clear_bad",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void p4d_clear_bad(p4d_t * p4d)
```

```json
{
  "name": "p4d_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581434848,
      "name": "p4d_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:27",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434848,
      "name": "p4d_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void p4d_clear_bad(p4d_t * p4d)
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>p4d_t * p4d</code> ➡️ <code>pgd_t * p4d</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>p4d_t * p4d</code> ➡️ <code>pgd_t * p4d</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>p4d_t * p4d</code> ➡️ <code>pgd_t * p4d</code>
</li>
</ul>
</details>
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
