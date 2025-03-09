# Function: <code>follow_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "follow_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580828145,
      "name": "follow_page",
      "external": false,
      "loc": "include/linux/mm.h:2113",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:break_ksm",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580879278,
      "name": "follow_page",
      "external": false,
      "loc": "include/linux/mm.h:2113",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:SyS_move_pages"
      ],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "follow_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580963728,
      "name": "follow_page",
      "external": false,
      "loc": "include/linux/mm.h:2237",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:break_ksm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581018323,
      "name": "follow_page",
      "external": false,
      "loc": "include/linux/mm.h:2237",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SyS_move_pages",
        "mm/migrate.c:do_pages_stat"
      ],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "follow_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580872431,
      "name": "follow_page",
      "external": false,
      "loc": "include/linux/mm.h:2223",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581035109,
      "name": "follow_page",
      "external": false,
      "loc": "include/linux/mm.h:2223",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:break_ksm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581092761,
      "name": "follow_page",
      "external": false,
      "loc": "include/linux/mm.h:2223",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SYSC_move_pages",
        "mm/migrate.c:do_pages_stat"
      ],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "follow_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580917426,
      "name": "follow_page",
      "external": false,
      "loc": "include/linux/mm.h:2328",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581082734,
      "name": "follow_page",
      "external": false,
      "loc": "include/linux/mm.h:2328",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:break_ksm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581139569,
      "name": "follow_page",
      "external": false,
      "loc": "include/linux/mm.h:2328",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SYSC_move_pages",
        "mm/migrate.c:do_pages_stat"
      ],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "follow_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581016838,
      "name": "follow_page",
      "external": false,
      "loc": "include/linux/mm.h:2437",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581194155,
      "name": "follow_page",
      "external": false,
      "loc": "include/linux/mm.h:2437",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:break_ksm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581261569,
      "name": "follow_page",
      "external": false,
      "loc": "include/linux/mm.h:2437",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:SYSC_move_pages",
        "mm/migrate.c:do_pages_stat"
      ],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "follow_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581151305,
      "name": "follow_page",
      "external": false,
      "loc": "include/linux/mm.h:2571",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581339084,
      "name": "follow_page",
      "external": false,
      "loc": "include/linux/mm.h:2571",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:break_ksm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581408263,
      "name": "follow_page",
      "external": false,
      "loc": "include/linux/mm.h:2571",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:do_pages_stat"
      ],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct page * follow_page(struct vm_area_struct * vma, long unsigned int address, unsigned int foll_flags)
