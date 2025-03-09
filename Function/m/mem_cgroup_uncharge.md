# Function: <code>mem_cgroup_uncharge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580943136,
      "name": "mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:5515",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580943136,
      "name": "mem_cgroup_uncharge",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090000,
      "name": "mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:5593",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090000,
      "name": "mem_cgroup_uncharge",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581165008,
      "name": "mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:5578",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165008,
      "name": "mem_cgroup_uncharge",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581212800,
      "name": "mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:5640",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581212800,
      "name": "mem_cgroup_uncharge",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581343168,
      "name": "mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:5737",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581343168,
      "name": "mem_cgroup_uncharge",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581490640,
      "name": "mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:5805",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581490640,
      "name": "mem_cgroup_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581576496,
      "name": "mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:6136",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:putback_inactive_pages",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581576496,
      "name": "mem_cgroup_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581687776,
      "name": "mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:6428",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__page_cache_release",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581687776,
      "name": "mem_cgroup_uncharge",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581761232,
      "name": "mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:6768",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_compound_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581761232,
      "name": "mem_cgroup_uncharge",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581980512,
      "name": "mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:6628",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__put_page",
        "mm/page_alloc.c:free_compound_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memremap.c:free_devmap_managed_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581980512,
      "name": "mem_cgroup_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582030720,
      "name": "mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:6888",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page_alloc.c:free_compound_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memremap.c:free_devmap_managed_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582030720,
      "name": "mem_cgroup_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582057376,
      "name": "mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:6743",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page_alloc.c:free_compound_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memremap.c:free_devmap_managed_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582057376,
      "name": "mem_cgroup_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581581699,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:703",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642287,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:703",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582013141,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:703",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_compound_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582312289,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:703",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582379193,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:703",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:delete_from_lru_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582424790,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:703",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:free_devmap_managed_page"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581935704,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:704",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582009628,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:704",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__put_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582439904,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:704",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_compound_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582797223,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:704",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582880467,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:704",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:delete_from_lru_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582940179,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:704",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:free_zone_device_page"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582362891,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:686",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582443707,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:686",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__folio_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582948960,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:686",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_compound_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583340009,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:686",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583430035,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:686",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:delete_from_lru_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583496781,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:686",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:free_zone_device_page"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582566191,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:699",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582649051,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:699",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__folio_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583166096,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:699",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_compound_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583651758,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:699",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:delete_from_lru_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583711789,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:699",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:free_zone_device_page"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582737042,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:708",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582820184,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:708",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__folio_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583349622,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:708",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:destroy_large_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583526726,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:708",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:free_huge_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583844880,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:708",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:delete_from_lru_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583912061,
      "name": "mem_cgroup_uncharge",
      "external": false,
      "loc": "include/linux/memcontrol.h:708",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:free_zone_device_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493215192,
      "name": "mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:6768",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__put_page",
        "mm/page_alloc.c:free_compound_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493215192,
      "name": "mem_cgroup_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226846224,
      "name": "mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:6768",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_compound_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226846224,
      "name": "mem_cgroup_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286727600,
      "name": "mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:6768",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_compound_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286727600,
      "name": "mem_cgroup_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272991592,
      "name": "mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:6768",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:__put_page",
        "mm/page_alloc.c:free_compound_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272991592,
      "name": "mem_cgroup_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581729968,
      "name": "mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:6768",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_compound_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581729968,
      "name": "mem_cgroup_uncharge",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581668736,
      "name": "mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:6768",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_compound_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668736,
      "name": "mem_cgroup_uncharge",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581721280,
      "name": "mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:6768",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_compound_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581721280,
      "name": "mem_cgroup_uncharge",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void mem_cgroup_uncharge(struct page * page)
```

```json
{
  "name": "mem_cgroup_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581789360,
      "name": "mem_cgroup_uncharge",
      "external": true,
      "loc": "mm/memcontrol.c:6768",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_compound_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581789360,
      "name": "mem_cgroup_uncharge",
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void mem_cgroup_uncharge(struct page * page)
```
</details>
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
