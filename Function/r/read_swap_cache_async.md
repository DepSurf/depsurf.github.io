# Function: <code>read_swap_cache_async</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580756992,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:389",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/madvise.c:SyS_madvise",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756992,
      "name": "read_swap_cache_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580879344,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:395",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:SyS_madvise",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580879344,
      "name": "read_swap_cache_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580947440,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:395",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:SyS_madvise",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580947440,
      "name": "read_swap_cache_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580992128,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:414",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_willneed",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580992128,
      "name": "read_swap_cache_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581096304,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:462",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_willneed",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:do_swap_page_readahead",
        "mm/swap_state.c:swapin_readahead",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096304,
      "name": "read_swap_cache_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237008,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:475",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_willneed",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237008,
      "name": "read_swap_cache_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581320432,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:437",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_willneed",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581320432,
      "name": "read_swap_cache_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581431520,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:448",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_willneed",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581431520,
      "name": "read_swap_cache_async",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581495760,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:448",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581495760,
      "name": "read_swap_cache_async",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581702430,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:465",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ],
      "caller_func": [
        "mm/madvise.c:madvise_willneed",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581702640,
      "name": "read_swap_cache_async",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581750151,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:557",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ],
      "caller_func": [
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581750368,
      "name": "read_swap_cache_async",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581777978,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:526",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ],
      "caller_func": [
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581778192,
      "name": "read_swap_cache_async",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582061077,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:521",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ],
      "caller_func": [
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592209044,
      "name": "read_swap_cache_async.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582061312,
      "name": "read_swap_cache_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll, struct swap_iocb * * plug)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582499454,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:529",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ],
      "caller_func": [
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593987111,
      "name": "read_swap_cache_async.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582499712,
      "name": "read_swap_cache_async",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll, struct swap_iocb * * plug)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583013406,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:513",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ],
      "caller_func": [
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596039102,
      "name": "read_swap_cache_async.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583013680,
      "name": "read_swap_cache_async",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll, struct swap_iocb * * plug)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583221971,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:528",
      "file": "mm/swap_state.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ],
      "caller_func": [
        "mm/madvise.c:shmem_swapin_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596561233,
      "name": "read_swap_cache_async.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583222416,
      "name": "read_swap_cache_async",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct folio * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, struct swap_iocb * * plug)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:536",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:shmem_swapin_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597466846,
      "name": "read_swap_cache_async.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583457728,
      "name": "read_swap_cache_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492915936,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:448",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__arm64_sys_madvise",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492915936,
      "name": "read_swap_cache_async",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226706900,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:448",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226706900,
      "name": "read_swap_cache_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286322608,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:448",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286322608,
      "name": "read_swap_cache_async",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272838112,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:448",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272838112,
      "name": "read_swap_cache_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581464608,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:448",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581464608,
      "name": "read_swap_cache_async",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581406784,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:448",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581406784,
      "name": "read_swap_cache_async",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581455808,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:448",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581455808,
      "name": "read_swap_cache_async",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct page * read_swap_cache_async(swp_entry_t entry, gfp_t gfp_mask, struct vm_area_struct * vma, long unsigned int addr, bool do_poll)
```

```json
{
  "name": "read_swap_cache_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581520240,
      "name": "read_swap_cache_async",
      "external": true,
      "loc": "mm/swap_state.c:448",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581520240,
      "name": "read_swap_cache_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool do_poll</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct swap_iocb * * plug</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool do_poll</code>
</li>
<li>
<b>Param reordered. </b>
<code>entry, gfp_mask, vma, addr, do_poll, plug</code> ➡️ <code>entry, gfp_mask, vma, addr, plug</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct page *</code> ➡️ <code>struct folio *</code>
</li>
</ul>
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