```

```json
{
  "name": "follow_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581188400,
      "name": "follow_page",
      "external": true,
      "loc": "mm/gup.c:442",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:do_pages_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188400,
      "name": "follow_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct page * follow_page(struct vm_area_struct * vma, long unsigned int address, unsigned int foll_flags)
```

```json
{
  "name": "follow_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581260944,
      "name": "follow_page",
      "external": true,
      "loc": "mm/gup.c:559",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581260944,
      "name": "follow_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct page * follow_page(struct vm_area_struct * vma, long unsigned int address, unsigned int foll_flags)
```

```json
{
  "name": "follow_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581319616,
      "name": "follow_page",
      "external": true,
      "loc": "mm/gup.c:558",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319616,
      "name": "follow_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct page * follow_page(struct vm_area_struct * vma, long unsigned int address, unsigned int foll_flags)
```

```json
{
  "name": "follow_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581513216,
      "name": "follow_page",
      "external": true,
      "loc": "mm/gup.c:792",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581513216,
      "name": "follow_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct page * follow_page(struct vm_area_struct * vma, long unsigned int address, unsigned int foll_flags)
```

```json
{
  "name": "follow_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581553776,
      "name": "follow_page",
      "external": true,
      "loc": "mm/gup.c:756",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:do_pages_stat_array",
        "mm/migrate.c:add_page_for_migration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581553776,
      "name": "follow_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct page * follow_page(struct vm_area_struct * vma, long unsigned int address, unsigned int foll_flags)
```

```json
{
  "name": "follow_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581576656,
      "name": "follow_page",
      "external": true,
      "loc": "mm/gup.c:841",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:split_huge_pages_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581576656,
      "name": "follow_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct page * follow_page(struct vm_area_struct * vma, long unsigned int address, unsigned int foll_flags)
```

```json
{
  "name": "follow_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581841312,
      "name": "follow_page",
      "external": true,
      "loc": "mm/gup.c:864",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:split_huge_pages_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581841312,
      "name": "follow_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
struct page * follow_page(struct vm_area_struct * vma, long unsigned int address, unsigned int foll_flags)
```

```json
{
  "name": "follow_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582233888,
      "name": "follow_page",
      "external": true,
      "loc": "mm/gup.c:885",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:split_huge_pages_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582233888,
      "name": "follow_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
struct page * follow_page(struct vm_area_struct * vma, long unsigned int address, unsigned int foll_flags)
```

```json
{
  "name": "follow_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582724272,
      "name": "follow_page",
      "external": true,
      "loc": "mm/gup.c:812",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:split_huge_pages_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582724272,
      "name": "follow_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
struct page * follow_page(struct vm_area_struct * vma, long unsigned int address, unsigned int foll_flags)
```

```json
{
  "name": "follow_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582940768,
      "name": "follow_page",
      "external": true,
      "loc": "mm/gup.c:842",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:split_huge_pages_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582940768,
      "name": "follow_page",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct page * follow_page(struct vm_area_struct * vma, long unsigned int address, unsigned int foll_flags)
```

```json
{
  "name": "follow_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583115984,
      "name": "follow_page",
      "external": true,
      "loc": "mm/gup.c:837",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:split_huge_pages_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583115984,
      "name": "follow_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
struct page * follow_page(struct vm_area_struct * vma, long unsigned int address, unsigned int foll_flags)
```

```json
{
  "name": "follow_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492725736,
      "name": "follow_page",
      "external": true,
      "loc": "mm/gup.c:558",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492725736,
      "name": "follow_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct page * follow_page(struct vm_area_struct * vma, long unsigned int address, unsigned int foll_flags)
```

```json
{
  "name": "follow_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226556632,
      "name": "follow_page",
      "external": true,
      "loc": "mm/gup.c:558",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:break_ksm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226556632,
      "name": "follow_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct page * follow_page(struct vm_area_struct * vma, long unsigned int address, unsigned int foll_flags)
```

```json
{
  "name": "follow_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286071680,
      "name": "follow_page",
      "external": true,
      "loc": "mm/gup.c:558",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286071680,
      "name": "follow_page",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct page * follow_page(struct vm_area_struct * vma, long unsigned int address, unsigned int foll_flags)
```

```json
{
  "name": "follow_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272717686,
      "name": "follow_page",
      "external": true,
      "loc": "mm/gup.c:558",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:break_ksm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272717686,
      "name": "follow_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
struct page * follow_page(struct vm_area_struct * vma, long unsigned int address, unsigned int foll_flags)
```

```json
{
  "name": "follow_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581288464,
      "name": "follow_page",
      "external": true,
      "loc": "mm/gup.c:558",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581288464,
      "name": "follow_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct page * follow_page(struct vm_area_struct * vma, long unsigned int address, unsigned int foll_flags)
```

```json
{
  "name": "follow_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581234272,
      "name": "follow_page",
      "external": true,
      "loc": "mm/gup.c:558",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581234272,
      "name": "follow_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct page * follow_page(struct vm_area_struct * vma, long unsigned int address, unsigned int foll_flags)
```

```json
{
  "name": "follow_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581279664,
      "name": "follow_page",
      "external": true,
      "loc": "mm/gup.c:558",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581279664,
      "name": "follow_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
struct page * follow_page(struct vm_area_struct * vma, long unsigned int address, unsigned int foll_flags)
```

```json
{
  "name": "follow_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581343584,
      "name": "follow_page",
      "external": true,
      "loc": "mm/gup.c:558",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581343584,
      "name": "follow_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct page * follow_page(struct vm_area_struct * vma, long unsigned int address, unsigned int foll_flags)
```
</details>
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
