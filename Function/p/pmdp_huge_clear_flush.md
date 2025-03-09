# Function: <code>pmdp_huge_clear_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:__split_huge_page_pmd",
        "mm/huge_memory.c:__split_huge_page_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580747536,
      "name": "pmdp_huge_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:116",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580866656,
      "name": "pmdp_huge_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:116",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580908592,
      "name": "pmdp_huge_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580953568,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:122",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_mkclean_one",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580953568,
      "name": "pmdp_huge_clear_flush",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581055296,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:123",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_mkclean_one",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581055296,
      "name": "pmdp_huge_clear_flush",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581194016,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:123",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_mkclean_one",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194016,
      "name": "pmdp_huge_clear_flush",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581277296,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:124",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_mkclean_one",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581277296,
      "name": "pmdp_huge_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581351760,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:124",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351760,
      "name": "pmdp_huge_clear_flush",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581411264,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:124",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581411264,
      "name": "pmdp_huge_clear_flush",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581611392,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:133",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581611392,
      "name": "pmdp_huge_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581658720,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:133",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581658720,
      "name": "pmdp_huge_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581680528,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:133",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581680528,
      "name": "pmdp_huge_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581949808,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:133",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581949808,
      "name": "pmdp_huge_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582359328,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:134",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582359328,
      "name": "pmdp_huge_clear_flush",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582861664,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:134",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582861664,
      "name": "pmdp_huge_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583077168,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:136",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583077168,
      "name": "pmdp_huge_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583259424,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:137",
      "file": "mm/pgtable-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:move_pages_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583259424,
      "name": "pmdp_huge_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492810736,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:124",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492810736,
      "name": "pmdp_huge_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286191024,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:124",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286191024,
      "name": "pmdp_huge_clear_flush",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581380112,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:124",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581380112,
      "name": "pmdp_huge_clear_flush",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581322816,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:124",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322816,
      "name": "pmdp_huge_clear_flush",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581371312,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:124",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581371312,
      "name": "pmdp_huge_clear_flush",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_huge_clear_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581435200,
      "name": "pmdp_huge_clear_flush",
      "external": true,
      "loc": "mm/pgtable-generic.c:124",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581435200,
      "name": "pmdp_huge_clear_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
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
